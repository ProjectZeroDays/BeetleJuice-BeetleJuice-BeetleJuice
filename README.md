<p align="center">
  <a href=""><img src="" alt="License MIT"></a><br>
    <a href="https://996.icu"><img src="https://img.shields.io/badge/link-996.icu-red.svg" alt="License"></a>
</p>

#### Call Device Information Using JS 

#### Type of Device:<br>
    - deviceType

#### Operating System:<br>
    - OS

#### Operating System Version:<br>
    - OSVersion

#### Screen Height:<br>
    - screenHeight 

#### Screen Width:<br>
    - screenWidth

#### Device Language - Country:<br>
    - language

#### Networking Information:<br>
    - netWork

#### Screen Orientation:<br>
    - orientation

#### Browser Information:<br>
    - browserInfo
 
#### Browser FingerPrint:<br>
    - fingerprint 

#### Contains: (appCodeName, appName, appVersion, Language, & Platform Information)<br>
    - userAgent

#### Geo Location:<br>
    - groPosition

#### System Time and Date:<br>
    - date

#### Universal Unique Identifier:<br>
    - UUID 

#### How To Call:<br>

 ```
    document.write(JSON.stringify(DeviceInfo.getDeviceInfo(
         {
             domain: 'Your-Web-Domain-Where-It-Is-Hosted',
             info: ['deviceType', 'OS', 'language']
         }
     )))
 ```

#### Usage: Display All Device Information Automatically By Default

    window.location.host; 

#### Note: (A hosted domain is required to pass fingerprint and is not given by default)

 
