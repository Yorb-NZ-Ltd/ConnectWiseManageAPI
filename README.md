

This has been forked from https://github.com/christaylorcodes/ConnectWiseManageAPI/tree/master/ConnectWiseManageAPI as a temporary workaround related to Powershell 7.4+ and ConnectWise proxy redirect issues 


﻿<h1 align="center">
  <br>
  <img src=".\Media\Manage-RGB-Horiz-Master.png" alt="logo"></a>
  <br>
  ConnectWise Manage REST API
  <br>
</h1>

<h4 align="center">

This is a PowerShell wrapper for the [ConnectWise Manage REST API](https://developer.connectwise.com/Products/Manage/REST)

</h4>


## [Install](https://www.powershellgallery.com/packages/ConnectWiseManageAPI)

This Module must be manually installed as it is not currently available in the Powershell Gallery.

To copy to your local PowerShell modules storage on Windows OS
```
Copy-Item 'C:\**\ConnectWiseManageAPI\ConnectWiseManageAPI' -Destination "$env:ProgramFiles\WindowsPowerShell\Modules" -Recurse
```

If you are using a different hosted service like an Azure function app you need to add this as a custom module

<ul>
  <li>https://jeffbrown.tech/azure-functions-powershell-module/</li>
  <li>https://techcommunity.microsoft.com/blog/appsonazureblog/steps-to-manually-add-powershell-modules-in-function-app/4163463</li>
</ul>

## [Usage]((https://github.com/christaylorcodes/ConnectWiseManageAPI/wiki/Getting-Started---Authentication))

> **As of 8/14/2019 ConnectWise requires the use of a [Client ID](https://developer.connectwise.com/ClientID) to interact with the API.**

The [Wiki](https://github.com/christaylorcodes/ConnectWiseManageAPI/wiki) has some great information on [how to get started](https://github.com/christaylorcodes/ConnectWiseManageAPI/wiki/Getting-Started---Authentication) with the module.


