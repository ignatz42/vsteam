# VSTeam

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/DarqueWarrior/vsteam/blob/master/LICENSE)
[![Documentation - VSTeam](https://img.shields.io/badge/Documentation-VSTeam-blue.svg)](https://github.com/DarqueWarrior/vsteam/blob/master/docs/readme.md)
[![PowerShell Gallery - VSTeam](https://img.shields.io/badge/PowerShell%20Gallery-VSTeam-blue.svg)](https://www.powershellgallery.com/packages/VSTeam)
[![Minimum Supported PowerShell Version](https://img.shields.io/badge/PowerShell-5.0-blue.svg)](https://github.com/PowerShell/PowerShell)

## Introduction

VSTeam is a PowerShell module with commands for accessing your [Azure DevOps Server (previously named Visual Studio Team Foundation Server) 2017/2018](https://cda.ms/Bf) and [Azure DevOps (previously named Visual Studio Team Services)](https://cda.ms/Bf).

VSTeam module is also is a provider allowing users to navigate their [Azure DevOps Server](https://cda.ms/Bf) and [Azure DevOps](https://cda.ms/Bf) as a file system.

To get started you can visit this blog [PowerShell I would like you to meet TFS and VSTS](http://www.donovanbrown.com/post/PowerShell-I-would-like-you-to-meet-TFS-and-VSTS)

## Pipeline Status

You can review the status of every stage of the pipeline below.

|         Stage                       |             Status           |
|-------------------------------------|------------------------------|
| Build                               | [![Build status](https://loecda.visualstudio.com/Team%20Module/_apis/build/status/CI)](https://loecda.visualstudio.com/Team%20Module/_build/latest?definitionId=52)|
| Linux Team Foundation Server 2017   | [![Environment status](https://loecda.vsrm.visualstudio.com/_apis/public/Release/badge/3e857acd-880f-4056-a46b-1de672ca55cc/1/7)](https://loecda.visualstudio.com/Team%20Module/_releases2?definitionId=1&view=mine&_a=releases) |
| macOS Team Foundation Server 2017   | [![Environment status](https://loecda.vsrm.visualstudio.com/_apis/public/Release/badge/3e857acd-880f-4056-a46b-1de672ca55cc/1/6)](https://loecda.visualstudio.com/Team%20Module/_releases2?definitionId=1&view=mine&_a=releases) |
| Windows Team Foundation Server 2017 | [![Environment status](https://loecda.vsrm.visualstudio.com/_apis/public/Release/badge/3e857acd-880f-4056-a46b-1de672ca55cc/1/2)](https://loecda.visualstudio.com/Team%20Module/_releases2?definitionId=1&view=mine&_a=releases) |
| Windows Team Foundation Server 2018 | [![Environment status](https://loecda.vsrm.visualstudio.com/_apis/public/Release/badge/3e857acd-880f-4056-a46b-1de672ca55cc/1/5)](https://loecda.visualstudio.com/Team%20Module/_releases2?definitionId=1&view=mine&_a=releases) |
| Windows Azure DevOps | [![Environment status](https://loecda.vsrm.visualstudio.com/_apis/public/Release/badge/3e857acd-880f-4056-a46b-1de672ca55cc/1/4)](https://loecda.visualstudio.com/Team%20Module/_releases2?definitionId=1&view=mine&_a=releases) |
| Publish to PowerShell Gallery       | [![Environment status](https://loecda.vsrm.visualstudio.com/_apis/public/Release/badge/3e857acd-880f-4056-a46b-1de672ca55cc/1/1)](https://loecda.visualstudio.com/Team%20Module/_releases2?definitionId=1&view=mine&_a=releases) |

The build for VSTeam is run on macOS, Linux and Windows to ensure there are no casing or other platform specific issues with the code.

![Build](.github/images/build.png)

 On each platform unit tests are run.

 ![Unit Tests](.github/images/unittests.png)

During the release the module is installed on macOS, Linux and Window and tested against [Azure DevOps Server](https://cda.ms/Bf) and [Azure DevOps](https://cda.ms/Bf) before being published to the PowerShell Gallery.

## Requirements

- Windows PowerShell 5.0 or newer.
- PowerShell Core.

## Module Dependencies

- [SHiPS module](https://www.powershellgallery.com/packages/SHiPS/)

## Contributors

[Guidelines](.github/CONTRIBUTING.md)

## Change Log

[Change Log](CHANGELOG.md)

## Maintainers

- [Donovan Brown](https://github.com/darquewarrior) - [@DonovanBrown](https://twitter.com/DonovanBrown)

## License

This project is [licensed under the MIT License](LICENSE).
