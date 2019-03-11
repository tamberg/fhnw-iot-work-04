# IoT Engineering
## Hands-on of lesson 4
For slides and example code, see [lesson 4](../../../fhnw-iot/blob/master/04/README.md)

> *Note: Do not work on this repository right away.*<br/>
> *[Check existing forks to find the specific repository for your class.](../../network/members)*

### a) Web services, 15'
* Build and run the previous Web service examples.
* Use the .ino link on each page to find the source.
* The examples are in the course repository.
* Make sure to use the ESP8266 board.

### b) Philips Hue, 15'
* Read the API documentation to find the following:
* API endpoints, protocols, data formats, queries.
* Try to control the Philips Hue light bulbs in class.
* Take notes about links, tools, requests used.

### c) CoAP, 15'
* Download a CoAP client and server [implementation](https://coap.technology/impls.html).
* Run it on your laptop or on the ESP8266, if possible.
* Consider using a testing service like http://coap.me/

### d) IKEA Tradfri, 15'
* Search for hints about the API to find the following:
* API endpoints, protocols, data formats, queries.
* Try to access the IKEA Tradfri gateway in class.
* Take notes about links, tools, requests used.
* Commit the file, ideally plain text.

### e) Homework, max. 3h
* Write a connected display service on the ESP8266.
* Create a RESTful Web API for the [4-digit display](https://github.com/tamberg/fhnw-iot/wiki/Grove-Actuators#4-digit-display).
* The API/Web UI should be self-documenting.
* Print the local IP address to the console.
* Commit to the hands-on repo.

### Submitting results
* [Commit and push](#git) local changes to your repository.
* Want a review? [Create an issue](../../issues/new), mention me (@tamberg).

## Tools
### Git
On your computer
* In the hands-on repository [fork for your class](../../network/members), in README.md, click the _GitHub Classroom link_.
* Once you accept the assessment, you get a personal, private repository URL for your _USER_NAME_:<pre>
http://github.com/fhnw-iot-CLASS/fhnw-iot-work-04-USER_NAME</pre>

On your computer or Raspberry Pi
* Clone the repository<pre>
    $ cd ~
    $ git clone REPO_URL</pre>
* Add a file<pre>
    $ git add FILE</pre>
* Commit changes<pre>
    $ git commit FILE -m "Fixed all bugs"</pre>
* Push changes<pre>
    $ git push</pre>

## Wiki
- [IoT Engineering Wiki](https://github.com/tamberg/fhnw-iot/wiki)

## Support
- [IoT Engineering Slack](https://fhnw-iot.slack.com/)
