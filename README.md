# Export a server on NCloud to Azure
Microsoft Azure는 온프레미스 또는 타 클라우드에서 생성된 VHD(Virtual Hard Disk)를 import 한 후,  Azure 가상머신 이미지와 가상머신을 생성할 수 있습니다. 본 컨텐츠는 VHD의 export 기능을 제공하지 않는 온프레미스 또는 클라우드 환경에서 VHD를 export 하는 방법과 export한 VHD를 Azure에 import하여 Azure 가상머신 이미지와 가상머신을 생성하는 방법을 제공합니다. 본 Hands-on-lab에서는 VHD를 export할 소스 환경으로 NCloud(Naver Business Platform)을 이용하며, NCloud의 server(Ubuntu 16.04 gen1)를 VHD로 export하여, Azure 상에서 가상머신 이미지를 만들고 Azure 가상머신을 배포하는 방법을 설명합니다.

## Azure services and related products
- Azure Blob (Page)
- Azure Images
- Azure Virtual machine

## Related products (Non-Azure)
- Windows 10 or server (installed Hyper-V)
- Veeam Agent for Linux Backup

## Hands-on lab
1. [Hands-on-lab 환경 준비](https://github.com/insobi/export-ncloud-server-to-azure-vm/blob/master/Hands-on-lab/0.HOL_Preparation.md)
2. [Hands-on-lab](https://github.com/insobi/export-ncloud-server-to-azure-vm/blob/master/Hands-on-lab/1.HOL_step-by-step.md)

## Related references
- [Veeam Agent for Linux](https://www.veeam.com/linux-cloud-server-backup-agent.html)
- [Prepare an Ubuntu virtual machine for Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/create-upload-ubuntu)
- [Prepare a Windows VHD or VHDX to upload to Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/prepare-for-upload-vhd-image)
