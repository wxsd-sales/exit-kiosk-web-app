# Exit Kiosk Web App

This is an example Webex Device Kiosk Web App which provides a way to exit Kiosk Mode on via a PIN Authentication 

![Snapshot Macro](https://github.com/wxsd-sales/exit-kiosk-webapp/assets/21026209/4dc11dd6-8320-4422-9c6b-ef57bf8f4a8d)

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
![image](https://github.com/wxsd-sales/exit-kiosk-webapp/assets/21026209/efafe00c-dacc-485a-a618-9669189dc907)


4. Set the Kiosk URL to the Exit Kiosk Web App and include the local username and password within the URL Parameters and save
      ```
      https://wxsd-sales.github.io/exit-kiosk-webapp/exitKioskWebapp.html?username=kioskwebapp&password=Cisco123
      ```
      ![image](https://github.com/wxsd-sales/exit-kiosk-webapp/assets/21026209/d26f5655-b7c1-4a75-a4b6-2a3dfb790ad0)

5. Set the Kiosk Mode to ```On``` to enable Kiosk Mode
![image](https://github.com/wxsd-sales/exit-kiosk-webapp/assets/21026209/d6b57ad4-9ebf-4464-a8dc-963cf71b2470)

    
    
## Demo

*For more demos & PoCs like this, check out our [Webex Labs site](https://collabtoolbox.cisco.com/webex-labs).

## License

All contents are licensed under the MIT license. Please see [license](LICENSE) for details.


## Disclaimer

Everything included is for demo and Proof of Concept purposes only. Use of the site is solely at your own risk. This site may contain links to third party content, which we do not warrant, endorse, or assume liability for. These demos are for Cisco Webex usecases, but are not Official Cisco Webex Branded demos.


## Questions
Please contact the WXSD team at [wxsd@external.cisco.com](mailto:wxsd@external.cisco.com?subject=Exit-Kiosk-WebApp) for questions. Or, if you're a Cisco internal employee, reach out to us on the Webex App via our bot (globalexpert@webex.bot). In the "Engagement Type" field, choose the "API/SDK Proof of Concept Integration Development" option to make sure you reach our team. 
