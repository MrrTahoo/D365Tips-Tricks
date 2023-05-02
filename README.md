# D365Tips-Tricks
This repository would contain all the tips and tricks for developers that will help them when working with Microsoft Dynamics 365 customization development.


# D365 URLs
The URLs below can be used to run classes and open tables directly inside the browser:

1. Classes: https://YourEnvironmentLink/?cmp=YourCompanyName&mi=SysClassRunner&cls=YourClassName
2. Tables:  https://YourEnvironmentLink/?cmp=YourCompanyName&mi=SysTableBrowser&tablename=YourClassName

# ModelUtil.exe application (Model management using CMD)

This tool is located in the packages bin folder (C:\packages\bin or I:\AosService\PackagesLocalDirectory\bin).

## Install a model in a development environment
To install a model file in a development environment, use the ModelUtil.exe tool and the -import directive.

ModelUtil.exe -import -metadatastorepath=[path of the metadata store where model should be imported] -file=[full path of the file to import]
