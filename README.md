# Med in Mind Power Apps
This repository contains the unpacked files of the .msapp file

A weblink to the Power Apps app can be found here: https://apps.powerapps.com/play/e/b5314d65-a815-ed39-83c1-2b2e03867af6/a/8a819525-dcf7-493c-9fe0-81b3a947c681?tenantId=316aa4d3-f4ee-48f0-9ce7-cef2e1e2a331&sourcetime=1713286774959

To pack this into a .msapp file, clone the repository, delete use README.md, .gitifnore, and .gitattributes files, then use the Microsoft Power Platform CLI to run the following command:
```
pac canvas pack --msapp "Med in Mind.msapp" --sources FromSourceFolder
```
