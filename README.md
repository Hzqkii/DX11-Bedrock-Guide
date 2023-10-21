## Force DX11 (Fix UI not appearing)

Pre-requisites - [Mclauncher](https://github.com/MCMrARM/mc-w10-version-launcher/releases/tag/0.4.0) (or) [Minecraft Bedrock Launcher](https://bedrocklauncher.github.io/)
### How does it work?

We use VKD3D which makes Minecraft: Bedrock Edition fallback to d3d11.
### What is VKD3D?

VKD3D is a translation layer for games running under proton, it essentially converts DX12 calls and translates them to Vulkan eg; DX12 is Russian and Vulkan is English, VKD3D is an interpreter or a translator for them.

### How do we actually do it? - I will only showcase Minecraft Bedrock Launcher here.

* You will need to get the library itself, it is in this repository!
* You will now need it in your execution directory, on Minecraft Bedrock Launcher
