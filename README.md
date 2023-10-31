## Force DX11 (Fix UI not appearing)

Pre-requisites - [Mclauncher](https://github.com/MCMrARM/mc-w10-version-launcher/releases/tag/0.4.0) (or) [Minecraft Bedrock Launcher](https://bedrocklauncher.github.io/)
### How does it work?

We use [VKD3D](https://github.com/HansKristian-Work/vkd3d-proton) which tries to translate the DirectX calls but fails forcing Minecraft: Bedrock Edition to fallback to d3d11.
### What is VKD3D?

VKD3D is a translation layer for games running under proton, it essentially converts DX12 calls and translates them to Vulkan eg; DX12 is Russian and Vulkan is English, VKD3D is an interpreter or a translator for them.

### How do we actually do it? - I will only showcase Minecraft Bedrock Launcher here.

* You will need to get the library itself, it is in this repository!
* You will now need it in your execution directory, on Minecraft Bedrock Launcher
* The Library: [d3d12.dll](https://raw.githubusercontent.com/Hzqkii/DX11-Bedrock-Guide/main/d3d12.dll)
![image](https://github.com/Hzqkii/DX11-Bedrock-Guide/assets/128440086/fa39abba-efe9-4f02-9139-904588779460)

![image](https://github.com/Hzqkii/DX11-Bedrock-Guide/assets/128440086/2a9edc6b-107a-4246-a74e-bc16d3a366cf)

![image](https://github.com/Hzqkii/DX11-Bedrock-Guide/assets/128440086/688155dc-24f0-46eb-a234-fa7737c4e85d)

![image](https://github.com/Hzqkii/DX11-Bedrock-Guide/assets/128440086/b479cc82-866b-4a52-9777-c2183c170795)


vkd3d version used in this guide: 2.10
