# Generative-AI-Cookbook
  * [Text 💬](#text)
  * [Image 🏞](#image)
  * [Audio 🎶🎤](#audio)
  * [Video 🎥](#video)
  
# Work In Progress! 🚧 🔨 👷‍♂️

## Text

| |Text 💬| Description |
------|----|---|
1 |OpenAI GPT [\[paper\]](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf)| GPT stands for Generative Pretrained Transformer, model that's been trained on a massive amount of text data. So it has a big brain, it can generate new text or answer questions based on what it's learned. |
2 |ChatGPT [\[blog\]](https://huggingface.co/blog/rlhf) | ChatGPT is a version of the GPT designed for chat applications it understands and respond to natural language messages. Model learns from interaction with users and use that information to improve its future responses (RLHF).|

## Image

|| Image 🏞| Description |
|-------------|--|--|
1| OpenAI Dall-E 2 [\[paper\]](https://cdn.openai.com/papers/dall-e-2.pdf) [\[blog\]](https://openai.com/dall-e-2/)| DALL·E 2 can create unique and lifelike images and artworks based on text descriptions. It can also edit existing images in a realistic manner and create variations of an image. It's able to do this by understanding the relationship between images and text, and using a process called "diffusion."|
2| Stable Diffusion [\[paper\]](https://arxiv.org/pdf/2112.10752.pdf) [\[blog\]](https://jalammar.github.io/illustrated-stable-diffusion/)| Stable Diffusion uses a series of transformations to go from random noise to a final image. It uses a stability loss function to avoid mode collapse and keep the generated images unique.|

## Audio

|| Audio 🎶🎤| Description |
|--------------|----------------|--|
1| OpenAI JukeBox [\[paper\]](https://arxiv.org/pdf/2005.00341.pdf) [\[demo blog\]](https://openai.com/blog/jukebox/)| Jukebox, a neural net that generates music. The model uses a combination of a multi-scale VQ-VAE (Vector Quantized - Variational Autoencoder!) and autoregressive Transformers to compress the audio and generate songs with coherence and high-fidelity up to multiple minutes.|
2| VALL-E [\[demo blog\]](https://valle-demo.github.io/)| VALL-E, a model that can understand how people talk. A system that talks like a real person, with only a 3-second recording it can create person's voice like them, even it mimics the speaker's emotions! |
3| MusicLM: Generating Music From Text [\[blog\]](https://google-research.github.io/seanet/musiclm/examples/) [\[paper\]](https://arxiv.org/pdf/2301.11325.pdf) | MusicLM, a model that can generate some pretty awesome music based on text descriptions. It's a sequence-to-sequence model that generates high-quality music and can even keep it consistent over long periods of time. Plus, it can even take in a whistled or hummed melody and change it to match the style described in the text.|
4| | SingSong, a model that generates instrumental music to accompany your voice. Audio to Audio mapping, Input: Vocals, Output: Instrumental audio/music. Think of it like a Rerverse Karaoke!  |


## Video

|| Video 🎥| Description |
|---|------|---|
1| Microsoft X-Clip [\[🤗 model\]](https://huggingface.co/microsoft/xclip-base-patch16-zero-shot) [\[paper\]](https://arxiv.org/pdf/2208.02816.pdf)| X-CLIP is a model used to generate video from text. It adapts pretrained language-image model (CLIP) to video recognition, instead of starting from scratch. X-CLIP uses a cross-frame attention mechanism to capture the long-range dependencies of frames in a video, and a video-specific prompting scheme to generate discriminative textual prompts.  |
2| Meta Make a Video [\[paper\]](https://arxiv.org/pdf/2209.14792.pdf) [\[demo blog\]](https://makeavideo.studio/) | Make-A-Video is a text-to-video generation system and it uses images with descriptions to learn what the world looks like and how it is often described. It also uses unlabeled videos to learn how the world moves. These ingredients are enough to cook one of a kind videos! |
