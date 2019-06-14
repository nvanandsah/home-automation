## Welcome to GitHub Pages
#**Introduction:-**
This is IoT based home automation project is done using low cost NodeMCU module, It uses relays and few simple components, four electrical devices can be controlled, Temperature and Humidity can be monitored. NodeMCU is low cost module is used here. The electrical devices can be controlled by the help of Google assistance and by the blynk android app. In contrast, Wireless system can be of great help for automation systems. With the advancement of wireless technologies such as Wi-Fi, Cloud networks in the recent past, Wireless systems are used every day and every where.

#**Components used**
1. Node MCU (Lolin)
2. DHT 11 
3. LDR 
4. Relay 6V 
5. Resistance 330 Ohms
6. Transistor  BC 547
7. L.E.D.
8. D.C. Jack
9. Diode IN 4007
10. General PCB Board
11. Wires
12. Adaptor 5V 2 Amps
13. Relay Connector

#**FUNCTIONS OF BASIC  COMPONENTS USED:**
**NODE MCU:**
NodeMCU is an open source development board and firmware based in the
 widely used ESP8266 -12E Wi-Fi module With its USB-TTL ,the nodeMCU 
board supports directly flashing from USB port. It combines features of WIFI
 accesspoint and station + microcontroller. These features   make the NodeMCU
 extremly powerful tool for Wi-Fi networking. It can be used as accesspoint and/or
 station, host a webserver or connect to internet to fetch or upload data.-In our 
project pins D1,D2,D7 and D8 are used to automate two lights and two fans
 respectively.Pin A0 is connected to LDR.D6 is connected to DHT11
**DHT11:** It is a sensor which is used to sense temperature and humidity of a 
 particular area.
**LDR:** It is a Light Dependent Resistor  used to sense the intensity of light.Here
 we are using a  LDR which has a maximum value of 1024.
**Relay:** A relay is an electrally operated switch. Many relays use an
Electromagnet to mechanically operate a switch. Relays are used where it is
 necessary to control a circuit by a separate low-power signal, or where several
 circuits must be controlled by one signal.In our project we have used  6volt
 relays to control two lights and two fans respectively.
**Transistor:** A transistor is a semiconductor device used to amplify or switch
electronic signals and electrical power. It is composed of semiconductor material 
usually with at least three terminals for connection to an external circuit.
In our project we have used transistor BC547  whose base is connected to node mcu ,
emitter to ground and collector to Relay.
**LED:** In our project we have used Two LED’s one Red and one Yellow.
When the circuit is on Red light glows and when we there is a online connection 
established  between the server and circuit yellow led glows.
**DC JACK:** A DC connector (or DC plug, for one common type of connector)
is an electrical connector for supplying direct current(DC) power.
**Diode:** Main functions. The most common function of a diode is to allow an 
electric current to pass in one direction (called the diode's forward direction),
while blocking it in the opposite direction (the reverse direction).
In our circuit  the positive pin of diodes are connected to  Relay.
**General PCB Board:** In our circuit we have used PCB instead of Breadboard 
and we have soldered each and every connection to make the connections tight  and Errorfree.
It  also makes it easier to carry.
**Adaptor:** An adaptor is used to connect to switch boards so that it can work on fans and lights directly.
**Relay Connector:** It is used to connect Relays

You can use the [editor on GitHub](https://github.com/Trivediujjwal/home-automation/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Trivediujjwal/home-automation/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

