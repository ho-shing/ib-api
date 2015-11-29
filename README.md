[![Logo](ib-logo.jpeg)](http://interactivebrokers.com/)

This is the Interactive Brokers API client library for Java. The source code is a direct clone of the official library.

Official API References:

* [Java API Getting Started](https://www.interactivebrokers.com/download/JavaAPIGettingStarted.pdf)
* [API References](https://www.interactivebrokers.com/en/software/api/api.htm)

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