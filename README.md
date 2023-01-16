# engage-rtc-web-client-collocation-demo-app
Engage RTC demo application is a sample one-page website created to help Radisys Engagedigital-SDK users, how to use the SDK and its functionalities into their application. It’s an HTML & CSS based web app which demonstrate registration of user and make a video call to the service phone number passing in phone number textbox.
Js file contains complete implementation of accessing the SDK and its subsequent classes and its methods to make the call feature functional. You can explore more on how to register and listening an event, calling an API etc in [main.js](https://github.com/RSYS-EDP/engage-rtc-demo-web-app/blob/main/main.js).

## How to Proceed: 
Download the project or clone it and open the html in a browser. A web page opens as below.

![image](https://user-images.githubusercontent.com/96531226/202685877-83e2934d-61d6-436a-a122-a62514987998.png)

The domain [rtr.egagedigital.ai](https://rtc.engagedigital.ai) is a sample domain used in the code base, you can check with radisys service provider for domain address and service phone number.

Collocation/reconnect: For conference establishment, all the participants should join the media server in the same zone. If the initial call is established with a different media server, then collocation or reconnection will occur so that call or media will be reestablished.
