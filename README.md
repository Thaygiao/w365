# Packer templates

Hasicorp [Packer](https://www.packer.io/) templates for building Windows Server and Windows 10 images for Windows Virtual Desktop, Citrix Cloud etc. in Azure. Images are built via Azure DevOps and stored in a [Shared Image Library](https://docs.microsoft.com/en-us/azure/virtual-machines/shared-image-galleries).

Leverages [Evergreen](https://stealthpuppy.com/evergreen) to create images with the latest application versions so that each image is always up to date.

Outputs reports in markdown format for basic tracking of image updates: [https://stealthpuppy.com/packer](https://stealthpuppy.com/packer).

| Operating System | Status |
|:--|:--|
| Windows 10 Enterprise | [![Build Status](https://dev.azure.com/stealthpuppyLab/Packer/_apis/build/status/windows10-enterprise-wvd?branchName=main)](https://dev.azure.com/stealthpuppyLab/Packer/_build/latest?definitionId=2&branchName=main) |
| Windows 10 multi-session | [![Build Status](https://dev.azure.com/stealthpuppyLab/Packer/_apis/build/status/windows10-multisession-wvd?branchName=main)](https://dev.azure.com/stealthpuppyLab/Packer/_build/latest?definitionId=2&branchName=main) |
| Windows 11 Enterprise | [![Build Status](https://dev.azure.com/stealthpuppyLab/Packer/_apis/build/status/windows11-enterprise-wvd?branchName=main)](https://dev.azure.com/stealthpuppyLab/Packer/_build/latest?definitionId=2&branchName=main) |
| Windows 11 multi-session | [![Build Status](https://dev.azure.com/stealthpuppyLab/Packer/_apis/build/status/windows11-multisession-wvd?branchName=main)](https://dev.azure.com/stealthpuppyLab/Packer/_build/latest?definitionId=2&branchName=main) |
| Windows Server 2022 | [![Build Status](https://dev.azure.com/stealthpuppyLab/Packer/_apis/build/status/windowsserver2022-wvd?branchName=main)](https://dev.azure.com/stealthpuppyLab/Packer/_build/latest?definitionId=2&branchName=main) |
