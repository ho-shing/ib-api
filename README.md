[![Logo](ib-logo.jpeg)](http://interactivebrokers.com/)

This is the Interactive Brokers API client library for Java. The source code is a direct clone of the official library.

Official API References:

* [Java API Getting Started](https://www.interactivebrokers.com/download/JavaAPIGettingStarted.pdf)
* [API References](https://www.interactivebrokers.com/en/software/api/api.htm)
* [Webinar - Getting Started with the Java](https://interactivebrokers.webex.com/ec3000/eventcenter/recording/recordAction.do?theAction=poprecord&AT=pb&internalRecordTicket=4832534b000000023cd7945fbdb8610c13aa63feb83ae83fc74e0a0e44f637a536847b921815f6f4&renewticket=0&isurlact=true&recordID=79512237&apiname=lsr.php&format=short&needFilter=false&&SP=EC&rID=79512237&RCID=56d97bf455054c7693ee7fdf6fb9df92&siteurl=interactivebrokers&actappname=ec3000&actname=%2Feventcenter%2Fframe%2Fg.do&rnd=7186074689&entappname=url3000&entactname=%2FnbrRecordingURL.do)

#Installation
```
repositories {
    jcenter()
}

dependencies {
    compile 'com.wilsonths:IBApi:1.0.0'
}
```

#Usage
The API is wrapped in the `com.ib.controller.ApiController` class. For more details, you can refer to the [HelloIB](https://github.com/wilsonths/hello-ib) sample program.