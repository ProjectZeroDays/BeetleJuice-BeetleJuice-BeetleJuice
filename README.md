<h3> Call Device Info Using JS</h3>
<p align="center">
<br>
<a href="https://996.icu"><img src="https://img.shields.io/badge/link-996.icu-red.svg" alt="License"></a><br>

<a href="https://raw.githubusercontent.com/ProjectZeroDays/Get-Device-Info-Baby/master/LICENSE"><img src="" alt="License MIT">License MIT</a>
<br>
  <a href="https://www.reddit.com/Anonym0us_User">Reddit</a>  •  <a href="https://twitter.com/ProjectZeroDays">Twitter</a>
<br>
<br>
<p> This is a small simple javascript module that access device info such as OS, OS Version, App IDs Codes ant Version, Browser Fingerprint, Device Language, Screen Dimensions & Orientation, Device Date & Time, Networking Information, & Provide a UUID. In order for this module to work, it must be hosted on your own domain in order to fingerprint the device properly. Use at your own discretion. I am not responsible for any misuse of this application. Apple changes its' terms and agreements often it is up to you to check and decide if this tool still complies wit their terms of agreement. My team and I are not liable for any misuse / damage or legal suites that derive from use of this software. It's design is for OSINT and DevOps. Cheers!</p>

### JS Functions & Usage 

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

#### Device Info Module & Usage: (How To Call)<br>

 ```
    document.write(JSON.stringify(DeviceInfo.getDeviceInfo(
         {
             domain: 'Your-Web-Domain-Where-It-Is-Hosted',
             info: ['deviceType', 'OS', 'language']
         }
     )))
 ```

#### Usage: (Display All Device Information Automatically By Default)

    window.location.host; 

#### Note: 
    A hosted domain is required to pass fingerprint and is not given by default.

 
