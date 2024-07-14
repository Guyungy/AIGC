## 标题：
{DD} Deepthroat frames for gif

## 链接：
https://civitai.com/models/23464/dd-deepthroat-frames-for-gif

## 触发词：
2x2frames,3x3frames,

## 介绍：
<h1>Genereal description</h1><p>I thought it would be awesome to create a template for gifs. This lora should help with that. It should create some almost identical captions of a girl who are performing a fellatio.</p><p>Enjoy)</p><p>Feel free to ask any questions here in comments, or in <a target="_blank" rel="ugc" href="https://discord.gg/9My32sKEAK">my discord channel</a>.</p><p>Also I am making games with AI arts. They will be free in the future, but if you want to participate in making or have an early access - you can <a target="_blank" rel="ugc" href="https://www.patreon.com/aDDont">support me on patreon</a>)</p><p>Also <a target="_blank" rel="ugc" href="https://civitai.com/user/eq2bcknatagzqbylcjob"><strong>eq2bcknatagzqbylcjob</strong></a> (many thanks to him) mad a really cool <a target="_blank" rel="ugc" href="https://drive.google.com/file/d/13omJ60a3tofoCh_vNJkSCxDZ7bVp8ypV/view?usp=sharing">script </a>that will help with splitting the image into frames.</p><p>And <a target="_blank" rel="ugc" href="https://civitai.com/user/DigitalDreamer"><strong>DigitalDreamer </strong></a>(many thanks to him) made a <a target="_blank" rel="ugc" href="https://pastebin.com/raw/dqsMyquZ">script</a> that may help to make gifs inside AUTOMATIC1111. Just place it inside scripts folder and restart UI. You'll find it in the UI down bellow in "scripts" dropdown. Use 2 when you made 2x2frames, and 3 for 3x3frames. It will make a gif and put it in your outputs folder.</p><p><strong>tags to trigger</strong></p><p>4bj, pov, 2x2 frames, 3x3frames</p><p><strong>Optional tags</strong></p><p>fellatio, blowjob, cum, cum in mouth, cum from nose</p><h1>How to use</h1><p>If you can't get anything good - here is the <a target="_blank" rel="ugc" href="https://civitai.com/models/60211/dd-how-to-make-gifs-from-my-loras">tutorial</a>.</p><h1>Versions</h1><p>v4OT</p><p>*OT - stands for over trained.</p><p>A lot of people are strugling with the frames set, so I made it overfitted. Hope this helps.</p><p>Use lower weight of the Lora if you want to stick closer to the model's original style.</p><p>v3</p><p>Retrained, borders are now gone. Now it can generate stable grids with 768 and even 1024. If you are strugling with receiving a grid - use <strong>2x2frames </strong>tag (<strong>3x3frames </strong>is kinda working to, but meh).</p><p>If you are still unable to generate grid - use controlNet for guidence.</p><p>I tried to make a gif with new approach - you can inpaint a part of the picture, like one of the frames, and use the same seed, but high denoising strength (I used even 1). Use 'latent noice' for more variability or 'original', if you want something close to the original frame.</p><p>Could be better, but it's ok, I think)</p><p>v2</p><p>Retrained, works better. Now works with character Loras. I tried to use it with my Viv character - results is in the examples.</p><p>*Tends to create photorealistic pics</p><p>v1</p><p>Basic version</p>

## 版本(4bj_v4_OT)介绍：
<p>Over fitting model, for those who struggle with making a frames set</p>

## 示例：
================\< 1 \>================
预览图: 
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1b86283b-ddad-421f-847f-ad292d6a875c/width=450/714558.jpeg)
该图无参数

================\< 2 \>================
预览图: 
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3256ae56-3797-4a18-998d-d9331ecb61f6/width=450/714468.jpeg)
参数: 
--Size: 1536x1536
--seed: 2572096649
--Model: hyperhavenorange_hyperorangehaven
--steps: 25
--hashes: {"model":"5b6ef45a36"}
--prompt: 1girl, 3x3frames, a series of pictures of a POV blowjob, large penis, \<lora:DDpovbj_1ot:0.5\>
masterpiece, best quality, high quality, perfect skin, intricate details, simple simple background, petite, long ginger hair,
--sampler: DPM++ 2M Karras
--cfgScale: 7
--Clip skip: 2
--Mask blur: 4
--resources: {"name":"DDpovbj_1ot","type":"lora","weight":0.5}
--resources: {"hash":"5b6ef45a36","name":"hyperhavenorange_hyperorangehaven","type":"model"}
--Model hash: 5b6ef45a36
--negativePrompt: 3d, sepia, painting, cartoons, sketch, (worst quality:2), (low quality:2), (normal quality:2), lowres, bad anatomy, bad hands, normal quality, (monochrome), ((grayscale)), (ugly:2.0), badhandv4, BBN, easynegative, poor quality
--Denoising strength: 0.5

================\< 3 \>================
预览图: 
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/791677bb-018e-4c1b-b830-040f0fdb55bf/width=450/714469.jpeg)
参数: 
--Size: 1536x1536
--seed: 2828167524
--Model: perfectdeliberate_v20
--steps: 25
--hashes: {"model":"6ac5833494"}
--prompt: 1girl, 3x3frames, a series of pictures of a POV blowjob, large penis, \<lora:DDpovbj_1ot:0.75\>
masterpiece, best quality, high quality, perfect skin, intricate details, simple simple background, petite, long ginger hair,
--sampler: DPM++ 2M Karras
--cfgScale: 7
--Clip skip: 2
--Mask blur: 4
--resources: {"name":"DDpovbj_1ot","type":"lora","weight":0.75}
--resources: {"hash":"6ac5833494","name":"perfectdeliberate_v20","type":"model"}
--Model hash: 6ac5833494
--negativePrompt: 3d, sepia, painting, cartoons, sketch, (worst quality:2), (low quality:2), (normal quality:2), lowres, bad anatomy, bad hands, normal quality, (monochrome), ((grayscale)), (ugly:2.0), badhandv4, BBN, easynegative, poor quality
--Denoising strength: 0.6
--Ultimate SD upscale padding: 32
--Ultimate SD upscale upscaler: 4x-UltraSharp
--Ultimate SD upscale mask_blur: 8
--Ultimate SD upscale tile_width: 512
--Ultimate SD upscale tile_height: 512

================\< 4 \>================
预览图: 
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9fbc3de6-ca46-4049-b4ef-105afde257f8/width=450/714514.jpeg)
参数: 
--Size: 1536x1536
--seed: 439268959
--Model: anything-v4.5
--steps: 25
--hashes: {"model":"1d1e459f9f"}
--prompt: 1girl, 3x3frames, a series of pictures of a POV blowjob, large penis, \<lora:DDpovbj_1ot:0.3\>
masterpiece, best quality, high quality, perfect skin, intricate details, simple simple background, petite, long ginger hair,
--sampler: DPM++ 2M Karras
--cfgScale: 7
--Clip skip: 2
--Mask blur: 4
--resources: {"name":"DDpovbj_1ot","type":"lora","weight":0.3}
--resources: {"hash":"1d1e459f9f","name":"anything-v4.5","type":"model"}
--Model hash: 1d1e459f9f
--negativePrompt: 3d, sepia, painting, cartoons, sketch, (worst quality:2), (low quality:2), (normal quality:2), lowres, bad anatomy, bad hands, normal quality, (monochrome), ((grayscale)), (ugly:2.0), badhandv4, BBN, easynegative, poor quality
--Denoising strength: 0.5

================\< 5 \>================
预览图: 
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d1ae9c5c-7451-4116-be30-9a69ec17fda3/width=450/714559.jpeg)
参数: 
--Size: 1536x1536
--seed: 1313651880
--Model: chilloutmix_NiPrunedFp32Fix
--steps: 25
--hashes: {"model":"fc2511737a"}
--prompt: 1girl, 3x3frames, a series of pictures of a POV blowjob, large penis, \<lora:DDpovbj_1ot:0.5\>
masterpiece, best quality, high quality, perfect skin, intricate details, simple simple background, petite, long ginger hair,
--sampler: DPM++ 2M Karras
--cfgScale: 7
--Clip skip: 2
--Mask blur: 4
--resources: {"name":"DDpovbj_1ot","type":"lora","weight":0.5}
--resources: {"hash":"fc2511737a","name":"chilloutmix_NiPrunedFp32Fix","type":"model"}
--Model hash: fc2511737a
--negativePrompt: 3d, sepia, painting, cartoons, sketch, (worst quality:2), (low quality:2), (normal quality:2), lowres, bad anatomy, bad hands, normal quality, (monochrome), ((grayscale)), (ugly:2.0), badhandv4, BBN, easynegative, poor quality
--Denoising strength: 0.4

================\< 6 \>================
预览图: 
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b79393ea-1f3b-4eb9-a0f2-059e95906af4/width=450/714564.jpeg)
参数: 
--Size: 768x768
--seed: 2423156362
--Model: hyperhavenorange_hyperorangehaven
--steps: 25
--hashes: {"model":"5b6ef45a36"}
--prompt: 1girl, 3x3frames, a series of pictures of a POV blowjob, large penis, \<lora:DDpovbj_1ot:0.5\>
masterpiece, best quality, high quality, perfect skin, intricate details, simple simple background, petite, long ginger hair,
--sampler: DPM++ 2M Karras
--cfgScale: 7
--Clip skip: 2
--resources: {"name":"DDpovbj_1ot","type":"lora","weight":0.5}
--resources: {"hash":"5b6ef45a36","name":"hyperhavenorange_hyperorangehaven","type":"model"}
--Model hash: 5b6ef45a36
--negativePrompt: 3d, sepia, painting, cartoons, sketch, (worst quality:2), (low quality:2), (normal quality:2), lowres, bad anatomy, bad hands, normal quality, (monochrome), ((grayscale)), (ugly:2.0), badhandv4, BBN, easynegative, poor quality

================\< 7 \>================
预览图: 
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4c2e37a8-aec2-477d-8d25-81d3ef67acda/width=450/714562.jpeg)
参数: 
--Size: 768x768
--seed: 2423156366
--Model: hyperhavenorange_hyperorangehaven
--steps: 25
--hashes: {"model":"5b6ef45a36"}
--prompt: 1girl, 3x3frames, a series of pictures of a POV blowjob, large penis, \<lora:DDpovbj_1ot:0.5\>
masterpiece, best quality, high quality, perfect skin, intricate details, simple simple background, petite, long ginger hair,
--sampler: DPM++ 2M Karras
--cfgScale: 7
--Clip skip: 2
--resources: {"name":"DDpovbj_1ot","type":"lora","weight":0.5}
--resources: {"hash":"5b6ef45a36","name":"hyperhavenorange_hyperorangehaven","type":"model"}
--Model hash: 5b6ef45a36
--negativePrompt: 3d, sepia, painting, cartoons, sketch, (worst quality:2), (low quality:2), (normal quality:2), lowres, bad anatomy, bad hands, normal quality, (monochrome), ((grayscale)), (ugly:2.0), badhandv4, BBN, easynegative, poor quality

================\< 8 \>================
预览图: 
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cc7ba1c7-7ef5-4b4c-bff4-fc86e108d005/width=450/714563.jpeg)
参数: 
--Size: 768x768
--seed: 2423156369
--Model: hyperhavenorange_hyperorangehaven
--steps: 25
--hashes: {"model":"5b6ef45a36"}
--prompt: 1girl, 3x3frames, a series of pictures of a POV blowjob, large penis, \<lora:DDpovbj_1ot:0.5\>
masterpiece, best quality, high quality, perfect skin, intricate details, simple simple background, petite, long ginger hair,
--sampler: DPM++ 2M Karras
--cfgScale: 7
--Clip skip: 2
--resources: {"name":"DDpovbj_1ot","type":"lora","weight":0.5}
--resources: {"hash":"5b6ef45a36","name":"hyperhavenorange_hyperorangehaven","type":"model"}
--Model hash: 5b6ef45a36
--negativePrompt: 3d, sepia, painting, cartoons, sketch, (worst quality:2), (low quality:2), (normal quality:2), lowres, bad anatomy, bad hands, normal quality, (monochrome), ((grayscale)), (ugly:2.0), badhandv4, BBN, easynegative, poor quality

================\< 9 \>================
预览图: 
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dd3b45ad-0338-4e48-be44-a7c7f447c57e/width=450/714561.jpeg)
参数: 
--Size: 768x768
--seed: 3013100252
--Model: anything-v4.5
--steps: 25
--hashes: {"model":"1d1e459f9f"}
--prompt: 1girl, 3x3frames, a series of pictures of a POV blowjob, large penis, \<lora:DDpovbj_1ot:0.5\>
masterpiece, best quality, high quality, perfect skin, intricate details, simple simple background, petite, long ginger hair,
--sampler: DPM++ 2M Karras
--cfgScale: 7
--Clip skip: 2
--resources: {"name":"DDpovbj_1ot","type":"lora","weight":0.5}
--resources: {"hash":"1d1e459f9f","name":"anything-v4.5","type":"model"}
--Model hash: 1d1e459f9f
--negativePrompt: 3d, sepia, painting, cartoons, sketch, (worst quality:2), (low quality:2), (normal quality:2), lowres, bad anatomy, bad hands, normal quality, (monochrome), ((grayscale)), (ugly:2.0), badhandv4, BBN, easynegative, poor quality

================\< 10 \>================
预览图: 
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7c98cd38-c076-4bf9-bfae-5917924d1a91/width=450/714560.jpeg)
参数: 
--Size: 768x768
--seed: 3013100254
--Model: anything-v4.5
--steps: 25
--hashes: {"model":"1d1e459f9f"}
--prompt: 1girl, 3x3frames, a series of pictures of a POV blowjob, large penis, \<lora:DDpovbj_1ot:0.5\>
masterpiece, best quality, high quality, perfect skin, intricate details, simple simple background, petite, long ginger hair,
--sampler: DPM++ 2M Karras
--cfgScale: 7
--Clip skip: 2
--resources: {"name":"DDpovbj_1ot","type":"lora","weight":0.5}
--resources: {"hash":"1d1e459f9f","name":"anything-v4.5","type":"model"}
--Model hash: 1d1e459f9f
--negativePrompt: 3d, sepia, painting, cartoons, sketch, (worst quality:2), (low quality:2), (normal quality:2), lowres, bad anatomy, bad hands, normal quality, (monochrome), ((grayscale)), (ugly:2.0), badhandv4, BBN, easynegative, poor quality
