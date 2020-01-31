<p align = "center">
  <a href="https://www.skillnull.com"> <img src = "https://skillnull.com/others/images/brand/MIT.svg" alt = "License MIT"> </a>
    <a href="https://996.icu"> <img src = "https://img.shields.io/badge/link-996.icu-red.svg" alt = "License"> </ a >
</ p>

> #### JS get device information

 -deviceType: device type
 -OS: Operating system
 -OSVersion: Operating system version
 -screenHeight: screen height
 -screenWidth: screen width
 -language: the current language-country
 -netWork: network type
 -orientation: horizontal and vertical screen
 -browserInfo: browser info
 -fingerprint: browser fingerprint
 -userAgent: contains appCodeName, appName, appVersion, language, platform, etc.
 -groPosition: geographical location
 -date: system time
 -UUID: Universally Unique Identifier

 > #### How to call:
 `` `
    document.write (JSON.stringify (DeviceInfo.getDeviceInfo (
         {
             domain: 'http://www.skillnull.com',
             info: ['deviceType', 'OS', 'language']
         }
     )))
 `` `
 > Note: The domain is required to generate the fingerprint of the browser. The default is to use window.location.host; info is the information you want to get, and the default is to display all the information.
 
 > #### Online address: [https://skillnull.com/others/GetDeviceInfo/index.html](https://skillnull.com/others/GetDeviceInfo/index.html)
