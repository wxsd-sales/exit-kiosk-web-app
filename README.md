# Exit Kiosk Web App

This is an example Webex Device Kiosk Web App demonstrates how a Web App can disable Kiosk Mode on the Webex Device in which it is being displayed on.

![Snapshot Macro](https://github.com/wxsd-sales/exit-kiosk-web-app/assets/21026209/7b0dd5c1-e88c-450f-83a9-e0e55004ba51)


## Overview

The example Bank Kiosk Web App features a PIN Authentication modal where entering the correct PIN will cause the Web App to make a local WebSocket connect to the Webex Device which is running on and then make a configuration change to disable kiosk mode.

## Setup

### Prerequisites & Dependencies: 

- Webex Device with RoomOS 11.8 or Greater
- Web admin access to the device configure Kiosk mode and Create Local Account
- (Optional) Web Server for hosting a custom copy of this example Web App


<!-- GETTING STARTED -->

### Installation Steps:
1.  Log into your Webex Devices web interface
2.  Set WebEngine Mode to ```On``` and AllowDeviceCertificate to ```True```
3.  Create a local account on the device with ```integrator``` role and disable the password reset requirement. Note the username and password for the next step
![image](https://github.com/wxsd-sales/exit-kiosk-web-app/assets/21026209/d07662ac-4e6a-4124-93ca-ae2cd2889557)



4. Set the Kiosk URL to the Exit Kiosk Web App and include the local username and password within the URL Parameters and save
      ```
      https://wxsd-sales.github.io/exit-kiosk-web-app/exitKioskWebapp.html?username=kioskwebapp&password=Cisco123
      ```
      ![image](https://github.com/wxsd-sales/exit-kiosk-web-app/assets/21026209/584f4009-1f33-4ff6-9d1d-ebf683ccf69c)


5. Set the Kiosk Mode to ```On``` to enable Kiosk Mode
![image](https://github.com/wxsd-sales/exit-kiosk-web-app/assets/21026209/d5a82808-aa6d-453e-ab3d-8f6bc3ef6f83)


    
    
## Demo

*For more demos & PoCs like this, check out our [Webex Labs site](https://collabtoolbox.cisco.com/webex-labs).

## License

All contents are licensed under the MIT license. Please see [license](LICENSE) for details.


## Disclaimer

Everything included is for demo and Proof of Concept purposes only. Use of the site is solely at your own risk. This site may contain links to third party content, which we do not warrant, endorse, or assume liability for. These demos are for Cisco Webex use cases, but are not Official Cisco Webex Branded demos.


## Questions
Please contact the WXSD team at [wxsd@external.cisco.com](mailto:wxsd@external.cisco.com?subject=Exit-Kiosk-WebApp) for questions. Or, if you're a Cisco internal employee, reach out to us on the Webex App via our bot (globalexpert@webex.bot). In the "Engagement Type" field, choose the "API/SDK Proof of Concept Integration Development" option to make sure you reach our team. 
