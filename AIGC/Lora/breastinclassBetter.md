---
Type: 辅助
Trigger: <lora:breastinclassbetter_v141:0.5>
ntoe: 乳房课堂：更好的身体
src: https://civitai.com/models/9025/breastinclass-better-bodies
name: breastinclassBetter.safetensors
---
# BreastInClass: Better Bodies

## 介绍：
<p><s>Pretty self explanatory.</s></p><p><s>The LORA formerly known as "nudify" but that proved too daunting and now we have this corny title instead</s></p><p></p><h1><u>⬇️ read the instructions ⬇️</u></h1><p></p><h3>What it is</h3><ul><li><p>This is a LORA that I use in<strong> <u>text2img</u></strong> to get better NUDE female body types out of generated images.</p></li><li><p>It's best at low weights with accompanying keywords. </p></li><li><p>It alters the body shape, particularly the breasts.</p></li><li><p>The data set is a collection of adult women with their faces cropped out of the photo.</p></li></ul><p></p><h3>What it is not</h3><ul><li><p>The dataset is all naked women with no faces. Any effect on clothing, men, flat chests, or faces is unintended.</p></li><li><p>It only works when you include it in the prompt (saddened I must tell you this).</p></li><li><p>It does not bias towards asians. Chilloutmix just happens to be very good at them. The models used are all white since v1.0.</p></li></ul><p></p><h2>Installation:</h2><ol><li><p>Download the file</p></li><li><p>Place it in models\Lora folder (webui)</p><p></p></li></ol><h2>Usage:</h2><p>You can also add it to the prompt by clicking the magenta picture icon beneath "generate" in webUI.</p><p></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7f53020f-e28a-4b64-7ff8-924eb28da500/width=525/7f53020f-e28a-4b64-7ff8-924eb28da500" /><p>You can also type it into the prompt, but it will not work if you make a single typo.<br />ex <code>&lt;lora:breastinclassBetter_v141:0.3&gt;</code></p><p></p><p>Adjust the weights. <code>0.1 - 1.0</code></p><p></p><h2>Tips:</h2><ul><li><p>This is a fairly strong LORA best used in conjunction with low weights and other keywords like "naked".</p></li><li><p><code>0.3 - 0.5</code> weight is pretty good for most purposes.</p></li><li><p>Very high weights can cause the face to crop out.</p></li><li><p>Very high weights can cause the image to burn.</p></li><li><p>Adding "small breast" or "huge breast" keywords can add more size variation, keeping the shape.</p></li><li><p>Adding stubborn loras or conflicting terms (e.g. "shirt") to the prompt can burn the image.</p></li></ul><p></p><p>Previews were made using <a target="_blank" rel="ugc" href="https://civitai.com/models/6424/chilloutmix">chilloutmix_ni</a></p><p></p><p></p>

## 版本(v1.41)介绍：
<p>The tool I used to make the lora fixed the issue that would print an error on first run. The data set, steps, configuration is all the same. There should be no/minimal difference in the generated image.</p><p>CL:</p><ul><li><p>No longer produces an "invalid keys" error</p></li></ul>

## 示例：
================\< 1 \>================
预览图: 
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1bee864f-7025-4c64-f7af-3fa429e4e900/width=450/251975.jpeg)
参数: 
--Size: 512x768
--seed: 700490917
--Model: chilloutmix_NiPrunedFp32Fix
--steps: 25
--prompt: 8k, RAW photo, portrait, best quality, ultra high res, photorealistic,
1girl, naked, full body, thigh, white hair, 
earrings, necklace, pool, grin, eyelashes, small breast,
cinematic lighting, night, depth of field, lens flare,
\<lora:koreanDollLikeness_v15:0.3\>, \<lora:taiwanDollLikeness_v10:0.2\>,  \<lora:breastinClass:0.7\>
--sampler: DPM++ SDE Karras
--cfgScale: 7.5
--resources: {"name":"koreanDollLikeness_v15","type":"lora","weight":0.3}
--resources: {"name":"taiwanDollLikeness_v10","type":"lora","weight":0.2}
--resources: {"name":"breastinClass","type":"lora","weight":0.7}
--resources: {"hash":"fc2511737a","name":"chilloutmix_NiPrunedFp32Fix","type":"model"}
--Model hash: fc2511737a
--negativePrompt: paintings, cartoon, rendered, anime, sketches, (worst quality:2), (low quality:2), (normal quality:2), wet, child, chest hair, dot, mole, lowres, normal quality, monochrome, grayscale, lowres, text, error, cropped, jpeg artifacts, ugly, duplicate, morbid, mutilated, out of frame, extra fingers, mutated hands, poorly drawn hands, poorly drawn face, mutation, deformed, blurry, dehydrated, bad anatomy, bad proportions, extra limbs, cloned face, disfigured, gross proportions, malformed limbs, missing arms, missing legs, extra arms, extra legs, fused fingers, too many fingers, long neck, username, watermark, signature,
--Face restoration: CodeFormer
