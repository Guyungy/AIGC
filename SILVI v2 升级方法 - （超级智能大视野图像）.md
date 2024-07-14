![](@%E9%99%84%E4%BB%B6/c8a0f4e5f0d6ab7c4f9b87eda10e3e85_MD5.jpeg)

https://civitai.com/articles/5834/silvi-v2-upscale-method-super-inteligence-large-vision-image

人工智能图像生成是一个迷人的领域。从我第一次使用它的那一刻起，我就深深地爱上了它，我知道它有着不可思议的潜力，尽管当时的结果存在许多错误和低分辨率。我最初尝试的事情之一是获取那些分辨率很低的照片的新“改进”版本。使用img2img，我可以使用一张参考照片，并通过一些提示和参数，通过AI的生成能力获得一些改进。但是存在一个问题：随着图像添加更多细节，人物原始特征越来越扭曲，变得无法辨认。我开始着迷于解决这个问题。

我花费了数小时测试不同的分辨率，改变去噪值，cfg等等…… 当Automatic1111集成了ControlNet模块后，我开始测试它，虽然我可以更好地控制最终结果，但图像的独特特征仍然丢失。

几个月前，我开始取得非常好的结果，并最终在reddit上制作了关于第一个版本SILVI的工作流程。目前，我大大改进了之前的方法，我认为我正在获得令人难以置信的结果，我想与你们分享。

![](@%E9%99%84%E4%BB%B6/89e85d478c3a4e6614535969d2d1a1d6_MD5.jpeg)

也许有些方法可以达到类似的结果，但它们经常会产生幻觉（例如在不应该有的地方生成眼睛或头发）。当前版本的SILVI允许通过细节上采样器在细节上非常有创意，同时避免了这些幻觉的产生。

在开发这种方法时，我其中一个执念是能够在缩放面部时保持特征，因为一些方法在在细节上有创意时，会失去人物的特征，使其与原始的不同。SILVI通过引入大量细节来保持这些特征。

该方法可以通过ControlNet模块的参数进行修改，我们可以控制上采样器在创意上的表现。

准备工作
我们需要准备以下内容：

- 更新后的Automatic1111
- 一个1.5版本的模型（我在这里使用Juggernaut Reborn）（https://civitai.com/models/46422/juggernaut）- SILVI使用SD 1.5模型，因为SDXL ControlNet模块给我的结果不理想。
- 4xFFHQDAT上采样器（https://openmodeldb.info/models/4x-FFHQDAT）
- 适用于SD版本1.5的Lora LCM（https://civitai.com/api/download/models/223551）- 这个Lora必须放置在其对应的LORA模型文件夹中。

首先，我们将转到img2img选项卡并加载要缩放的图像。然后按照以下步骤进行操作：

1. 选择检查点和VAE

![](@%E9%99%84%E4%BB%B6/8aca92f9602b2049b51a0f1187543cef_MD5.jpeg)
2. 选择采样方法和步数
![](@%E9%99%84%E4%BB%B6/1b4bd7eab3ab6b28e7332b85cee8ca97_MD5.jpeg)
3. 选择大小（768x768可以得到良好的结果）
这个大小将被SD UPSCALE脚本用来生成瓦片图像

4. 选择CFG比例 3
5. 选择去噪强度 1

去噪强度必须设置为最大，这样上采样器在细节上可以有创意
ControlNet模块负责控制，以确保不会出现幻觉或者伪影

6. 选择第一个ControlNet模块
![](@%E9%99%84%E4%BB%B6/065cc55abbcc6740fb0568fc4bbd9598_MD5.jpeg)

控制权重值控制了缩放器细节笔画的创造力。应始终保持在此值。通过将结束控制步骤值修改为此模块的0.7到0.8之间，我们可以在物体和构图中引入大量创意，但在大多数情况下，特征的保真度会丧失。（KREA AI或MAGNIFIC AI风格）。

7. 选择第二个ControlNet
[Open: Pasted image 20240630015708.png](@%E9%99%84%E4%BB%B6/cb7b06b1f464b2cf5c9464bf5f7921a7_MD5.jpeg)
![](@%E9%99%84%E4%BB%B6/cb7b06b1f464b2cf5c9464bf5f7921a7_MD5.jpeg)

8. 选择第三个ControlNet模块
9. 选择SD增强脚本并设置它