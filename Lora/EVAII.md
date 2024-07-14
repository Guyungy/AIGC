## 标题：
EVA『新世紀エヴァンゲリオン』新世纪福音战士 Neon Genesis EVANGELION LoRA

## 链接：
https://civitai.com/models/51484/eva-neon-genesis-evangelion-lora

## 触发词：
EVAGOD,EVA 00,EVA 01,EVA 02,EVA 08,

## 介绍：
<p>这是一个可以生成类EVA风格泛用人型决战兵器的LoRA。</p><p>EVA 00、EVA 01、EVA 02、EVA 08这几个tag分别关联的是零号机、初号机、二号机以及八号机。初号机和二号机因为训练图更多，所以效果更好。其次是零号机，八号机的生成效果一般。</p><p>另外我给所有训练集图片都打上了EVAGOD这个tag，因此调用这个tag时，可以生成融合风格的人形兵器。</p><p>请注意，因为模型中训练照片来源多样，因此并不能准确复现原作中机体的细节，但在风格上具有显著的EVA风。</p><p>本Lora我是使用NAI为底模训练的。使用Lyriel模型的3D测试效果不错，其他模型我还没试过，应该会有更多适用的大模型。欢迎大家多多晒图分享在其他大模型上生成的画风效果！</p>

## 版本(V2.0)介绍：
<p>这个版本对训练集进行了扩充，并更仔细地调整了训练图的打标</p>

## 示例：
================\< 1 \>================
预览图: 
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8afced28-2554-4bfe-56c8-cd06f5322b00/width=450/613082.jpeg)
参数: 
--ENSD: 31337
--Size: 512x704
--seed: 2406236387
--Model: 2D_meinamix_meinaV9
--steps: 27
--hashes: {"model":"eac6c08a19"}
--prompt: ((eva 02), evagod:1.1), evagenlion, Concept Design, sci-fic character design, SCIENCE FICTION, giant robot, advanced metal and Ceramic Mecha, Accurate EVA 02 head details, high-tech, huge android, (outdoors, sky, clouds), global illumination, rim light, octane rendering, ray tracing, 4k, Best quality, masterpiece, high res, highly detailed, scientific anatomy, carbon fiber, titanium alloy, hyperrealistic, anatomical, beautiful Tokyo-3 background, CG, unity, wallpaper, Futurism, epic sense, doomsday, sci-fi fighter, giant machinery, correct perspective
--sampler: DPM++ SDE Karras
--cfgScale: 7
--Clip skip: 2
--resources: {"hash":"eac6c08a19","name":"2D_meinamix_meinaV9","type":"model"}
--resources: {"hash":"717a371cbad1","name":"000037","type":"lora","weight":null}
--Model hash: eac6c08a19
--Hires steps: 24
--Hires upscale: 2
--AddNet Enabled: True
--AddNet Model 1: EVAII-000037(717a371cbad1)
--Hires upscaler: Latent (bicubic antialiased)
--negativePrompt: darkness, (worst quality, low quality:1.2), sketches, lowres, poorly drawn, bad head, fake hands, wrong hands, bad anatomy, wrong anatomy, extra limb, missing limb, floating limbs, (mutated hands and fingers:1.4), disconnected limbs, mutation, mutated, disgusting, amputation, wrong perspective, bad_prompt_version2
--AddNet Module 1: LoRA
--AddNet Weight A 1: 0.6
--AddNet Weight B 1: 0.6
--Denoising strength: 0.56

================\< 2 \>================
预览图: 
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cd90590d-3310-43b3-d74c-cebaf5c25700/width=450/613096.jpeg)
参数: 
--ENSD: 31337
--Size: 512x704
--seed: 706713772
--Model: 3D_cardosAnimated_v20
--steps: 27
--hashes: {"model":"4fafa71c2a"}
--prompt: ((eva 00), evagod:1.1), evagenlion, Concept Design, sci-fic character design, SCIENCE FICTION, advanced giant robot, metal and Ceramic Mecha, Accurate head details, high-tech, huge android, (outdoors, red sky, orange clouds, Sunlight), global illumination, rim light, octane rendering, ray tracing, 4k, Best quality, masterpiece, high res, highly detailed, scientific anatomy, carbon fiber, titanium alloy, hyperrealistic, anatomical, beautiful Tokyo-3 background, CG, unity, wallpaper, Futurism, epic sense, doomsday, sci-fi fighter, giant machinery, correct perspective
--sampler: DPM++ SDE Karras
--cfgScale: 7
--resources: {"hash":"4fafa71c2a","name":"3D_cardosAnimated_v20","type":"model"}
--resources: {"hash":"717a371cbad1","name":"000037","type":"lora","weight":null}
--Model hash: 4fafa71c2a
--Hires steps: 24
--Hires upscale: 2
--AddNet Enabled: True
--AddNet Model 1: EVAII-000037(717a371cbad1)
--Hires upscaler: Latent (bicubic antialiased)
--negativePrompt: darkness, (worst quality, low quality:1.2), sketches, lowres, poorly drawn, bad head, fake hands, wrong hands, bad anatomy, wrong anatomy, extra limb, missing limb, floating limbs, (mutated hands and fingers:1.4), disconnected limbs, mutation, mutated, disgusting, amputation, wrong perspective, bad_prompt_version2
--AddNet Module 1: LoRA
--AddNet Weight A 1: 0.6
--AddNet Weight B 1: 0.6
--Denoising strength: 0.56

================\< 3 \>================
预览图: 
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/95f1104e-a1f3-4742-50e3-10e648373300/width=450/613107.jpeg)
参数: 
--ENSD: 31337
--Size: 512x704
--seed: 2569955794
--Model: 3D_cardosAnimated_v20
--steps: 27
--hashes: {"model":"4fafa71c2a"}
--prompt: ((eva 01), evagod:1.1), evagenlion, Concept Design, sci-fic character design, SCIENCE FICTION, giant robot, advanced metal and Ceramic Mecha, Accurate EVA 01 head details, high-tech, huge android, (outdoors, sky, clouds), global illumination, rim light, octane rendering, ray tracing, 4k, Best quality, masterpiece, high res, highly detailed, scientific anatomy, carbon fiber, titanium alloy, hyperrealistic, anatomical, beautiful Tokyo-3 background, CG, unity, wallpaper, Futurism, epic sense, doomsday, sci-fi fighter, giant machinery, correct perspective
--sampler: DPM++ SDE Karras
--cfgScale: 7
--resources: {"hash":"4fafa71c2a","name":"3D_cardosAnimated_v20","type":"model"}
--resources: {"hash":"717a371cbad1","name":"000037","type":"lora","weight":null}
--Model hash: 4fafa71c2a
--Hires steps: 24
--Hires upscale: 2
--AddNet Enabled: True
--AddNet Model 1: EVAII-000037(717a371cbad1)
--Hires upscaler: Latent (bicubic antialiased)
--negativePrompt: darkness, (worst quality, low quality:1.2), sketches, lowres, poorly drawn, bad head, fake hands, wrong hands, bad anatomy, wrong anatomy, extra limb, missing limb, floating limbs, (mutated hands and fingers:1.4), disconnected limbs, mutation, mutated, disgusting, amputation, wrong perspective, bad_prompt_version2
--AddNet Module 1: LoRA
--AddNet Weight A 1: 0.6
--AddNet Weight B 1: 0.6
--Denoising strength: 0.56

================\< 4 \>================
预览图: 
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3756a398-9c6a-4f32-83cd-db1fb9f70200/width=450/613089.jpeg)
参数: 
--ENSD: 31337
--Size: 512x704
--seed: 3127104872
--Model: 2D_meinamix_meinaV9
--steps: 27
--hashes: {"model":"eac6c08a19"}
--prompt: ((eva 08), evagod:1.1), evagenlion, Concept Design, sci-fic character design, SCIENCE FICTION, giant robot, advanced metal and Ceramic Mecha, Accurate EVA 08 head details, high-tech, huge android, (outdoors, sky, clouds), global illumination, rim light, octane rendering, ray tracing, 4k, Best quality, masterpiece, high res, highly detailed, scientific anatomy, carbon fiber, titanium alloy, hyperrealistic, anatomical, beautiful Tokyo-3 background, CG, unity, wallpaper, Futurism, epic sense, doomsday, sci-fi fighter, giant machinery, correct perspective
--sampler: DPM++ SDE Karras
--cfgScale: 7
--Clip skip: 2
--resources: {"hash":"eac6c08a19","name":"2D_meinamix_meinaV9","type":"model"}
--resources: {"hash":"717a371cbad1","name":"000037","type":"lora","weight":null}
--Model hash: eac6c08a19
--Hires steps: 24
--Hires upscale: 2
--AddNet Enabled: True
--AddNet Model 1: EVAII-000037(717a371cbad1)
--Hires upscaler: Latent (bicubic antialiased)
--negativePrompt: darkness, (worst quality, low quality:1.2), sketches, lowres, poorly drawn, bad head, fake hands, wrong hands, bad anatomy, wrong anatomy, extra limb, missing limb, floating limbs, (mutated hands and fingers:1.4), disconnected limbs, mutation, mutated, disgusting, amputation, wrong perspective, bad_prompt_version2
--AddNet Module 1: LoRA
--AddNet Weight A 1: 0.6
--AddNet Weight B 1: 0.6
--Denoising strength: 0.56
