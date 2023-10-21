## Force DX11 (Fix UI not appearing)

Pre-requisites - [Mclauncher](https://github.com/MCMrARM/mc-w10-version-launcher/releases/tag/0.4.0) (or) [Minecraft Bedrock Launcher](https://bedrocklauncher.github.io/)
### How does it work?

We use VKD3D which makes Minecraft: Bedrock Edition fallback to d3d11.
### What is VKD3D?

VKD3D is a translation layer for games running under proton, it essentially converts DX12 calls and translates them to Vulkan eg; DX12 is Russian and Vulkan is English, VKD3D is an interpreter or a translator for them.

### How do we actually do it? - I will only showcase Minecraft Bedrock Launcher here.

* You will need to get the library itself, it is in this repository!
* You will now need it in your execution directory, on Minecraft Bedrock Launcher

![image](https://github.com/Hzqkii/DX11-Bedrock-Guide/assets/128440086/a2e32e2e-8df1-46cd-9644-f7319e972e60)

![image](https://github.com/Hzqkii/DX11-Bedrock-Guide/assets/128440086/3f0236a1-d816-48e9-90f8-0664276185a1)

![image](https://github.com/Hzqkii/DX11-Bedrock-Guide/assets/128440086/6d19e32a-ad76-4bad-ae9e-f769c711105b)

![image](https://github.com/Hzqkii/DX11-Bedrock-Guide/assets/128440086/cd556851-76ce-4965-9a67-4899cf1c9cc0)
