# Export NCloud server to Azure VM
Microsoft Azure는 온프레미스 또는 타 클라우드에서 생성된 VHD(Virtual Hard Disk)를 import 한 후,  Azure 가상머신 이미지와 가상머신을 생성할 수 있습니다. 이 리포지토리에서 다루는 내용은 다음과 같습니다.

- VHD export 기능을 제공하지 않는 온프레미스 또는 클라우드 환경에서 VHD를 export 하는 방법
- VHD를 Azure에 import하여 Azure 가상머신 이미지와 가상머신을 생성하는 방법

Hands-on-lab에서는 VHD를 export할 소스 환경으로 NCloud(Naver Business Platform)을 이용하며, NCloud의 server(Ubuntu 16.04 gen1)를 VHD로 export하여, Azure 상에서 가상머신 이미지를 만들고 Azure 가상머신을 배포하는 방법을 설명합니다.

## Azure services and related products
- Azure Blob (Page)
- Azure Images
- Azure Virtual machine

## Related products (Non-Azure)
- Windows 10 or server (installed Hyper-V)
- Veeam Agent for Linux Backup

## Hands-on lab
1. [Hands-on-lab 환경 준비하기](https://github.com/insobi/export-ncloud-server-to-azure-vm/blob/master/Hands-on-lab/0.HOL_Preparation.md)
2. [Hands-on-lab: VHD Export](https://github.com/insobi/export-ncloud-server-to-azure-vm/blob/master/Hands-on-lab/1.HOL_Exporting_VHD.md)
3. [Hands-on-lab: Create Image & VM](https://github.com/insobi/export-ncloud-server-to-azure-vm/blob/master/Hands-on-lab/2.HOL_Creating_Image_VM.md)

## Related references
- [Veeam Agent for Linux](https://helpcenter.veeam.com/docs/agentforlinux/userguide/quickstart.html)
- [Prepare an Ubuntu virtual machine for Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/create-upload-ubuntu)
- [Prepare a Windows VHD or VHDX to upload to Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/prepare-for-upload-vhd-image)
