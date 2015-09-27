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
  - [Libraries & Tools](#libraries-and-tools)
  - [Miscellaneous](#miscellaneous)
- [Protocols and Networks](#protocols-and-alliances)
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

- [Arduino](https://www.arduino.cc/) - Arduino is an open-source electronics platform based on easy-to-use hardware and software. It's intended for anyone making interactive projects. Arduino senses the environment by receiving inputs from many sensors, and affects its surroundings by controlling lights, motors, and other actuators.
- [BeagleBoard](http://beagleboard.org/) - The BeagleBoard is a low-power open-source hardware single-board computer produced by Texas Instruments in association with Digi-Key and Newark element14. The BeagleBoard was also designed with open source software development in mind, and as a way of demonstrating the Texas Instrument's OMAP3530 system-on-a-chip.
- [Intel Galileo](https://www-ssl.intel.com/content/www/us/en/do-it-yourself/galileo-maker-quark-board.html) - The Intel® Galileo Gen 2 board is the first in a family of Arduino*-certified development and prototyping boards based on Intel® architecture and specifically designed for makers, students, educators, and DIY electronics enthusiasts.
- [Microduino](https://www.microduino.cc/) - Microduino and mCookie bring powerful, small, stackable electronic hardware to makers, designers, engineers, students and curious tinkerers of all ages. Build open-source projects or create innovative new ones.
- [Node MCU (ESP 8266)](http://nodemcu.com/index_en.html) - NodeMCU is an open source IoT platform. It uses the Lua scripting language. It is based on the eLua project, and built on the ESP8266 SDK 0.9.5. It uses many open source projects, such as lua-cjson, and spiffs. It includes firmware which runs on the ESP8266 Wi-Fi SoC, and hardware which is based on the ESP-12 module.
- [Particle](https://www.particle.io) - A suite of hardware and software tools to help you
prototype, scale, and manage your Internet of Things products.
- [Pinoccio](https://pinocc.io/) - Pinoccio is a pocket-sized, wireless sensor and microcontroller board that combines the features of an Arduino Mega board with a ZigBee compatible 2.4GHz radio. It also includes components for IoT application development, such as an RGB LED and a micro-SD card slot.
- [Raspberry Pi](https://www.raspberrypi.org/) - The Raspberry Pi is a low cost, credit-card sized computer that plugs into a computer monitor or TV, and uses a standard keyboard and mouse. It’s capable of doing everything you’d expect a desktop computer to do, from browsing the internet and playing high-definition video, to making spreadsheets, word-processing, and playing games.
- [Tessel](https://tessel.io/) - Tessel is a completely open source and community-driven IoT and robotics development platform. It encompases development boards, hardware module add-ons, and the software that runs on them. Tessel is about designing intuitive and accessible hardware development experiences around the open web.

### Software

#### Operating systems

 - [ARM mbed](http://www.mbed.com/) - The ARM® mbed™ IoT Device Platform provides the operating system, cloud services, tools and developer ecosystem to make the creation and deployment of commercial, standards-based IoT solutions possible at scale.
 - [Contiki](http://www.contiki-os.org/) - Contiki is an open source operating system for the Internet of Things. Contiki connects tiny low-cost, low-power microcontrollers to the Internet.
 - [FreeRTOS](http://www.freertos.org/) - FreeRTOS is a popular real-time operating system kernel for embedded devices, that has been ported to 35 microcontrollers.
 - [Google Brillo](https://developers.google.com/brillo/) - Brillo extends the Android platform to all your connected devices, so they are easy to set up and work seamlessly with each other and your smartphone.
 - [Raspbian](https://raspbian.org/) - Raspbian is a free operating system based on Debian optimized for the Raspberry Pi hardware.
 - [RIOT](http://www.riot-os.org/) - The friendly Operating System for the Internet of Things.
 - [Tiny OS](http://www.tinyos.net/) - TinyOS is an open source, BSD-licensed operating system designed for low-power wireless devices, such as those used in sensor networks, ubiquitous computing, personal area networks, smart buildings, and smart meters.

#### Frameworks

 - [Eclipse Smarthome](https://eclipse.org/smarthome/) - The Eclipse SmartHome framework is designed to run on embedded devices, such as a Raspberry Pi, a BeagleBone Black or an Intel Edison. It requires a Java 7 compliant JVM and an OSGi (4.2+) framework, such as Eclipse Equinox.
 - [Iotivity](https://www.iotivity.org/) - IoTivity is an open source software framework enabling seamless device-to-device connectivity to address the emerging needs of the Internet of Things.
 - [Kura](https://eclipse.org/kura/) - Kura aims at offering a Java/OSGi-based container for M2M applications running in service gateways. Kura provides or, when available, aggregates open source implementations for the most common services needed by M2M applications. Kura components are designed as configurable OSGi Declarative Service exposing service API and raising events. While several Kura components are in pure Java, others are invoked through JNI and have a dependency on the Linux operating system.
 - [Mihini](https://wiki.eclipse.org/Mihini) - The main goal of Mihini is to deliver an embedded runtime running on top of Linux, that exposes high-level API for building M2M applications. Mihini aims at enabling easy and portable development, by facilitating access to the I/Os of an M2M system, providing a communication layer, etc.
 - [OpenHAB](http://www.openhab.org/) - The openHAB runtime is a set of OSGi bundles deployed on an OSGi framework (Equinox). It is therefore a pure Java solution and needs a JVM to run. Being based on OSGi, it provides a highly modular architecture, which even allows adding and removing functionality during runtime without stopping the service.

## Protocols and Networds

##### <img width="50" src="http://www.tonex.com/wp-content/uploads/6lowpan.jpg" /> - [6LowPan](https://en.wikipedia.org/wiki/6LoWPAN) (IETF)

6LoWPAN is an acronym of IPv6 over Low power Wireless Personal Area Networks. 6LoWPAN is the name of a concluded working group in the Internet area of the IETF. - [Wikipedia](https://en.wikipedia.org/wiki/6LoWPAN)

> The 6LoWPAN concept originated from the idea that "the Internet Protocol could and should be applied even to the smallest devices,"and that low-power devices with limited processing capabilities should be able to participate in the Internet of Things.
The 6LoWPAN group has defined encapsulation and header compression mechanisms that allow IPv6 packets to be sent and received over IEEE 802.15.4 based networks. IPv4 and IPv6 are the work horses for data delivery for local-area networks, metropolitan area networks, and wide-area networks such as the Internet. Likewise, IEEE 802.15.4 devices provide sensing communication-ability in the wireless domain. The inherent natures of the two networks though, are different.

##### <img width="50" src="http://www.taktilis.fr/wp-content/uploads/Lora.jpg" /> - [LoRaWAN](https://en.wikipedia.org/wiki/LoRaWAN) (LoRa Alliance)

A LoRaWAN wide area network allows low bit rate communication from and to connected objects, thus participating to Internet of Things, machine-to-machine M2M, and smart city. - [Wikipedia](https://en.wikipedia.org/wiki/LoRaWAN)

> This technology is standardized by the LoRa Alliance. It was initially developed by Cycleo, which was acquired by Semtech in 2012. LoRaWAN is an acronym for Long Range Wide-area network.

##### <img width="50" src="http://www.silvereco.fr/wp-content/uploads/2015/02/logo510f703a4647f1.jpg" /> - [Sigfox](https://en.wikipedia.org/wiki/Sigfox) (Sigfox)

Sigfox is a French firm that builds wireless networks to connect low-energy objects such as electricity meters, smart watches, and washing machines, which need to be continuously on and emitting small amounts of data. Its infrastructure is intended to be a contribution to what is known as the Internet of Things (IoT). - [Wikipedia](https://en.wikipedia.org/wiki/Sigfox)

> SIGFOX describes itself as "the first and only company providing global cellular connectivity for the Internet of Things." Its infrastructure is "completely independent of existing networks, such as telecommunications networks." SIGFOX seeks to provide the means for the "deployment of billions of objects and thousands of new uses" with the long-term goal of "having petabytes of data produced by everyday objects".


##### <img width="50" src="http://www.twice.com/sites/default/files/styles/blog_content/public/ThreadGroupLogo_4_3_0.jpg?itok=SmyKXf7r" /> - [Thread](http://threadgroup.org/) (Thread Group)

Thread is an IPv6 based protocol for "smart" household devices to communicate on a network.

> In July 2014 Google Inc's Nest Labs announced a working group with the companies Samsung, ARM Holdings, Freescale, Silicon Labs, Big Ass Fans and the lock company Yale in an attempt to have Thread become the industry standard by providing Thread certification for products. Other protocols currently in use include ZigBee and Bluetooth Smart.
Thread uses 6LoWPAN, which in turn uses the IEEE 802.15.4 wireless protocol with mesh communication, as does ZigBee and other systems. Thread however is IP-addressable, with cloud access and AES encryption. It supports over 250 devices on a network.

##### <img width="50" src="http://www.zenatik.com/img/cms/zigbee.png" /> - [ZigBee](https://en.wikipedia.org/wiki/ZigBee) (ZigBee Alliance)

ZigBee is a IEEE 802.15.4-based specification for a suite of high-level communication protocols used to create personal area networks with small, low-power digital radios. - [Wikipedia](https://en.wikipedia.org/wiki/ZigBee)

> The technology defined by the ZigBee specification is intended to be simpler and less expensive than other wireless personal area networks (WPANs), such as Bluetooth or Wi-Fi. Applications include wireless light switches, electrical meters with in-home-displays, traffic management systems, and other consumer and industrial equipment that requires short-range low-rate wireless data transfer.

##### <img width="50" src="https://upload.wikimedia.org/wikipedia/commons/0/08/Z-Wave_logo.jpg" /> - [Z-Wave](http://www.z-wave.com/) (Z-Wave Alliance)

Z-Wave is a wireless communications specification designed to allow devices in the home (lighting, access controls, entertainment systems and household appliances, for example) to communicate with one another for the purposes of home automation. - [Wikipedia](https://en.wikipedia.org/wiki/Z-Wave)

> Z-Wave technology minimizes power consumption so that it is suitable for battery-operated devices. Z-Wave is designed to provide, reliable, low-latency transmission of small data packets at data rates up to 100kbit/s, unlike Wi-Fi and other IEEE 802.11-based wireless LAN systems that are designed primarily for high data rates. Z-Wave operates in the sub-gigahertz frequency range, around 900 MHz. This band competes with some cordless telephones and other consumer electronics devices, but avoids interference with Wi-Fi, Bluetooth and other systems that operate on the crowded 2.4 GHz band. Z-Wave is designed to be easily embedded in consumer electronics products, including battery operated devices such as remote controls, smoke alarms and security sensors. Z-Wave was developed by a Danish startup called Zen-Sys that was acquired by Sigma Designs in 2008.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Halim Qarroum](https://github.com/HQarroum/) has waived all copyright and related or neighboring rights to this work.
