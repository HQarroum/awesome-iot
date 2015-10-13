# Awesome IoT [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<img src="iot-logo.png" align="right" width="100">

> A curated list of awesome Internet of Things projects and resources.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.

## Table of Contents

- [Hardware](#hardware)
- [Software](#software)
  - [Operating systems](#operating-systems)
  - [Programming Languages](#programming-languages)
  - [Frameworks](#frameworks)
  - [Middlewares](#middlewares)
  - [Libraries & Tools](#libraries-and-tools)
  - [Miscellaneous](#miscellaneous)
- [Protocols and Networks](#protocols-and-networks)
- [Technologies](#technologies)
- [Standards & Alliances](#standard-and-alliances)
- [Resources](#resources)
  - [Books](#books)
  - [Articles](#articles)
  - [Papers](#papers)
- [Existing projects](#existing-projects)
  - [Open Source](#open-source)
  - [Closed Source](#closed-source)

### Hardware

- [Arduino](https://www.arduino.cc/) - Arduino is an open-source electronics platform based on easy-to-use hardware and software. It's intended for anyone making interactive projects.
- [BeagleBoard](http://beagleboard.org/) - The BeagleBoard is a low-power open-source hardware single-board computer produced by Texas Instruments in association with Digi-Key and Newark element14.
- [Intel Galileo](https://www-ssl.intel.com/content/www/us/en/do-it-yourself/galileo-maker-quark-board.html) - The Intel® Galileo Gen 2 board is the first in a family of Arduino*-certified development and prototyping boards based on Intel® architecture and specifically designed for makers, students, educators, and DIY electronics enthusiasts.
- [Microduino](https://www.microduino.cc/) - Microduino and mCookie bring powerful, small, stackable electronic hardware to makers, designers, engineers, students and curious tinkerers of all ages. Build open-source projects or create innovative new ones.
- [Node MCU (ESP 8266)](http://nodemcu.com/index_en.html) - NodeMCU is an open source IoT platform. It uses the Lua scripting language. It is based on the eLua project, and built on the ESP8266 SDK 0.9.5.
- [Particle](https://www.particle.io) - A suite of hardware and software tools to help you prototype, scale, and manage your Internet of Things products.
- [Pinoccio](https://pinocc.io/) - Pinoccio is a pocket-sized, wireless sensor and microcontroller board that combines the features of an Arduino Mega board with a ZigBee compatible 2.4GHz radio.
- [Raspberry Pi](https://www.raspberrypi.org/) - The Raspberry Pi is a low cost, credit-card sized computer that plugs into a computer monitor or TV, and uses a standard keyboard and mouse. It’s capable of doing everything you’d expect a desktop computer to do, from browsing the internet and playing high-definition video, to making spreadsheets, word-processing, and playing games.
- [Tessel](https://tessel.io/) - Tessel is a completely open source and community-driven IoT and robotics development platform. It encompases development boards, hardware module add-ons, and the software that runs on them.

### Software

#### Operating systems

 - [ARM mbed](http://www.mbed.com/) - The ARM® mbed™ IoT Device Platform provides the operating system, cloud services, tools and developer ecosystem to make the creation and deployment of commercial, standards-based IoT solutions possible at scale.
 - [Contiki](http://www.contiki-os.org/) - Contiki is an open source operating system for the Internet of Things. Contiki connects tiny low-cost, low-power microcontrollers to the Internet.
 - [FreeRTOS](http://www.freertos.org/) - FreeRTOS is a popular real-time operating system kernel for embedded devices, that has been ported to 35 microcontrollers.
 - [Google Brillo](https://developers.google.com/brillo/) - Brillo extends the Android platform to all your connected devices, so they are easy to set up and work seamlessly with each other and your smartphone.
 - [OpenWrt](https://openwrt.org/) - OpenWrt is an operating system (in particular, an embedded operating system) based on the Linux kernel, primarily used on embedded devices to route network traffic. The main components are the Linux kernel, util-linux, uClibc or musl, and BusyBox. All components have been optimized for size, to be small enough for fitting into the limited storage and memory available in home routers.
 - [Raspbian](https://raspbian.org/) - Raspbian is a free operating system based on Debian optimized for the Raspberry Pi hardware.
 - [RIOT](http://www.riot-os.org/) - The friendly Operating System for the Internet of Things.
 - [Tiny OS](http://www.tinyos.net/) - TinyOS is an open source, BSD-licensed operating system designed for low-power wireless devices, such as those used in sensor networks, ubiquitous computing, personal area networks, smart buildings, and smart meters.

#### Programming languages

> This sections regroups every awesome programming language, whether it is compiled, interpreted or a DSL, related to embedded development.

 - [C](https://en.wikipedia.org/wiki/C_(programming_language)) - A general-purpose, imperative computer programming language, supporting structured programming, lexical variable scope and recursion, while a static type system prevents many unintended operations.
 - [C++](https://en.wikipedia.org/wiki/C%2B%2B) - A general-purpose programming language. It has imperative, object-oriented and generic programming features, while also providing facilities for low-level memory manipulation.
 - [Groovy](http://www.groovy-lang.org/) - Groovy is a powerful, optionally typed and dynamic language, with static-typing and static compilation capabilities, for the Java platform aimed at multiplying developers’ productivity thanks to a concise, familiar and easy to learn syntax. It is used by the SmartThings development environment to create smart applications.
 - [Lua](http://www.lua.org/) - Lua is a powerful, fast, lightweight, embeddable scripting language. Lua is dynamically typed, runs by interpreting bytecode for a register-based virtual machine, and has automatic memory management with incremental garbage collection, making it ideal for configuration, scripting, and rapid prototyping.
 - [eLua](http://www.eluaproject.net/) - eLua stands for Embedded Lua and the project offers the full implementation of the Lua Programming Language to the embedded world, extending it with specific features for efficient and portable software embedded development.
 - [ELIoT](https://c3d.github.io/eliot/) - ELIoT is a very simple and small programming language specifcally designed to facilitate the configuration and control of swarms of small devices such as sensors or actuators.

#### Frameworks

 - [Eclipse Smarthome](https://eclipse.org/smarthome/) - The Eclipse SmartHome framework is designed to run on embedded devices, such as a Raspberry Pi, a BeagleBone Black or an Intel Edison. It requires a Java 7 compliant JVM and an OSGi (4.2+) framework, such as Eclipse Equinox.
 - [Iotivity](https://www.iotivity.org/) - IoTivity is an open source software framework enabling seamless device-to-device connectivity to address the emerging needs of the Internet of Things.
 - [Kura](https://eclipse.org/kura/) - Kura aims at offering a Java/OSGi-based container for M2M applications running in service gateways. Kura provides or, when available, aggregates open source implementations for the most common services needed by M2M applications.
 - [Mihini](https://wiki.eclipse.org/Mihini) - The main goal of Mihini is to deliver an embedded runtime running on top of Linux, that exposes high-level API for building M2M applications. Mihini aims at enabling easy and portable development, by facilitating access to the I/Os of an M2M system, providing a communication layer, etc.
 - [OpenHAB](http://www.openhab.org/) - The openHAB runtime is a set of OSGi bundles deployed on an OSGi framework (Equinox). It is therefore a pure Java solution and needs a JVM to run. Being based on OSGi, it provides a highly modular architecture, which even allows adding and removing functionality during runtime without stopping the service.
 - [Gobot](http://gobot.io/) - Gobot is a framework for robotics, physical computing, and the Internet of Things, written in the Go programming language.

#### Middlewares

 - [Kaa](http://www.kaaproject.org/) - An open-source middleware platform for rapid creation of IoT solutions.

#### Libraries & Tools

 - [Cylon.js](http://cylonjs.com/) - Cylon.js is a JavaScript framework for robotics, physical computing, and the Internet of Things. It makes it incredibly easy to command robots and devices.
 - [Luvit](https://luvit.io/) - Luvit implements the same APIs as Node.js, but in Lua ! While this framework is not directly involved with IoT development, it is still a *great* way to rapidly build powertfull, yet memory efficient, embedded web applications.
 - [Johnny-Five](http://johnny-five.io/) - Johnny-Five is the original JavaScript Robotics programming framework. Released by Bocoup in 2012, Johnny-Five is maintained by a community of passionate software developers and hardware engineers.
 - [WiringPi](http://wiringpi.com/) - WiringPi is a GPIO access library written in C for the BCM2835 used in the Raspberry Pi.

#### Miscellaneous

 - [IFTTT](https://ifttt.com/) - IFTTT is a web-based service that allows users to create chains of simple conditional statements, called "recipes", which are triggered based on changes to other web services such as Gmail, Facebook, Instagram, and Pinterest. IFTTT is an abbreviation of "If This Then That" (pronounced like "gift" without the "g").

## Protocols and Networks

### Physical layer

#### <img width="50" src="http://www.greenpeak.com/images/IEEE802154.jpg" /> - [802.15.4](https://en.wikipedia.org/wiki/IEEE_802.15.4) (IEEE)

IEEE 802.15.4 is a standard which specifies the physical layer and media access control for low-rate wireless personal area networks (LR-WPANs). It is maintained by the IEEE 802.15 working group, which has defined it in 2003. It is the basis for the ZigBee, ISA100.11a, WirelessHART, and MiWi specifications, each of which further extends the standard by developing the upper layers which are not defined in IEEE 802.15.4. Alternatively, it can be used with 6LoWPAN and standard Internet protocols to build a wireless embedded Internet. - [Wikipedia](https://en.wikipedia.org/wiki/IEEE_802.15.4)

> IEEE standard 802.15.4 intends to offer the fundamental lower network layers of a type of wireless personal area network (WPAN) which focuses on low-cost, low-speed ubiquitous communication between devices. It can be contrasted with other approaches, such as Wi-Fi, which offer more bandwidth and require more power. The emphasis is on very low cost communication of nearby devices with little to no underlying infrastructure, intending to exploit this to lower power consumption even more.

#### <img width="50" src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fc/BluetoothLogo.svg/770px-BluetoothLogo.svg.png" /> - [Bluetooth](https://en.wikipedia.org/wiki/Bluetooth) (Bluetooth Special Interest Group)

Bluetooth is a wireless technology standard for exchanging data over short distances (using short-wavelength UHF radio waves in the ISM band from 2.4 to 2.485 GHz) from fixed and mobile devices, and building personal area networks (PANs). Invented by telecom vendor Ericsson in 1994, it was originally conceived as a wireless alternative to RS-232 data cables. It can connect several devices, overcoming problems of synchronization. - [Wikipedia](https://en.wikipedia.org/wiki/Bluetooth)

> Bluetooth is managed by the Bluetooth Special Interest Group (SIG), which has more than 25,000 member companies in the areas of telecommunication, computing, networking, and consumer electronics.

#### <img width="50" src="https://upload.wikimedia.org/wikipedia/en/thumb/2/20/Bluetooth_Smart_Logo.svg/288px-Bluetooth_Smart_Logo.svg.png" /> - [Bluetooth Low Energy](https://en.wikipedia.org/wiki/Bluetooth_low_energy) (Bluetooth Special Interest Group)

Bluetooth low energy (Bluetooth LE, BLE, marketed as Bluetooth Smart) is a wireless personal area network technology designed and marketed by the Bluetooth Special Interest Group aimed at novel applications in the healthcare, fitness, beacons, security, and home entertainment industries. - [Wikipedia](https://en.wikipedia.org/wiki/Bluetooth_low_energy)

> Compared to Classic Bluetooth, Bluetooth Smart is intended to provide considerably reduced power consumption and cost while maintaining a similar communication range. The Bluetooth SIG predicts that by 2018 more than 90 percent of Bluetooth-enabled smartphones will support Bluetooth Smart.

#### <img width="50" src="http://www.taktilis.fr/wp-content/uploads/Lora.jpg" /> - [LoRaWAN](https://en.wikipedia.org/wiki/LoRaWAN) (LoRa Alliance)

A LoRaWAN wide area network allows low bit rate communication from and to connected objects, thus participating to Internet of Things, machine-to-machine M2M, and smart city. - [Wikipedia](https://en.wikipedia.org/wiki/LoRaWAN)

> This technology is standardized by the LoRa Alliance. It was initially developed by Cycleo, which was acquired by Semtech in 2012. LoRaWAN is an acronym for Long Range Wide-area network.

#### <img width="50" src="http://www.silvereco.fr/wp-content/uploads/2015/02/logo510f703a4647f1.jpg" /> - [Sigfox](https://en.wikipedia.org/wiki/Sigfox) (Sigfox)

Sigfox is a French firm that builds wireless networks to connect low-energy objects such as electricity meters, smart watches, and washing machines, which need to be continuously on and emitting small amounts of data. Its infrastructure is intended to be a contribution to what is known as the Internet of Things (IoT). - [Wikipedia](https://en.wikipedia.org/wiki/Sigfox)

> SIGFOX describes itself as "the first and only company providing global cellular connectivity for the Internet of Things." Its infrastructure is "completely independent of existing networks, such as telecommunications networks." SIGFOX seeks to provide the means for the "deployment of billions of objects and thousands of new uses" with the long-term goal of "having petabytes of data produced by everyday objects".

#### <img width="50" src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fe/Wi-Fi_Alliance_Logo.svg/648px-Wi-Fi_Alliance_Logo.svg.png" /> - [Wi-Fi](https://en.wikipedia.org/wiki/Wi-Fi) (Wi-Fi Alliance)

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

#### <img width="50" src="http://www.httptechnology.com.au/logo.jpg" /> - [HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol) (IETF)

The Hypertext Transfer Protocol (HTTP) is an application protocol for distributed, collaborative, hypermedia information systems. HTTP is the foundation of data communication for the World Wide Web. - [Wikipedia](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)

> The standards development of HTTP was coordinated by the Internet Engineering Task Force (IETF) and the World Wide Web Consortium (W3C), culminating in the publication of a series of Requests for Comments (RFCs). The first definition of HTTP/1.1, the version of HTTP in common use, occurred in RFC 2068 in 1997, although this was obsoleted by RFC 2616 in 1999.

#### <img width="50" src="http://blog.thingstud.io/wp-content/uploads/mqttorg.png" /> - [MQTT](http://mqtt.org/) (IBM)

MQTT (formerly MQ Telemetry Transport) is a publish-subscribe based "light weight" messaging protocol for use on top of the TCP/IP protocol. It is designed for connections with remote locations where a "small code footprint" is required or the network bandwidth is limited. - [Wikipedia](https://en.wikipedia.org/wiki/MQTT)

> The publish-subscribe messaging pattern requires a message broker. The broker is responsible for distributing messages to interested clients based on the topic of a message. Andy Stanford-Clark and Arlen Nipper of Cirrus Link Solutions authored the first version of the protocol in 1999.

#### <img width="50" src="https://stomp.github.io/images/project-logo.png" /> - [STOMP](https://stomp.github.io/)

Simple (or Streaming) Text Oriented Message Protocol (STOMP), formerly known as TTMP, is a simple text-based protocol, designed for working with message-oriented middleware (MOM). - [Wikipedia](https://en.wikipedia.org/wiki/Streaming_Text_Oriented_Messaging_Protocol)

> STOMP provides an interoperable wire format that allows STOMP clients to talk with any message broker supporting the protocol. It is thus language-agnostic, meaning a broker developed for one programming language or platform can receive communications from client software developed in another language.

#### <img width="50" src="https://www.rabbitmq.com/wp-uploads/2012/02/HTML5_Logo_256.png" /> - [Websocket](https://en.wikipedia.org/wiki/WebSocket)

WebSocket is a protocol providing full-duplex communication channels over a single TCP connection. - [Wikipedia](https://en.wikipedia.org/wiki/WebSocket)

> WebSocket is designed to be implemented in web browsers and web servers, but it can be used by any client or server application. The WebSocket Protocol is an independent TCP-based protocol. The WebSocket protocol makes more interaction between a browser and a website possible, facilitating live content and the creation of real-time games. This is made possible by providing a standardized way for the server to send content to the browser without being solicited by the client, and allowing for messages to be passed back and forth while keeping the connection open

## Technologies

### <img width="50" src="http://vectorlogofree.com/wp-content/uploads/2012/12/nfc-logo-vector-400x400.png" /> - [NFC](https://en.wikipedia.org/wiki/Near_field_communication)

Near field communication (NFC) is the set of protocols that enable electronic devices to establish radio communication with each other by touching the devices together, or bringing them into proximity to a distance of typically 10cm or less. - [Wikipedia](https://en.wikipedia.org/wiki/Near_field_communication)

## Standards & Alliances

- [AllSeen Alliance](https://allseenalliance.org/) - The AllSeen Alliance is a nonprofit consortium dedicated to enabling and driving the widespread adoption of products, systems and services that support the Internet of Everything with an open, universal development framework supported by a vibrant ecosystem and thriving technical community.
- [Bluetooth Special Interest Group](https://www.bluetooth.org/) - The Bluetooth Special Interest Group (SIG) is the body that oversees the development of Bluetooth standards and the licensing of the Bluetooth technologies and trademarks to manufacturers. The SIG is a not-for-profit, non-stock corporation founded in September 1998. The SIG is headquartered in Kirkland, Washington.
- [IPSO Alliance](http://www.ipso-alliance.org/) - Since 2008, the IPSO Alliance has served as a resource center and thought leader seeking to establish the Internet Protocol as the basis for the connection of Smart Objects. The IPSO Alliance provides a foundation for industry growth by fostering awareness, providing education, promoting the industry, generating research, and creating a better understanding of IP and its role in the Internet of Things.
- [LoRa Alliance](https://www.lora-alliance.org/) - The LoRa Alliance is an open, non-profit association of members that believes the internet of things era is now. It was initiated by industry leaders with a mission to standardize Low Power Wide Area Networks (LPWAN) being deployed around the world to enable Internet of Things (IoT), machine-to-machine (M2M), and smart city, and industrial applications. The Alliance members will collaborate to drive the global success of the LoRa protocol (LoRaWAN), by sharing knowledge and experience to guarantee interoperability between operators in one open global standard.
- [Open Interconnect Consortium](http://openinterconnect.org/) - The Open Interconnect Consortium (OIC) is an industry group whose stated mission is to develop standards and certification for devices involved in the Internet of Things (IoT) based around CoAP. OIC was created in July 2014 by Intel, Broadcom, and Samsung Electronics.
- [Thread Group](http://threadgroup.org/) - The Thread Group, composed of members from Nest, Samsung, ARM, Freescale, Silicon Labs, Big Ass Fans and Yale, drives the development of the Thread network protocol.
- [Wi-Fi Alliance](https://www.wi-fi.org/) - Wi-Fi Alliance® is a worldwide network of companies composed of several companies forming a global non-profit association with the goal of driving the best user experience with a new wireless networking technology – regardless of brand.
- [Zigbee Alliance](http://www.zigbee.org/) - The ZigBee Alliance is an open, non-profit association of approximately 450 members driving development of innovative, reliable and easy-to-use ZigBee standards. The Alliance promotes worldwide adoption of ZigBee as the leading wirelessly networked, sensing and control standard for use in consumer, commercial and industrial areas.
- [Z-Wave Alliance](http://z-wavealliance.org/) - Established in 2005, the Z-Wave Alliance is comprised of industry leaders throughout the globe that are dedicated to the development and extension of Z-Wave as the key enabling technology for 'smart' home and business applications.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Halim Qarroum](https://github.com/HQarroum/) has waived all copyright and related or neighboring rights to this work.
