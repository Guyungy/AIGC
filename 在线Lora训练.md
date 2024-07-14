
F:\sd-webui-aki-v4\extensions\sd-webui-additional-networks\models\lora

## 本期视频链接
1. colab训练链接：https://github.com/Linaqruf/kohya-trainer
2. 训练程序：https://colab.research.google.com/drive/1WYVOnGiyzVUpEDoXNW1S832r-BVsltCg
3. 训练集标签编辑器：[https://github.com/toshiaki1729/stabl...](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqa0cteTlPaW5rOUVZTmg1aG84VlJoQ1JSOWc4d3xBQ3Jtc0tuQlBsVXk5ci1RYVc3cEhDdG9Ea1dsdUxVQng2R1lZR0xtSmNveDczSDlDaWJGcEtEZHlnTGJpSUdBeVNwcVNzWWM5Vmd5eGpfd2E5MTRwcUxaMExLdXJNZlNUZTQwcGJnOS1uOFNzZERNMDlFelh6Yw&q=https%3A%2F%2Fgithub.com%2Ftoshiaki1729%2Fstable-diffusion-webui-dataset-tag-editor&v=fH1jf8juA8Y) 
4. 批量调整图片尺寸：[https://www.birme.net/?target_width=5...](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbGFJMkhjOUdVaXZhQlUzT01ESnZoWlhlXzdkd3xBQ3Jtc0tsS0lqWldDM0pxdzAwV2hKNFpxaUs2eWY5V3FFczdkQkNKaTEzMHVwWi1KVWY1TmVrSF82V0hKV3BscDUwaGhSRW9VX0RmaXRrc3EwaTd1eUhReG5xcE9Wb1poaHQxTmQxWElITlJmc3o5c1plUy1abw&q=https%3A%2F%2Fwww.birme.net%2F%3Ftarget_width%3D512%26target_height%3D512&v=fH1jf8juA8Y) 
5. 批量调整图片格式：[https://www.wdku.net/image/imageformat](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbVYyeFlDZXdJSDNsRFdielp4YTlwVXV0Rk9JZ3xBQ3Jtc0tsank4UElRYXZZdTNrR2VnR09rWnhSRG9ia1pXZk9zTjg2b1dOUmE4YzRYUEZXMldxSDhNNEd0LUtzZ3BRdFEyV0oySFNnQy10eldETHlPLVZnTjZZZHV6TVlaYUVQSTc2eExjLWtCM0MtdTd1MTJwVQ&q=https%3A%2F%2Fwww.wdku.net%2Fimage%2Fimageformat&v=fH1jf8juA8Y) 

## SD使用相关链接
1. 使用Colab 搭建Stable Diffusion的链接： [https://github.com/camenduru/stable-d...](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqblUyVjZBNGVMcGlDd0J3MXdmRk1fTldaVFM4UXxBQ3Jtc0trbDJxM19yQzUxeVVfQncydFFkeDZwWkljOTd0MmJWWVBSSk5ETFFVX3dOMjhzV3FzQW83TmVXSXcyTURxT0JGdFdUZFpNZXJZc3NDNUtZcEVtTUVLSjlieGhIdWZuTmJleWlIMlVRRVdGSUg0LTN3NA&q=https%3A%2F%2Fgithub.com%2Fcamenduru%2Fstable-diffusion-webui-colab&v=fH1jf8juA8Y)
2. 使用Colab 搭建Stable Diffusion的教程：    [![](https://www.gstatic.com/youtube/img/watch/yt_favicon.png) • 【SD教程】用Colab一键免费搭...](https://www.youtube.com/watch?v=u6LWc1y4e0Y&t=3s)   
3. 模型下载网站：[https://civitai.com/](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqa2ZQSHBFelN3dUg1OXJ1SUFSbFRicXhhUDItUXxBQ3Jtc0trMnM1eE90aVgzcTZoa1ZkbjF4Y0dLeUV1NnNRWGc2Q2FKV1VHc2FsdjU1OE5lQ1JCLWxsQjBpN0hJbC1rSEJ0eG9ETHpNVElkZGdLS0p5WjQxX1FScV9uNElmeng0dzVUb0loeDRFUTlxYzVQN0VFaw&q=https%3A%2F%2Fcivitai.com%2F&v=fH1jf8juA8Y)

## 安装插件
  Dataset Tag Edito
  WD 1.4 标签器（Tagger）

https://colab.research.google.com/drive/1WYVOnGiyzVUpEDoXNW1S832r-BVsltCg
lora
SD1.5 512
SD2.*  768

## 运行
打完标签之后

运行训练的程序
https://colab.research.google.com/drive/1WYVOnGiyzVUpEDoXNW1S832r-BVsltCg#scrollTo=_u3q60di584x

1. 勾选mount_drive 然后点击运行![[file/Pasted image 20230712162045.png]]
2. 选择基础模型  Stable diffusion 1.5就可以![[file/Pasted image 20230712162207.png]]
3. 2.2 是指如果不用2.1提供的模型 也可以选择其他模型 粘贴链接就可以 如果不需要就跳过![[file/Pasted image 20230712162233.png]]
4. 2.3选择VAE，选择![[file/Pasted image 20230712162334.png]]
5. 3.1是准备训练数据，只需要运行，然后回建立文件夹，直接运行，然后左侧有目录![[file/Pasted image 20230712162354.png]]
6. 把处理集全部上传到Train data
7. 5.1训练参数 最后的钩子要勾![[file/Pasted image 20230712162620.png]]
8. 5.2训练参数 第一个布数![[file/Pasted image 20230712162727.png]]
9. 5.3直接运行 不用修改
10. 5.4 是训练设置10![[file/Pasted image 20230712162905.png]]
11.设置为1 ![[file/Pasted image 20230712162930.png]]
5.5直接运行，部署三四千效果好