# IoT Engineering
## Hands-on of lesson 4
For slides and example code, see [lesson 4](../../../fhnw-iot/blob/master/04/README.md)

> *Note: Do not work on this repository right away.*<br/>
> *[Check existing forks to find the specific repository for your class.](../../network/members)*

### a) Web services, 15'
* Build and run the previous Web service examples.
* Use the .ino link on each page to find the source.
* Check the serial monitor to see the server IP.
* Use your browser and Curl as Web clients.
* Is there a difference between clients?
* Done? Here's a bonus [example](https://github.com/tamberg/fhnw-iot/blob/master/04/Arduino/ESP8266_WebServerSecureBasicAuth/ESP8266_WebServerSecureBasicAuth.ino) to study.

### b) Philips Hue API, 15'
* Read the API documentation to find the following:
* API endpoints, protocols, data formats, queries.
* Try to control the Philips Hue lights in class.
* Take notes on links, tools, requests used.

### c) CoAP, 15'
* Download a CoAP client and server [implementation](https://coap.technology/impls.html).
* Run it on your laptop or on the ESP8266, if possible.
* Consider using a testing service like http://coap.me/

### d) IKEA Tradfri, 15'
* Search for hints about the API to find the following:
* API endpoints, protocols, data formats, queries.
* Try to access the IKEA Tradfri gateway in class.
* Take notes about links, tools, requests used.

### e) Challenge
* Write a connected display service on the ESP8266.
* Create a RESTful Web API for the [4-digit display](https://github.com/tamberg/fhnw-iot/wiki/Grove-Actuators#4-digit-display).
* Document the HTTP calls your API can handle.
* Print the service IP address to the console.
* Commit to the hands-on repo.
