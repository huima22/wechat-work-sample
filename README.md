# WeChat Work Sample

This sample illustrates the scenario of sending a Welcome note to a new
external contact
 
## Authenticate API
One off authentication using corpid and corpsecret to retrieve access_token,
which will be used in the subsequent API calls
https://work.weixin.qq.com/api/doc/90000/90135/91039

## Creating a Message Receiving Server URL

## Subscribe to news and events
In order to allow two-way communication between self-built applications and enterprise WeChat, enterprises can enable the receive message mode in the application management background.
Enterprises that enable the message receiving mode need to provide the available message receiving server URL (https is recommended).

https://work.weixin.qq.com/api/doc/90000/90135/90237

Enterprise needs to provide 
- token for authenticating the event received from the message receiving URL
- AES Key for encrypting the message

## Receiving events - e.g. Adding an external contact
https://work.weixin.qq.com/api/doc/90000/90135/92130#%E6%B7%BB%E5%8A%A0%E4%BC%81%E4%B8%9A%E5%AE%A2%E6%88%B7%E4%BA%8B%E4%BB%B6

From this API we can get the welcome_code for sending welcome note for the new customer
 
## Send new customer welcome message
Require welcome_code
https://work.weixin.qq.com/api/doc/90000/90135/92137
