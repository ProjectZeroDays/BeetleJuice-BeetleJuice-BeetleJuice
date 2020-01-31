<p align="center">
  <a href=""><img src="" alt="License MIT"></a>
    <a href="https://996.icu"><img src="https://img.shields.io/badge/link-996.icu-red.svg" alt="License"></a>
</p>

> #### Call Device Information Using JS 

 - deviceType: Type of Device
 - OS: Operating System
 - OSVersion: Operating System Version
 - screenHeight: Screen Height
 - screenWidth: Screen Width
 - language: Device Language - Country 
 - netWork: Networking Information 
 - orientation: Cross-Screen or Screen Rotation
 - browserInfo: Browser Information
 - fingerprint: Browser FingerPrint
 - userAgent: Contains appCodeName, appName, appVersion, Language, Platform Information
 - groPosition: Geo Location 
 - date: System Time and Date 
 - UUID: Universal Unique Identifier

 > #### How To Call：
 ```
    document.write(JSON.stringify(DeviceInfo.getDeviceInfo(
         {
             domain: 'Your-Web-Domain-Where-It-Is-Hosted',
             info: ['deviceType', 'OS', 'language']
         }
     )))
 ```

#### Note：A hosted domain is required to pass fingerprint and is not given by default
#### Usage: Display All Device Information Automatically By Default 

    window.location.host; 

