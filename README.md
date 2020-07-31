# Export a server on NCloud to Azure
NCloud(Naver Business Platform)의 server(Ubuntu 16.04 gen1)를 VHD로 export하여, Azure 상에서 가상머신 이미지를 만들고 Azure 가상머신을 배포합니다.

## Azure services and related products
- Azure Blob (Page)
- Azure Images
- Azure Virtual machine

## Related products (Non-Azure)
- Windows 10 or server (installed Hyper-V)
- Veeam Agent for Linux Backup

## Hands-on lab
1. [Preparation](https://github.com/insobi/export-ncloud-server-to-azure-vm/blob/master/Hands-on-lab/0.HOL_Preparation.md)
2. [Step-by-Step](https://github.com/insobi/export-ncloud-server-to-azure-vm/blob/master/Hands-on-lab/1.HOL_step-by-step.md)

## Related references
- [Veeam Agent for Linux](https://www.veeam.com/linux-cloud-server-backup-agent.html)
- [Prepare an Ubuntu virtual machine for Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/create-upload-ubuntu)
- [Prepare a Windows VHD or VHDX to upload to Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/prepare-for-upload-vhd-image)
