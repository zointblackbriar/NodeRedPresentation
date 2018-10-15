A visual tool for wiring the Internet of Things.

![Node-RED: A visual tool for wiring the Internet of Things](http://nodered.org/images/node-red-screenshot.png)

Tested with Ubuntu 16.04 LTS 
npm version -- 6.4.1
nodejs version --- v10.11.0

Tested with Windows 10
npm version -- 5.6.0
nodejs version -- v8.11.1

If you want to run the latest code from git, here's how to get started:

1. Clone the code:

        git clone git@github.com:zointblackbriar/NodeRedPresentation.git
        cd NodeRedPresentation

2. Install the node-red dependencies

        npm install

Note: If you get some errors when you typed "npm run build" command, you should type before the command as below, respectively

a) npm rebuild
b) npm update

3. Build the code

        npm run build

4. Run

        npm start
   or

        node red.js
		

After your installation part is finished, you need to configure your nodes manually because of "npm run build" command.
You can find the node configuration under the folder named "node-red-flows"
Configuration Part

The following screenshot taken from real-time view.

## Analog Measurement
![AnalogMeasurement](https://github.com/zointblackbriar/NodeRedPresentation/blob/master/img/NodeRedPresentation/Analog_Mesurement.png)

## Panel
![Panel](https://github.com/zointblackbriar/NodeRedPresentation/blob/master/img/NodeRedPresentation/panel.png)


## Sensors of Fraunhofer
![Sensors](https://github.com/zointblackbriar/NodeRedPresentation/blob/master/img/NodeRedPresentation/Sensors.png)

If you require to use the feature of Real Time Database, you may configure as described below

In Intro Page, as you can see that we need to create a Real Time Database

![Intro Page](https://github.com/zointblackbriar/NodeRedPresentation/blob/master/img/NodeRedPresentation/Firebase_Intro.png)

As depicted image below, database might be configure to show about statistics of result

![Index Page](https://github.com/zointblackbriar/NodeRedPresentation/blob/master/img/NodeRedPresentation/Firebase_Index_HTML.png)

You should create a Realtime Database in the page as below

![Database Intro Page](https://github.com/zointblackbriar/NodeRedPresentation/blob/master/img/NodeRedPresentation/Database_Intro.png)

If you configured your page correctly, you will see result of MQTT data as depicted.

![Database_Action Page](https://github.com/zointblackbriar/NodeRedPresentation/blob/master/img/NodeRedPresentation/Database_Action.png)

The following image is your MQTT node in node-red platform. Please assign your settings properly.

![Configuration Page](https://github.com/zointblackbriar/NodeRedPresentation/blob/master/img/NodeRedPresentation/Configuration.png)




## Contributing

Before raising a pull-request, please read our
[contributing guide](https://github.com/node-red/node-red/blob/master/CONTRIBUTING.md).

This project adheres to the [Contributor Covenant 1.4](http://contributor-covenant.org/version/1/4/).
 By participating, you are expected to uphold this code. Please report unacceptable
 behavior to any of the project's core team at team@nodered.org.

## Authors

Node-RED is a project of the [JS Foundation](http://js.foundation).

It was created by [IBM Emerging Technology](https://www.ibm.com/blogs/emerging-technology/).

* Nick O'Leary [@knolleary](http://twitter.com/knolleary)
* Dave Conway-Jones [@ceejay](http://twitter.com/ceejay)



## Copyright and license

Copyright JS Foundation and other contributors, http://js.foundation under [the Apache 2.0 license](LICENSE).
