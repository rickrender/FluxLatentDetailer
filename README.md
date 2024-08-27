# Flux Latent Detailer

![Generated Image 1](https://github.com/rickrender/FluxLatentDetailer/blob/main/FluxLatentDetailer.png)

## Description

This was an experiment that just seems to work, I really don't know how or why. It seems that interpolation of latents with Flux yields more fine details in images. To vary an image more substantially you can try adding a node to set another seed for the 2nd pass, this allows you to change the image details while retaining quality and most of the composition. I haven't explored other types of styles with this workflow besides photos.

**I CANNOT PROVIDE SUPPORT FOR THIS, I'M JUST SHARING!**

## Resources

This workflow uses `araminta_k_flux_koda.safetensors` which can be found at CivitAI.
[https://civitai.com/models/653093/Koda%20Diffusion%20(Flux)](https://civitai.com/models/653093/Koda%20Diffusion%20(Flux)) -- Amazing lora!

The Kodachrome LUT file can be downloaded from here:
[https://www.freepresets.com/product/free-lut-kodachrome-lookup-table/](https://www.freepresets.com/product/free-lut-kodachrome-lookup-table/)

LUT goes into ComfyUI\custom_nodes\ComfyUI_essentials\luts, if you are using cubiq's comfy_essential nodes like in this workflow.

## Setup

The Flux.1 checkpoint used in this workflow is the dev version. If you're missing any custom nodes or get errors/red nodes:

1. Click manager
2. Click on "Install Missing Custom Nodes"
3. When the installation finishes, click "Restart" as instructed
4. Reload the workflow

## Performance

I'm using an RTX 4090 with 24GB of RAM. Each image takes approximately 98 seconds.

## License

If you modify and share this workflow, all I ask is that you credit me.
https://renderartist.com
https://www.instagram.com/renderartist/
https://www.x.com/renderartist/
