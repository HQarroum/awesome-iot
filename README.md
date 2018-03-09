# Awesome IoT

<img src="iot-logo.png" align="right" width="100">

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/HQarroum/awesome-iot.svg?branch=master)](https://travis-ci.org/HQarroum/awesome-iot)

> A curated list of awesome Internet of Things projects and resources.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.

## Table of Contents

- [Hardware](#hardware)
- [Software](#software)
  - [Operating systems](#operating-systems)
  - [Programming Languages](#programming-languages)
  - [Frameworks](#frameworks)
  - [Middlewares](#middlewares)
  - [Libraries and Tools](#libraries-and-tools)
  - [Miscellaneous](#miscellaneous)
- [Protocols and Networks](#protocols-and-networks)
- [Technologies](#technologies)
- [Standards and Alliances](#standards-and-alliances)
- [Resources](#resources)
  - [Books](#books)
  - [Articles](#articles)
  - [Papers](#papers)

### Hardware

- [Arduino](https://www.arduino.cc/) - Arduino is an open-source electronics platform based on easy-to-use hardware and software. It's intended for anyone making interactive projects.
- [BeagleBoard](http://beagleboard.org/) - The BeagleBoard is a low-power open-source hardware single-board computer produced by Texas Instruments in association with Digi-Key and Newark element14.
- [Dragonboard](https://developer.qualcomm.com/hardware/dragonboard-410c) - The DragonBoard 410c, a product of Arrow Electronics, is the development board based on the mid-tier Qualcomm® Snapdragon™ 410E processor. It features advanced processing power, Wi-Fi, Bluetooth connectivity, and GPS, all packed into a board the size of a credit card.
- [HummingBoard](https://www.solid-run.com/freescale-imx6-family/hummingboard/) - HummingBoard is a family of three Linux- and Android-ready, open source SBCs based on 1GHz Freescale i.MX6 SoCs, with a Pi-like 26-pin I/O connector.
- [Intel Galileo](https://www-ssl.intel.com/content/www/us/en/do-it-yourself/galileo-maker-quark-board.html) - The Intel® Galileo Gen 2 board is the first in a family of Arduino*-certified development and prototyping boards based on Intel® architecture and specifically designed for makers, students, educators, and DIY electronics enthusiasts.
- [Microduino](https://www.microduino.cc/) - Microduino and mCookie bring powerful, small, stackable electronic hardware to makers, designers, engineers, students and curious tinkerers of all ages. Build open-source projects or create innovative new ones.
- [Node MCU (ESP 8266)](http://nodemcu.com/index_en.html) - NodeMCU is an open source IoT platform. It uses the Lua scripting language. It is based on the eLua project, and built on the ESP8266 SDK 0.9.5.
- [OLinuXino](https://www.olimex.com/Products/OLinuXino/open-source-hardware) - OLinuXino is an Open Source Software and Open Source Hardware low cost (EUR 30) Linux Industrial grade single board computer with GPIOs capable of operating from -25°C to +85°C.
- [Odroid](http://www.hardkernel.com/) - The ODROID means Open + Droid. It is a development platform for the hardware as well as the software.
- [Particle](https://www.particle.io) - A suite of hardware and software tools to help you prototype, scale, and manage your Internet of Things products.
- [Pinoccio](https://www.open-electronics.org/pinoccio-wifi-mesh-networking-for-arduino-and-iot-available-now/) - Pinoccio is a solution to add mesh networking capability and WiFi-Internet access to all yout IoT devices, and it is Arduino compatible.
- [Raspberry Pi](https://www.raspberrypi.org/) - The Raspberry Pi is a low cost, credit-card sized computer that plugs into a computer monitor or TV, and uses a standard keyboard and mouse. It’s capable of doing everything you’d expect a desktop computer to do, from browsing the internet and playing high-definition video, to making spreadsheets, word-processing, and playing games.
- [Tessel](https://tessel.io/) - Tessel is a completely open source and community-driven IoT and robotics development platform. It encompases development boards, hardware module add-ons, and the software that runs on them.
- [UDOO](http://www.udoo.org) - UDOO is a single-board computer with an integrated Arduino 2 compatible microcontroller, designed for computer science education, the world of Makers and the Internet of Things.

### Software

#### Operating systems

 - [Apache Mynewt](https://mynewt.apache.org/) - Apache Mynewt is a real-time, modular operating system for connected IoT devices that need to operate for long periods of time under power, memory, and storage constraints. The first connectivity stack offered is BLE 4.2.
 - [ARM mbed](http://www.mbed.com/) - The ARM® mbed™ IoT Device Platform provides the operating system, cloud services, tools and developer ecosystem to make the creation and deployment of commercial, standards-based IoT solutions possible at scale.
 - [Contiki](http://www.contiki-os.org/) - Contiki is an open source operating system for the Internet of Things. Contiki connects tiny low-cost, low-power microcontrollers to the Internet.
 - [FreeRTOS](http://www.freertos.org/) - FreeRTOS is a popular real-time operating system kernel for embedded devices, that has been ported to 35 microcontrollers.
 - [Google Brillo](https://developers.google.com/brillo/) - Brillo extends the Android platform to all your connected devices, so they are easy to set up and work seamlessly with each other and your smartphone.
 - [OpenWrt](https://openwrt.org/) - OpenWrt is an operating system (in particular, an embedded operating system) based on the Linux kernel, primarily used on embedded devices to route network traffic. The main components are the Linux kernel, util-linux, uClibc or musl, and BusyBox. All components have been optimized for size, to be small enough for fitting into the limited storage and memory available in home routers.
 - [Snappy Ubuntu](https://developer.ubuntu.com/en/snappy/) - Snappy Ubuntu Core is a new rendition of Ubuntu with transactional updates.  It provides a minimal server image with the same libraries as today’s Ubuntu, but applications are provided through a simpler mechanism.
 - [NodeOS](http://node-os.com/) - NodeOS is an operating system entirely written in Javascript, and managed by npm on top of  the Linux kernel.
 - [Raspbian](https://raspbian.org/) - Raspbian is a free operating system based on Debian optimized for the Raspberry Pi hardware.
 - [RIOT](http://www.riot-os.org/) - The friendly Operating System for the Internet of Things.
 - [Tiny OS](http://tinyos.stanford.edu/tinyos-wiki/index.php/TinyOS_Overview) - TinyOS is an open source, BSD-licensed operating system designed for low-power wireless devices, such as those used in sensor networks, ubiquitous computing, personal area networks, smart buildings, and smart meters.
 - [Windows 10 IoT Core](https://dev.windows.com/en-us/iot) - Windows 10 IoT is a family of Windows 10 editions targeted towards a wide range of intelligent devices, from small industrial gateways to larger more complex devices like point of sales terminals and ATMs.
  - [Zephyr Project](https://www.zephyrproject.org/) - The Zephyr™ Project is a scalable real-time operating system (RTOS) supporting multiple hardware architectures, optimized for resource constrained devices, and built with security in mind.

#### Programming languages

> This sections regroups every awesome programming language, whether it is compiled, interpreted or a DSL, related to embedded development.

 - [C](https://en.wikipedia.org/wiki/C_(programming_language)) - A general-purpose, imperative computer programming language, supporting structured programming, lexical variable scope and recursion, while a static type system prevents many unintended operations.
 - [C++](https://en.wikipedia.org/wiki/C%2B%2B) - A general-purpose programming language. It has imperative, object-oriented and generic programming features, while also providing facilities for low-level memory manipulation.
 - [Groovy](http://www.groovy-lang.org/) - Groovy is a powerful, optionally typed and dynamic language, with static-typing and static compilation capabilities, for the Java platform aimed at multiplying developers’ productivity thanks to a concise, familiar and easy to learn syntax. It is used by the SmartThings development environment to create smart applications.
 - [Lua](http://www.lua.org/) - Lua is a powerful, fast, lightweight, embeddable scripting language. Lua is dynamically typed, runs by interpreting bytecode for a register-based virtual machine, and has automatic memory management with incremental garbage collection, making it ideal for configuration, scripting, and rapid prototyping.
 - [eLua](http://www.eluaproject.net/) - eLua stands for Embedded Lua and the project offers the full implementation of the Lua Programming Language to the embedded world, extending it with specific features for efficient and portable software embedded development.
 - [ELFE](http://c3d.github.io/elfe/) - ELFE is a very simple and small programming language. While it is a general-purpose programming language, it is specifically tuned to facilitate the configuration and control of swarms of small devices such as sensors or actuators.

#### Frameworks

 - [AllJoyn](https://openconnectivity.org/developer/reference-implementation/alljoyn) - AllJoyn is an open source software framework that makes it easy for devices and apps to discover and communicate with each other.
 - [Apple HomeKit](https://developer.apple.com/homekit/) - HomeKit is a framework for communicating with and controlling connected accessories in a user’s home.
 - [Blynk](http://www.blynk.cc) - Blynk is a platform for creating iOS and Android apps for connected things. You can easily build graphic interfaces for all your projects by simply dragging and dropping widgets (right on the smartphone). Supports Ethernet, WiFi, Bluetooth, GSM/GPRS, USB/Serial connections with wide range of prototyping platforms from Arduino, Raspberry, ARM mbed, Particle, RedBear, etc.
 - [Countly IoT Analytics](http://github.com/countly/countly-server) - Countly is a general purpose analytics platform for mobile and IoT devices, available as open source.
 - [Eclipse Smarthome](https://eclipse.org/smarthome/) - The Eclipse SmartHome framework is designed to run on embedded devices, such as a Raspberry Pi, a BeagleBone Black or an Intel Edison. It requires a Java 7 compliant JVM and an OSGi (4.2+) framework, such as Eclipse Equinox.
 - [Freedomotic](http://www.freedomotic.com) - Freedomotic is an open source, flexible, secure Internet of Things (IoT) development framework, useful to build and manage modern smart spaces. It is targeted to private individuals (home automation) as well as business users (smart retail environments, ambient aware marketing, monitoring and analytics, etc). Written in Java, it can interact with well known standard building automation protocols as well as with "do it yourself" solutions.
 - [Iotivity](https://www.iotivity.org/) - IoTivity is an open source software framework enabling seamless device-to-device connectivity to address the emerging needs of the Internet of Things.
 - [Kura](https://eclipse.org/kura/) - Kura aims at offering a Java/OSGi-based container for M2M applications running in service gateways. Kura provides or, when available, aggregates open source implementations for the most common services needed by M2M applications.
 - [Lelylan](http://www.lelylan.com/) - Lelylan is an IoT cloud platform based on a lightweight microservices architecture. The Lelylan platform is both hardware-agnostic and platform-agnostic. This means that you can connect any hardware, from the ESP8266 to the most professional embedded hardware solution and everything in between - and it can run on any public cloud, your own private datacenter, or even in a hybrid environment, whether virtualized or bare metal.
 - [Mihini](https://wiki.eclipse.org/Mihini) - The main goal of Mihini is to deliver an embedded runtime running on top of Linux, that exposes high-level API for building M2M applications. Mihini aims at enabling easy and portable development, by facilitating access to the I/Os of an M2M system, providing a communication layer, etc.
 - [OpenHAB](http://www.openhab.org/) - The openHAB runtime is a set of OSGi bundles deployed on an OSGi framework (Equinox). It is therefore a pure Java solution and needs a JVM to run. Being based on OSGi, it provides a highly modular architecture, which even allows adding and removing functionality during runtime without stopping the service.
 - [Gobot](http://gobot.io/) - Gobot is a framework for robotics, physical computing, and the Internet of Things, written in the Go programming language.
 - [Home Assistant](https://github.com/home-assistant/home-assistant) - Home Assistant is a home automation platform running on Python 3. The goal of Home Assistant is to be able to track and control all devices at home and offer a platform for automating control.
 - [Lightweight MQTT Machine Network](http://lwmqn.github.io/) - LWMQN is an open source project that follows part of OMA LWM2M v1.0 specification and uses the IP-base Smart Object model to meet the minimum requirements of machine network management. It provides both server-side and machine-side libraries to make full-stack IoT development possible with JavaScript and Node.js. See also: IPSO Alliance [Technical Archive](http://www.ipso-alliance.org/ipso-community/resources/technical-archive/).
 - [Thingsboard IoT Gateway](https://github.com/thingsboard/thingsboard-gateway) - Open-source IoT Gateway - integrates devices connected to legacy and third-party systems with Thingsboard IoT Platform using OPC-UA and MQTT protocols.
 - [Pimatic](https://pimatic.org/) - Pimatic is a home automation framework that runs on node.js. It provides a common extensible platform for home control and automation tasks.
 - [IOTA](https://dev.iota.org/) - Open-source distributed ledger protocol for IoT. Uses a directed acyclic graph (DAG) instead of a blockchain.

#### Middlewares

 - [Corlysis](https://corlysis.com/) - Corlysis is a platform that helps you with storing and visualizing your time-series data. It is based on the open-source projects Grafana and InfluxDB that also SpaceX uses.
 - [IFTTT](https://ifttt.com/) - IFTTT is a web-based service that allows users to create chains of simple conditional statements, called "recipes", which are triggered based on changes to other web services such as Gmail, Facebook, Instagram, and Pinterest. IFTTT is an abbreviation of "If This Then That" (pronounced like "gift" without the "g").
 - [Huginn](https://github.com/cantino/huginn) - Huginn is a system for building agents that perform automated tasks for you online.
 - [Kaa](http://www.kaaproject.org/) - An open-source middleware platform for rapid creation of IoT solutions.
 - [Losant](https://losant.com) - Losant is an easy-to-use and powerful developer platform designed to help you quickly and securely build complex connected solutions. Losant uses open communication standards like REST and MQTT to provide connectivity from one to millions of devices. Losant provides powerful data collection, aggregation, and visualization features to help understand and quantify vast amounts of sensor data. Losant's drag-and-drop workflow editor allows you to trigger actions, notifications, and machine-to-machine communication without programming.
 - [DreamFactory](http://www.dreamfactory.com) - DreamFactory is a free open source REST API Platform for mobile, web and IoT Applications.
 - [I1820](https://i1820.github.io/) - I1820 is a free open source platform which provides discovery, data collection and configuration services based on MQTT. I1820 implements a REST API for controlling the things and it stores all collected data in a Time-Series database named InfluxDB.
 - [IOStash](https://iostash.io) - IOStash is a high performance IoT platform that is free for DIY developers and non profit applications. It has multiple connectivity options and enables easy development of M2M or M2A applications. IOStash offers Nodejs and Android libraries for easy application creation. 
 - [Thingsboard](https://thingsboard.io) - An open-source IoT platform. Device management, data collection, processing and visualization for your IoT solution.

#### Libraries and Tools

 - [Cylon.js](http://cylonjs.com/) - Cylon.js is a JavaScript framework for robotics, physical computing, and the Internet of Things. It makes it incredibly easy to command robots and devices.
 - [Luvit](https://luvit.io/) - Luvit implements the same APIs as Node.js, but in Lua ! While this framework is not directly involved with IoT development, it is still a *great* way to rapidly build powerful, yet memory efficient, embedded web applications.
 - [Johnny-Five](http://johnny-five.io/) - Johnny-Five is the original JavaScript Robotics programming framework. Released by Bocoup in 2012, Johnny-Five is maintained by a community of passionate software developers and hardware engineers.
 - [Pi4J](http://pi4j.com/) - Pi4j is intended to provide a friendly object-oriented I/O API and implementation libraries for Java Programmers to access the full I/O capabilities of the Raspberry Pi platform.
 - [WiringPi](http://wiringpi.com/) - WiringPi is a GPIO access library written in C for the BCM2835 used in the Raspberry Pi.
 - [Node-RED](http://nodered.org/) - A visual tool for wiring the Internet of Things.
 - [SmartObject](https://github.com/PeterEB/smartobject) - A Smart Object Class that helps you with creating IPSO Smart Objects in your JavaScript applications. See also: IPSO Alliance [Technical Archive](http://www.ipso-alliance.org/ipso-community/resources/technical-archive/).

#### Miscellaneous

 - [Amazon Dash](https://fresh.amazon.com/dash/) - Amazon Dash Button is a Wi-Fi connected device that reorders your favorite item with the press of a button.
 - [Freeboard](http://freeboard.io/) - A real-time interactive dashboard and visualization creator implementing an intuitive drag & drop interface.
 - [Nebula](http://nebula.readthedocs.io) -  A docker orchestrator designed to manage IoT devices

## Protocols and Networks

### Physical layer

#### <img width="50" src="http://www.ieee802.org/15/pub/ieee802-15%20logo.jpg" /> - [802.15.4](https://en.wikipedia.org/wiki/IEEE_802.15.4) (IEEE)

IEEE 802.15.4 is a standard which specifies the physical layer and media access control for low-rate wireless personal area networks (LR-WPANs). It is maintained by the IEEE 802.15 working group, which has defined it in 2003. It is the basis for the ZigBee, ISA100.11a, WirelessHART, and MiWi specifications, each of which further extends the standard by developing the upper layers which are not defined in IEEE 802.15.4. Alternatively, it can be used with 6LoWPAN and standard Internet protocols to build a wireless embedded Internet. - [Wikipedia](https://en.wikipedia.org/wiki/IEEE_802.15.4)

> IEEE standard 802.15.4 intends to offer the fundamental lower network layers of a type of wireless personal area network (WPAN) which focuses on low-cost, low-speed ubiquitous communication between devices. It can be contrasted with other approaches, such as Wi-Fi, which offer more bandwidth and require more power. The emphasis is on very low cost communication of nearby devices with little to no underlying infrastructure, intending to exploit this to lower power consumption even more.

#### <img width="50" src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fc/BluetoothLogo.svg/770px-BluetoothLogo.svg.png" /> - [Bluetooth](https://en.wikipedia.org/wiki/Bluetooth) (Bluetooth Special Interest Group)

Bluetooth is a wireless technology standard for exchanging data over short distances (using short-wavelength UHF radio waves in the ISM band from 2.4 to 2.485 GHz) from fixed and mobile devices, and building personal area networks (PANs). Invented by telecom vendor Ericsson in 1994, it was originally conceived as a wireless alternative to RS-232 data cables. It can connect several devices, overcoming problems of synchronization. - [Wikipedia](https://en.wikipedia.org/wiki/Bluetooth)

> Bluetooth is managed by the Bluetooth Special Interest Group (SIG), which has more than 25,000 member companies in the areas of telecommunication, computing, networking, and consumer electronics.

#### <img width="50" src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/20/Bluetooth_Smart_Logo.svg/241px-Bluetooth_Smart_Logo.svg.png" /> - [Bluetooth Low Energy](https://en.wikipedia.org/wiki/Bluetooth_low_energy) (Bluetooth Special Interest Group)

Bluetooth low energy (Bluetooth LE, BLE, marketed as Bluetooth Smart) is a wireless personal area network technology designed and marketed by the Bluetooth Special Interest Group aimed at novel applications in the healthcare, fitness, beacons, security, and home entertainment industries. - [Wikipedia](https://en.wikipedia.org/wiki/Bluetooth_low_energy)

> Compared to Classic Bluetooth, Bluetooth Smart is intended to provide considerably reduced power consumption and cost while maintaining a similar communication range. The Bluetooth SIG predicts that by 2018 more than 90 percent of Bluetooth-enabled smartphones will support Bluetooth Smart.

#### [EC-GSM-IoT](http://www.gsma.com/connectedliving/extended-coverage-gsm-internet-of-things-ec-gsm-iot/) (EC-GSM-IoT Group)

Extended coverage GSM IoT (EC-GSM-IoT) is a standard-based Low Power Wide Area technology. It is based on eGPRS and designed as a high capacity, long range, low energy and low complexity cellular system for IoT communications.

> The EC-GSM-IOT network trials have begun, with the first commercial launches planned for 2017. Supported by all major mobile equipment, chip set and module manufacturers, EC-GSM-IoT networks will co-exist with 2G, 3G, and 4G mobile networks. It will also benefit from all the security and privacy mobile network features, such as support for user identity confidentiality, entity authentication, confidentiality, data integrity, and mobile equipment identification.

#### <img width="50" src="https://intelilight.eu/wp-content/uploads/2017/02/technology_lorawan.png" /> - [LoRaWAN](https://en.wikipedia.org/wiki/LoRaWAN) (LoRa Alliance)

A LoRaWAN wide area network allows low bit rate communication from and to connected objects, thus participating to Internet of Things, machine-to-machine M2M, and smart city. - [Wikipedia](https://en.wikipedia.org/wiki/LoRaWAN)

> This technology is standardized by the LoRa Alliance. It was initially developed by Cycleo, which was acquired by Semtech in 2012. LoRaWAN is an acronym for Long Range Wide-area network.

#### [NB-IoT](https://en.wikipedia.org/wiki/NarrowBand_IOT) (3GPP)

NarrowBand IoT (NB-IoT) is a Low Power Wide Area Network (LPWAN) radio technology standard that has been developed to enable a wide range of devices and services to be connected using cellular telecommunications bands. - [Wikipedia](https://en.wikipedia.org/wiki/NarrowBand_IOT)

> NB-IoT is a narrowband radio technology designed for the Internet of Things (IoT), and is one of a range of Mobile IoT (MIoT) technologies standardized by the 3rd Generation Partnership Project (3GPP).

#### <img width="50" src="http://www.silvereco.fr/wp-content/uploads/2015/02/logo510f703a4647f1.jpg" /> - [Sigfox](https://en.wikipedia.org/wiki/Sigfox) (Sigfox)

Sigfox is a French firm that builds wireless networks to connect low-energy objects such as electricity meters, smart watches, and washing machines, which need to be continuously on and emitting small amounts of data. Its infrastructure is intended to be a contribution to what is known as the Internet of Things (IoT). - [Wikipedia](https://en.wikipedia.org/wiki/Sigfox)

> SIGFOX describes itself as "the first and only company providing global cellular connectivity for the Internet of Things." Its infrastructure is "completely independent of existing networks, such as telecommunications networks." SIGFOX seeks to provide the means for the "deployment of billions of objects and thousands of new uses" with the long-term goal of "having petabytes of data produced by everyday objects".

#### <img width="50" src="https://upload.wikimedia.org/wikipedia/commons/f/f8/Wi-FI_Alliance_Logo.png" /> - [Wi-Fi](https://en.wikipedia.org/wiki/Wi-Fi) (Wi-Fi Alliance)

Wi-Fi (or WiFi) is a local area wireless computer networking technology that allows electronic devices to network, mainly using the 2.4 gigahertz (12 cm) UHF and 5 gigahertz (6 cm) SHF ISM radio bands. - [Wikipedia](https://en.wikipedia.org/wiki/Wi-Fi)

> The Wi-Fi Alliance defines Wi-Fi as any "wireless local area network" (WLAN) product based on the Institute of Electrical and Electronics Engineers' (IEEE) 802.11 standards.[1] However, the term "Wi-Fi" is used in general English as a synonym for "WLAN" since most modern WLANs are based on these standards. "Wi-Fi" is a trademark of the Wi-Fi Alliance. The "Wi-Fi Certified" trademark can only be used by Wi-Fi products that successfully complete Wi-Fi Alliance interoperability certification testing.

### Network / Transport layer

#### <img width="50" src="http://www.tonex.com/wp-content/uploads/6lowpan.jpg" /> - [6LowPan](https://en.wikipedia.org/wiki/6LoWPAN) (IETF)

6LoWPAN is an acronym of IPv6 over Low power Wireless Personal Area Networks. 6LoWPAN is the name of a concluded working group in the Internet area of the IETF. - [Wikipedia](https://en.wikipedia.org/wiki/6LoWPAN)

> The 6LoWPAN concept originated from the idea that "the Internet Protocol could and should be applied even to the smallest devices,"and that low-power devices with limited processing capabilities should be able to participate in the Internet of Things.
The 6LoWPAN group has defined encapsulation and header compression mechanisms that allow IPv6 packets to be sent and received over IEEE 802.15.4 based networks. IPv4 and IPv6 are the work horses for data delivery for local-area networks, metropolitan area networks, and wide-area networks such as the Internet. Likewise, IEEE 802.15.4 devices provide sensing communication-ability in the wireless domain. The inherent natures of the two networks though, are different.

#### <img width="50" src="http://www.twice.com/sites/default/files/styles/blog_content/public/ThreadGroupLogo_4_3_0.jpg?itok=SmyKXf7r" /> - [Thread](http://threadgroup.org/) (Thread Group)

Thread is an IPv6 based protocol for "smart" household devices to communicate on a network.

> In July 2014 Google Inc's Nest Labs announced a working group with the companies Samsung, ARM Holdings, Freescale, Silicon Labs, Big Ass Fans and the lock company Yale in an attempt to have Thread become the industry standard by providing Thread certification for products. Other protocols currently in use include ZigBee and Bluetooth Smart.
Thread uses 6LoWPAN, which in turn uses the IEEE 802.15.4 wireless protocol with mesh communication, as does ZigBee and other systems. Thread however is IP-addressable, with cloud access and AES encryption. It supports over 250 devices on a network.

#### <img width="50" src="http://www.zenatik.com/img/cms/zigbee.png" /> - [ZigBee](https://en.wikipedia.org/wiki/ZigBee) (ZigBee Alliance)

ZigBee is a IEEE 802.15.4-based specification for a suite of high-level communication protocols used to create personal area networks with small, low-power digital radios. - [Wikipedia](https://en.wikipedia.org/wiki/ZigBee)

> The technology defined by the ZigBee specification is intended to be simpler and less expensive than other wireless personal area networks (WPANs), such as Bluetooth or Wi-Fi. Applications include wireless light switches, electrical meters with in-home-displays, traffic management systems, and other consumer and industrial equipment that requires short-range low-rate wireless data transfer.

#### <img width="50" src="https://upload.wikimedia.org/wikipedia/commons/0/08/Z-Wave_logo.jpg" /> - [Z-Wave](http://www.z-wave.com/) (Z-Wave Alliance)

Z-Wave is a wireless communications specification designed to allow devices in the home (lighting, access controls, entertainment systems and household appliances, for example) to communicate with one another for the purposes of home automation. - [Wikipedia](https://en.wikipedia.org/wiki/Z-Wave)

> Z-Wave technology minimizes power consumption so that it is suitable for battery-operated devices. Z-Wave is designed to provide, reliable, low-latency transmission of small data packets at data rates up to 100kbit/s, unlike Wi-Fi and other IEEE 802.11-based wireless LAN systems that are designed primarily for high data rates. Z-Wave operates in the sub-gigahertz frequency range, around 900 MHz.

### Application layer

#### [CoAP](http://coap.technology/) (IETF)

Constrained Application Protocol (CoAP) is a software protocol intended to be used in very simple electronics devices that allows them to communicate interactively over the Internet. - [Wikipedia](https://en.wikipedia.org/wiki/Constrained_Application_Protocol)

> CoAP is particularly targeted for small low power sensors, switches, valves and similar components that need to be controlled or supervised remotely, through standard Internet networks. CoAP is an application layer protocol that is intended for use in resource-constrained internet devices, such as WSN nodes.

#### [DTLS](https://fr.wikipedia.org/wiki/Datagram_Transport_Layer_Security) (IETF)

The Datagram Transport Layer Security (DTLS) communications protocol provides communications security for datagram protocols.  - [Wikipedia](https://fr.wikipedia.org/wiki/Datagram_Transport_Layer_Security)

> DTLS allows datagram-based applications to communicate in a way that is designed[by whom?] to prevent eavesdropping, tampering, or message forgery. The DTLS protocol is based on the stream-oriented Transport Layer Security (TLS) protocol and is intended to provide similar security guarantees.

#### <img width="50" src="https://cdn.arstechnica.net/wp-content/uploads/2015/07/2015-07-13_16-46-26.jpg" /> - [Eddystone](https://en.wikipedia.org/wiki/Eddystone_(Google)) (Google)

Eddystone is a beacon technology profile released by Google in July 2015. The open source, cross-platform software gives users location and proximity data via Bluetooth low-energy beacon format. - [Wikipedia](https://en.wikipedia.org/wiki/Eddystone_(Google))

> Though similar to the iBeacon released by Apple in 2013, Eddystone works on both Android and iOS, whereas iBeacon is limited to iOS platforms. A practical application of both softwares is that business owners can target potential customers based on the location of their smartphones in real time.

#### <img width="50" src="http://www.httptechnology.com.au/logo.jpg" /> - [HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol) (IETF)

The Hypertext Transfer Protocol (HTTP) is an application protocol for distributed, collaborative, hypermedia information systems. HTTP is the foundation of data communication for the World Wide Web. - [Wikipedia](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)

> The standards development of HTTP was coordinated by the Internet Engineering Task Force (IETF) and the World Wide Web Consortium (W3C), culminating in the publication of a series of Requests for Comments (RFCs). The first definition of HTTP/1.1, the version of HTTP in common use, occurred in RFC 2068 in 1997, although this was obsoleted by RFC 2616 in 1999.

#### <img width="50" src="https://developer.apple.com/ibeacon/images/ibeacon-logo.svg" /> - [iBeacon](https://en.wikipedia.org/wiki/IBeacon) (Apple)

iBeacon is a protocol standardized by Apple and introduced at the Apple Worldwide Developers Conference in 2013. - [Wikipedia](https://en.wikipedia.org/wiki/IBeacon)

> iBeacon uses Bluetooth low energy proximity sensing to transmit a universally unique identifier picked up by a compatible app or operating system. The identifier can be used to determine the device's physical location, track customers, or trigger a location-based action on the device such as a check-in on social media or a push notification.

#### <img width="50" src="http://blog.thingstud.io/wp-content/uploads/mqttorg.png" /> - [MQTT](http://mqtt.org/) (IBM)

MQTT (formerly MQ Telemetry Transport) is a publish-subscribe based "light weight" messaging protocol for use on top of the TCP/IP protocol. It is designed for connections with remote locations where a "small code footprint" is required or the network bandwidth is limited. - [Wikipedia](https://en.wikipedia.org/wiki/MQTT)

> The publish-subscribe messaging pattern requires a message broker. The broker is responsible for distributing messages to interested clients based on the topic of a message. Andy Stanford-Clark and Arlen Nipper of Cirrus Link Solutions authored the first version of the protocol in 1999.

#### <img width="50" src="https://stomp.github.io/images/project-logo.png" /> - [STOMP](https://stomp.github.io/)

Simple (or Streaming) Text Oriented Message Protocol (STOMP), formerly known as TTMP, is a simple text-based protocol, designed for working with message-oriented middleware (MOM). - [Wikipedia](https://en.wikipedia.org/wiki/Streaming_Text_Oriented_Messaging_Protocol)

> STOMP provides an interoperable wire format that allows STOMP clients to talk with any message broker supporting the protocol. It is thus language-agnostic, meaning a broker developed for one programming language or platform can receive communications from client software developed in another language.

#### <img width="50" src="https://www.rabbitmq.com/wp-uploads/2012/02/HTML5_Logo_256.png" /> - [Websocket](https://en.wikipedia.org/wiki/WebSocket)

WebSocket is a protocol providing full-duplex communication channels over a single TCP connection. - [Wikipedia](https://en.wikipedia.org/wiki/WebSocket)

> WebSocket is designed to be implemented in web browsers and web servers, but it can be used by any client or server application. The WebSocket Protocol is an independent TCP-based protocol. The WebSocket protocol makes more interaction between a browser and a website possible, facilitating live content and the creation of real-time games. This is made possible by providing a standardized way for the server to send content to the browser without being solicited by the client, and allowing for messages to be passed back and forth while keeping the connection open.

#### <img width="50" src="https://upload.wikimedia.org/wikipedia/commons/9/95/XMPP_logo.svg" /> - [XMPP](https://en.wikipedia.org/wiki/XMPP) (IETF)

Extensible Messaging and Presence Protocol (XMPP) is a communications protocol for message-oriented middleware based on XML (Extensible Markup Language). - [Wikipedia](https://en.wikipedia.org/wiki/XMPP)

> It enables the near-real-time exchange of structured yet extensible data between any two or more network entities. Designed to be extensible, the protocol has also been used for publish-subscribe systems, signalling for VoIP, video, file transfer, gaming, Internet of Things (IoT) applications such as the smart grid, and social networking services.

## Technologies

> This sections regroups a curated list of awesome technologies that are closely related to the IoT world.

### <img width="50" src="http://vectorlogofree.com/wp-content/uploads/2012/12/nfc-logo-vector-400x400.png" /> - [NFC](https://en.wikipedia.org/wiki/Near_field_communication)

Near field communication (NFC) is the set of protocols that enable electronic devices to establish radio communication with each other by touching the devices together, or bringing them into proximity to a distance of typically 10cm or less. - [Wikipedia](https://en.wikipedia.org/wiki/Near_field_communication)

### <img width="50" src="https://opcfoundation.org/wp-content/themes/opc/images/logo.jpg"/>- [OPCUA](https://en.wikipedia.org/wiki/OPC_Unified_Architecture)
OPC-UA is a not only a protocol for industrial automation but also a technology that allows semantic description and object modelling of industrial environment.
[Wikipedia](https://en.wikipedia.org/wiki/OPC_Unified_Architecture)


## Standards and Alliances

### Standards

- [ETSI M2M](http://www.etsi.org/technologies-clusters/technologies/m2m) - The ETSI Technical Committee is developing standards for Machine to Machine Communications.
- [OneM2M](http://www.onem2m.org/) - The purpose and goal of oneM2M is to develop technical specifications which address the need for a common M2M Service Layer that can be readily embedded within various hardware and software, and relied upon to connect the myriad of devices in the field with M2M application servers worldwide.
- [OPCUA](https://opcfoundation.org/) - OPC Unified Architecture (OPC UA) is an industrial M2M communication protocol for interoperability developed by the OPC Foundation.
- [OCF](https://openconnectivity.org/) - OCF, The Open Connectivity Foundation, develop standards and certification for devices involved in the Internet of Things (IoT) based around Constrained Application Protocol (CoAP).

### Alliances

- [AIOTI](http://www.meet-iot.eu/Alliance-for-Internet-of-Things-Innovation-AIOTI.html) - The Internet of Things Innovation (AIOTI) aims to strengthen links and build new relationships between the different IoT players (industries, SMEs, startups) and sectors.
- [AllSeen Alliance](https://allseenalliance.org/) - The AllSeen Alliance is a nonprofit consortium dedicated to enabling and driving the widespread adoption of products, systems and services that support the Internet of Everything with an open, universal development framework supported by a vibrant ecosystem and thriving technical community.
- [Bluetooth Special Interest Group](https://www.bluetooth.com/) - The Bluetooth Special Interest Group (SIG) is the body that oversees the development of Bluetooth standards and the licensing of the Bluetooth technologies and trademarks to manufacturers.
- [IPSO Alliance](http://www.ipso-alliance.org/) - The IPSO Alliance provides a foundation for industry growth by fostering awareness, providing education, promoting the industry, generating research, and creating a better understanding of IP and its role in the Internet of Things.
- [LoRa Alliance](https://www.lora-alliance.org/) - The LoRa Alliance is an open, non-profit association of members that believes the internet of things era is now. It was initiated by industry leaders with a mission to standardize Low Power Wide Area Networks (LPWAN) being deployed around the world to enable Internet of Things (IoT), machine-to-machine (M2M), and smart city, and industrial applications.
- [OPC Foundation](https://opcfoundation.org/about/opc-foundation/mission-statement/) - The mission of the OPC Foundation is to manage a global organization in which users, vendors and consortia collaborate to create data transfer standards for multi-vendor, multi-platform, secure and reliable interoperability in industrial automation. To support this mission, the OPC Foundation
creates and maintains specifications, ensures compliance with OPC specifications via certification testing and collaborates with industry-leading standards organizations.
- [Thread Group](http://threadgroup.org/) - The Thread Group, composed of members from Nest, Samsung, ARM, Freescale, Silicon Labs, Big Ass Fans and Yale, drives the development of the Thread network protocol.
- [Wi-Fi Alliance](https://www.wi-fi.org/) - Wi-Fi Alliance® is a worldwide network of companies composed of several companies forming a global non-profit association with the goal of driving the best user experience with a new wireless networking technology – regardless of brand.
- [Zigbee Alliance](http://www.zigbee.org/) - The ZigBee Alliance is an open, non-profit association of approximately 450 members driving development of innovative, reliable and easy-to-use ZigBee standards.
- [Z-Wave Alliance](http://z-wavealliance.org/) - Established in 2005, the Z-Wave Alliance is comprised of industry leaders throughout the globe that are dedicated to the development and extension of Z-Wave as the key enabling technology for 'smart' home and business applications.

## Resources

### Books

#### [Building the Web of Things: with examples in Node.js and Raspberry Pi](http://book.webofthings.io) (2016) *by [Dominique Guinard](http://amazon.com/author/domguinard) and Vlad Trifa* [5.0] 

> A hands-on guide that will teach how to design and implement scalable, flexible, and open IoT solutions using web technologies. This book focuses on providing the right balance of theory, code samples, and practical examples to enable you to successfully connect all sorts of devices to the web and to expose their services and data over REST APIs. The book covers a number of web technologies for your IoT toolbox: GPIO, Raspberry Pi, Embedded Systems, REST and HTTP, WS, MQTT, CoAP, JSON-LD, Social Networks, Node-RED, IFTTT, etc.

#### [Abusing the Internet of Things: Blackouts, Freakouts, and Stakeouts](http://www.amazon.com/Abusing-Internet-Things-Blackouts-Freakouts/dp/1491902337) (2015) *by [Nitesh Dhanjani](http://www.amazon.com/Nitesh-Dhanjani/e/B001KDWB6W/ref=dp_byline_cont_book_1)* [5.0]

>  future with billions of connected "things" includes monumental security concerns. This practical book explores how malicious attackers can abuse popular IoT-based devices, including wireless LED lightbulbs, electronic door locks, baby monitors, smart TVs, and connected cars.

#### [Using the Web to Build the IoT](https://manning.com/books/using-the-web-to-build-the-iot) (2016) *by [Dominique Guinard](http://amazon.com/author/domguinard)
and Vlad Trifa
> Using the Web to Build the IoT is a free book built as a collection of six hand-picked chapters that introduce the key technologies and concepts for building the application layer of the IoT. Dom Guinard and Vlad Trifa, selected these specific topics to give you an overview of the Web of Things architecture, along with techniques for data ingestion, searching, security, and visualization.


#### [Building Wireless Sensor Networks: with ZigBee, XBee, Arduino, and Processing](http://www.amazon.com/Building-Wireless-Sensor-Networks-Processing/dp/0596807732) (2011) *by [Robert Faludi](http://www.amazon.com/Robert-Faludi/e/B004JKWA3C/ref=dp_byline_cont_book_1)* [4.5]

> Get ready to create distributed sensor systems and intelligent interactive devices using the ZigBee wireless networking protocol and Series 2 XBee radios. By the time you're halfway through this fast-paced, hands-on guide, you'll have built a series of useful projects, including a complete ZigBee wireless network that delivers remotely sensed data.

#### [Designing the Internet of Things](http://www.amazon.co.uk/Designing-Internet-Things-Adrian-McEwen/dp/111843062X/ref=sr_1_1?ie=UTF8&qid=1444905007&sr=8-1) (2013) *by [Adrian McEwen](http://www.amazon.co.uk/Adrian-McEwen/e/B00FF7V2VY/ref=dp_byline_cont_book_1) and [Hakim Cassimally](http://www.amazon.co.uk/Hakim-Cassimally/e/B00FF5I3Y0/ref=ntt_athr_dp_pel_2/277-3946068-7961614)* [4.0]

> Whether it's called physical computing, ubiquitous computing, or the Internet of Things, it's a hot topic in technology: how to channel your inner Steve Jobs and successfully combine hardware, embedded software, web services, electronics, and cool design to create cutting-edge devices that are fun, interactive, and practical. If you'd like to create the next must-have product, this unique book is the perfect place to start.

#### [Getting Started with Bluetooth Low Energy: Tools and Techniques for Low-Power Networking](http://www.amazon.com/Getting-Started-Bluetooth-Low-Energy/dp/1491949511) (2014) *by [Kevin Townsend](http://www.amazon.com/Getting-Started-Bluetooth-Low-Energy/dp/1491949511#productDescription), [Carles Cufí](http://www.amazon.com/Getting-Started-Bluetooth-Low-Energy/dp/1491949511#productDescription), [Akiba](http://www.amazon.com/Getting-Started-Bluetooth-Low-Energy/dp/1491949511#productDescription) and [Robert Davidson](http://www.amazon.com/Getting-Started-Bluetooth-Low-Energy/dp/1491949511#productDescription)* [4.5]

> This book provides a solid, high-level overview of how devices use Ble to communicate with each other. You'll learn useful low-cost tools for developing and testing Ble-enabled mobile apps and embedded firmware and get examples using various development platforms including iOs and Android for app developers and embedded platforms for product designers and hardware engineers.

#### [Smart Things: Ubiquitous Computing User Experience Design](http://www.amazon.com/Smart-Things-Ubiquitous-Computing-Experience/dp/0123748992) (2010) *by [Mike Kuniavsky](http://www.amazon.com/Mike-Kuniavsky/e/B001K8LTGU/ref=dp_byline_cont_book_1)* [4.5]

> Smart Things presents a problem-solving approach to addressing designers' needs and concentrates on process, rather than technological detail, to keep from being quickly outdated. It pays close attention to the capabilities and limitations of the medium in question and discusses the tradeoffs and challenges of design in a commercial environment.

#### [JavaScript on Things: Hardware for Web Developers](https://www.manning.com/books/javascript-on-things) (2018 - est.) *by [Lyza Danger Gardner](https://www.amazon.com/s/ref=dp_byline_sr_book_1?ie=UTF8&text=Lyza+Danger+Gardner&search-alias=books&field-author=Lyza+Danger+Gardner&sort=relevancerank)* [early access book]

> JavaScript on Things is your first step into the exciting and downright entertaining world of programming for small electronics. If you know enough JavaScript to hack a website together, you'll be making things bleep, blink and spin faster than you can say "nodebot". This fully-illustrated, hands-on book shows you how to get going with platforms like Arduino, Tessel, and Raspberry Pi. 

### Articles

- [A Simple Explanation Of 'The Internet Of Things' (Forbes)](http://www.forbes.com/sites/jacobmorgan/2014/05/13/simple-explanation-internet-things-that-anyone-can-understand/) - This article attemps to give an answer to what exactly is the “Internet of things” and what impact it is going to have on us.
- [IoT security. Is there an app for that ?](http://embedded-computing.com/21517-iot-security-is-there-an-app-for-that/) - The Internet of Things World conference investigates IoT application development, security, and business models.
- [The IoT Testing Atlas](http://iamqa.in/2015/10/04/The-IoT-Testing-Atlas/) - A testing methodology for managing the permutations of parameters while testing an IoT based product.


### Papers

- [A Reference Architecture for the Internet of Things](http://wso2.com/wso2_resources/wso2_whitepaper_a-reference-architecture-for-the-internet-of-things.pdf) - This white paper introduces a Reference Architecture for the Internet of Things (IoT): this includes the devices as well as the server-side and cloud architecture required to interact with and manage the devices.
- [Developing solutions for the Internet of Things](https://www-ssl.intel.com/content/dam/www/public/us/en/documents/white-papers/developing-solutions-for-iot.pdf) - Intel's vision in enabling secure and seamless solutions for the Internet of Things (IoT).
- [Evaluation of indoor positioning based on Bluetooth Smart technology](http://publications.lib.chalmers.se/records/fulltext/199826/199826.pdf) - Master of Science Thesis in the Programme Computer Systems and Networks.
- [IoT: A Vision, Architectural Elements, and Future Directions](http://arxiv.org/pdf/1207.0203.pdf) - This paper presents a cloud centric vision for worldwide implementation of Internet of Things. The key enabling technologies and application domains that are likely to drive IoT research in the near future are discussed.
- [Realizing the Potential of the Internet of Things](https://www.tiaonline.org/sites/default/files/pages/TIA-White-Paper-Realizing_the_Potential_of_the_Internet_of_Things.pdf) - A white paper from the Telecommunications Industry Association (TIA) written in the form of a set of recommendations to policy maker on leveraging and realizing the potential of the Internet of Things market.
- [The Internet of Things: Evolution or Revolution ?](http://www.aig.com/Chartis/internet/US/en/AIG%20White%20Paper%20-%20IoT%20English%20DIGITAL_tcm3171-677828_tcm3171-698578.pdf) - This white paper compares the current Internet of Things market rise to other industrial revolutions, the challenges it introduces, as well as its consequences on our daily lives.


## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Halim Qarroum](https://github.com/HQarroum/) has waived all copyright and related or neighboring rights to this work.
