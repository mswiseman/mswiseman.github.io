---
layout: post
title:  "DIY Laboratory Hardware"
excerpt: "Resources to inspire creative problem solving"
project: true
feature: https://hackster.imgix.net/uploads/attachments/930989/pmp-ph-wiring-diagram_kIYhbdsmNg.png
date: 2022-03-15
tags:
- DIY 
- maker
- hardware
- hardwareX
- automation
comments: true
---
**Can you break down tasks or processes from your research into simple, step-wise parts? Do you have processes that sequentially build from previous steps? Does your work involve gathering multiple types of environmental data at regular increments? If so, you might consider exploring DIY software and/or hardware for your laboratory.**

## Background

This website is a resource for anyone interested in DIY **f**ree and **o**pen **s**ource **h**ardware and **s**oftware (FOSH and FOSS) for their plant science research. <br><br>I am **not** an engineer and thus I have tried to tread lightly in areas for which my terminology and/or understanding may not be accurate or thorough. Sometimes exploring a new skill or field can be frustrating or intimidating, especially early in the process; to overcome this, I encourage you to seek help from people who have more experience and from the many other resources available (videos, documentation, forums, books, etc.). Keep in mind: nobody is all-knowing and everyone has to start somewhere; alas, let's foster a collaborative and supportive DIY movement together!

## Why DIY FOSH and FOSS?

If your lab is fortunate enough to be flush with funding, you may be asking: why bother building something myself when I can pay a company to do it for me? Great question. This may not be relevant for you. However, you may still find other benefits by learning how to build hardware and software yourself. Some benefits include:

* Improving accessibility to underfunded laboratories
* Creating customization and/or automation for repetitive tasks
* Improving intra- and inter-laboratory reproducibility
* Learning critical troubleshooting, coding, and electrical skills
* Getting paid to build the socially-acceptable version of adult Legos (:smirk:)

## Resources

**Interested in learning more? I hope so!** I encourage you to first review the selected publications below as I believe they have exceptional documentation and show the breadth of possible applications. While pursuing the published, peer-examples, think about similarities and differences between your work processes and the published work: does your research have similar tasks or processes? If so, a good place to start is by learning more about the hardware and software implemented in the paper of interest. If electronic wiring and microcontrollers are new to you, you should then consider exploring a DIY kit before starting on a larger project - this will greatly reduce frustration later on by building troubleshooting skills in low stakes situations (versatile kits [here](https://www.amazon.com/ELEGOO-Project-Tutorial-Controller-Projects/dp/B01D8KOZF4/), [here](https://www.amazon.com/Arduino-Starter-Kit-English-Official/dp/B009UKZV0A/)). 

* [Selected publications for inspiration](#selected-publications)
* [Peer reviewed scientific resources](#peer-reviewed-scientific-resources)
* [Free and open source software](#free-and-open-source-software)
* [Documentation for commonly used hardware](#hardware-documentation)
    * [Microcontrollers](#microcontrollers)
    * [Stepper drivers](#stepper-drivers)
    * [Environmental sensors](#environmental-sensors)
    * [Microprocessors/Mini-Computers](#microprocessors)
* [Exceptional YouTube tutorials](#youtube-links)
* [Recommendations on where to purchase components](#purchasing-recommendations)
* [Local resources for Oregon State University](#local-resources)
* [Links to insightful reviews and commentary](#insightful-reviews-and-commentary)
* [Useful CAD Libraries and Open Hardware Repositories](#useful-cad-libraries-and-open-hardware-repositories)
* [Books](#books)
* [Other](#other)
* [Contact](#contact)

<sub>*Disclosure statement: I do not benefit financially from any of the links on this page.*</sub>

---

## Selected publications
[Back to top](#resources)

[**Highly-Customizable 3D Printed Peristaltic Pump Kit**](https://www.sciencedirect.com/science/article/pii/S2468067221000316#f0010)<br>
Applications: precise fluid handling, cell culture, microfluidics<br>
Cost: $51 USD

![Graphical Abstract](https://raw.githubusercontent.com/mswiseman/mswiseman.github.io/master/assets/img/customizable_peristaltic_pump.jpg)
Other peristaltic pumps: [Jönsson et al. 2020](https://www.sciencedirect.com/science/article/pii/S2468067220300249), [iGEM Aachen Team 2017](https://www.instructables.com/Open-Source-Peristaltic-Pump/), [Thingiverse peristaltic pumps (not necessarily peer-reviewed)](https://www.thingiverse.com/search?q=peristaltic+pump&type=things&sort=relevant)

---

[**Principles of computer-controlled linear motion applied to an open-source affordable liquid handler for automated micropipetting**](https://www.nature.com/articles/s41598-020-70465-5/)<br>
**Applications**: liquid handling, cell culture, phenomics<br>
**Cost**: $1500 USD

![Graphical Abstract](https://raw.githubusercontent.com/mswiseman/mswiseman.github.io/master/assets/img/otto.webp)
Other liquid handlers: [Eggert et al. 2020](https://www.sciencedirect.com/science/article/pii/S2468067220300614), [Faiña et al. 2020](https://www.mdpi.com/2076-3417/10/3/814/htm)

---

[**eGreenhouse: Robotically positioned, low-cost, open-source CO2 analyzer and sensor device for greenhouse applications**](https://www.sciencedirect.com/science/article/pii/S2468067221000225#f0385)<br>
**Applications**: phenomics, environmental sensing, precision agriculture<br>
**Cost**: Varies with size of application, starts at ~$150<br>

![Graphical Abstract](https://raw.githubusercontent.com/mswiseman/mswiseman.github.io/master/assets/img/greenhouserobot.jpg)
Other greenhouse tools: [Plug-and-play Hyperspectral Imaging Sensor](https://www.sciencedirect.com/science/article/pii/S2468067219300513), [HyperRail](https://www.sciencedirect.com/science/article/pii/S2468067219300483),[Robotic Gantry System](https://www.sciencedirect.com/science/article/pii/S2468067221000031), [Irrigation Water Usage Monitoring](https://www.sciencedirect.com/science/article/pii/S2468067219300070)

---

## Peer reviewed scientific resources
[Back to top](#resources)

<img align="left" alt="HardwareX Logo" src="https://raw.githubusercontent.com/mswiseman/mswiseman.github.io/master/assets/img/hardwarexlogo.gif" class="padding" />

[HardwareX](https://www.journals.elsevier.com/hardwarex) is a peer-reviewed open access scientific journal dedicated to the open source design and construction of scientific instrumentation. The journal publishes science hardware shared under an open source hardware license. For DIY hardware, I believe HardwareX has the most detailed manuscripts thus enabling easier reproducibility. <br clear="left"/>

<img align="left" alt="Nature Scientific Reports Logo" src="https://raw.githubusercontent.com/mswiseman/mswiseman.github.io/master/assets/img/ScientificReportsandNatureLogo.png" class="padding" />

[Nature Scientific Reports](https://www.nature.com/srep/) is an open access journal publishing original research from across all areas of the natural sciences, medicine and engineering. To find manuscripts more likely to have DIY hardware, I would explore the tags [*lab-on-a-chip*](https://www.nature.com/search?q=lab-on-a-chip&order=relevance&journal=srep), [*biomedical engineering*](https://www.nature.com/search?q=biomedical%20engineering&order=relevance&journal=srep), or [*mechanical engineering*](https://www.nature.com/search?q=mechanical%20engineering&order=relevance&journal=srep). <br clear="left"/><br>

<img align="left" width="100" alt="Precision Agriculture" src="https://raw.githubusercontent.com/mswiseman/mswiseman.github.io/master/assets/img/precisionagriculture.png" class="padding" />

[Precision Agriculture](https://www.springer.com/journal/11119) presents innovative data and technologies emerging from research in the field of precision agriculture. <br><br><br clear="left"/>

---

## Free and open source software
[Back to top](#resources)

Free and open-source software (FOSS) enable unrestrained reuse and modification of a software's source code. Linux OS and Mozilla Firefox are classic examples of FOSS that enjoy widespread usage. There's a great list of open CAM/CNC software [here](https://www.reddit.com/r/hobbycnc/comments/aj0hu8/list_of_free_and_open_source_camcnc_software/).

---

## Hardware documentation
[Back to top](#resources)

I've included direct links to the documentation of hardware commonly used in DIY free open source hardware. This field is rapidly evolving, so I imagine this section will change frequently. 

### Microcontrollers

[Microcontrollers](https://makezine.com/2016/09/06/12-specs-to-consider-when-choosing-a-microcontroller-for-your-product/) are the brains of hardware - they tell the other components what to do. They are best suited for simple repetitive tasks (such as activating a motor). I recommend choosing a microcontroller based on your power needs, programming language preference (generally C or micropython), peripherals, and based on the company's reputation and the available documentation. Speaking from experience: you will save yourself *a lot of frustration* if you work with a microcontroller that has thorough documentation and support (like the Arduino series). 

**Overview of Common Open Source Microcontrollers**

<img align="center" width="500" alt="Microcontrollers" src="https://raw.githubusercontent.com/mswiseman/mswiseman.github.io/master/assets/img/microcontrollers.png">

Boards |A. [Arduino Nano](https://store.arduino.cc/usa/arduino-nano) |B. [Arduino Uno](https://store.arduino.cc/usa/arduino-uno-rev3) |C. [Arduino Due](https://store.arduino.cc/usa/due) |D. [Raspberry Pi Pico](https://www.raspberrypi.org/products/raspberry-pi-pico/)
--- | --- | --- | --- | ---
Price | $20 | $30 | $40 | $4 
Processor | ATmega328 | ATmega328P | AT91SAM3X8E | Dual-core Arm Cortex-M0+
Processor Speed | 16 MHz | 16 MHz | 16 MHz | 84 MHz
Analog Pins | 8 | 6 | 12 | 3
Digital Pins | 22 | 6 | 54 | 26
Memory | 32 KB | 32 KB | 512 KB | 264 KB
Programming Language | Arduino (C) | Arduino (C)| Arduino (C) | C and MicroPython
Programmer | USB | USB | USB | USB
Serial Communication | UART | UART or SPI | UART or SPI | UART or SPI

#### CNC Microcontrollers
Have a task that can be programmed and contained on an X, Y, Z system? You'll probably use computer numerical control (CNC). These microcontrollers have firmware that's adapted for and commonly used in CNC applications (CNC routers, 3d printers, liquid handlers, etc.):
* [Arduino Uno (8-bit)](https://store.arduino.cc/usa/arduino-uno-rev3)
* [Arduino Mega (8-bit)](https://store.arduino.cc/usa/mega-2560-r3)
* [Arduino Due (32-bit)](https://store.arduino.cc/usa/due)
* [Duet2 (32-bit)](https://www.duet3d.com/DuetWifi)
* [Duet3 (32-bit)](https://www.duet3d.com/Duet3Mainboard6HC)
* [Smoothieboard (32-bit)](http://smoothieware.org/)

#### Tiny Microcontrollers
These tiny microcontrollers are well-suited for wearable, lightweight, or space-limited applications. 
* [Ardunio Nano (8-bit)](https://store.arduino.cc/usa/arduino-nano)
* [Raspberry Pi Pico](https://www.raspberrypi.org/products/raspberry-pi-pico/)
* [Seeeduino XIAO](https://www.seeedstudio.com/Seeeduino-XIAO-Arduino-Microcontroller-SAMD21-Cortex-M0+-p-4426.html)

---

### Microcontroller firmware
Firmware is essentially permanent software that is programmed to microcontrollers. You will need to change the firmware (or write your own) to adapt it for your application; consequently, it's wise to familiarize yourself with the available resources, formatting, and limitations of various firmware packages. Firmware is typically written in C, C++, or Micropython. The software component of DIY hardware *can be challenging*, **but** there are tools, such as integrated development environments (IDE), that can make customizing firmware fairly straightforward. Not familiar with IDE? If you have used R-Studio or Jupyter Notebook, then you have used IDEs for the R and Python, respectively. [Here's](https://www.youtube.com/watch?v=ana1mFFMHIk) a nice overview of IDEs.

[Updated list of active open source microcontroller firmware](https://reprap.org/wiki/List_of_Firmware)



<img align="left" width="75" alt="Marlin" src="https://raw.githubusercontent.com/mswiseman/mswiseman.github.io/master/assets/img/marlin.png" class="padding" /> 

[Marlin](https://marlinfw.org/) <br>
[Compatible 8/16/32-bit boards](https://marlinfw.org/docs/hardware/boards.html) <br><br clear="left"/>

<img align="left" width="75" alt="Grbl" src="https://raw.githubusercontent.com/mswiseman/mswiseman.github.io/master/assets/img/grbl.png" class="padding" />

[grbl](https://github.com/grbl/grbl) <br>
Compatible with Arduino Uno Stack, Arduino Nano Stack, MKS-DLC, Mega 2560 Stack, and others <br><br clear="left"/>

<img align="left" width="75" alt="Micropython" src="https://raw.githubusercontent.com/mswiseman/mswiseman.github.io/master/assets/img/micropython.png" class="padding" />

[MicroPython](https://micropython.org/download/) <br>
Compatible with Pyboard v1, STM32 boards, Raspberry Pi Pico, WiPy, TinyPICO, and others  <br><br clear="left"/>

<img align="left" width="75" alt="RepRap" src="https://raw.githubusercontent.com/mswiseman/mswiseman.github.io/master/assets/img/reprap.png" class="padding" />

[RepRap](https://reprap.org/wiki/RepRap) <br>
[Compatible 8/16-bit boards](https://reprap.org/wiki/Category:8/16-bit_board)<br>
[Compatible 32-bit boards](https://reprap.org/wiki/Category:32-bit_board)  <br><br clear="left"/>

[Smoothieware](https://smoothieware.org/)<br>
Compatible with all RepRap boards <br>

---

### Stepper drivers
Stepper motors are the most type of common motor deployed in high-precision CNC-type applications. Stepper motors work move in a precise, incremental, step-wise fashion (thorough review [here](https://www.motioncontrolproducts.com/applications/selection-guide-for-stepper-motors/)). Stepper drivers are components that *drive* stepper motors.  Stepper drivers are often integrated into microcontroller boards, but can also be wired externally. When choosing a stepper driver, one needs to consider how powerful their stepper motors are, what extra features they would like, and how precise they need their stepper motor to be. Good overviews can be found [here](https://all3dp.com/2/what-s-a-stepper-motor-driver-why-do-i-need-it/), [here](https://3daddict.com/stepper-driver-comparison-3d-printer-upgrade/), and [here](https://www.drdflo.com/pages/Guides/How-to-Build-a-3D-Printer/Stepper-Driver.html). 

<img align="center" width="500" alt="Example of stepper driving wiring" src="https://raw.githubusercontent.com/mswiseman/mswiseman.github.io/master/assets/img/A4988.jpg">

---

### Environmental sensors
Microcontrollers and microprocessors are well suited for environmental sensing; as such, many accessory modules have been developed and are able to detect air movement, humidity, temperature, light, vibration, sound, etc. If you're an OSU researcher and have a project involving environmental sensing, reach out to the [OPEnS Lab](https://open-sensing.org/) - this is their specialty. If not, I've provided some resources below. 

* [Open Source Ecology](https://wiki.opensourceecology.org/wiki/Main_Page)
* [Tutorials on several environmental sensors](http://www.osbss.com/tutorials/)
* [Low-cost electronic sensors for environmental research: Pitfalls and opportunities](https://journals.sagepub.com/doi/full/10.1177/0309133320956567)
* [HardwareX special issue on environmental sensing](https://www.sciencedirect.com/journal/hardwarex/special-issue/10GZTLV8SHB)
* [How to build an Arduino data logger](https://thecavepearlproject.org/how-to-build-an-arduino-data-logger/)
* [Cave Pearl Data Logger](https://www.mdpi.com/1424-8220/18/2/530)
* [Portable DIY hummingbird triggering system](https://onlinelibrary.wiley.com/doi/full/10.1002/ece3.3040)
* [DIY environmental microcontroller units (EMUs)](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.13128)

---

### Microprocessors
Technically speaking, microprocessors (aka mini-computers) are not microcontrollers as they can handle multiple tasks at once. These are best suited for software-heavy applications or as a computer that controls multiple microcontrollers.

* [Beagle Board](https://beagleboard.org/)
* [Raspberry Pi](https://www.raspberrypi.org/)

---

## YouTube Links 
[Back to top](#resources)

There are endless tutorials and informational videos on YouTube, but some are more helpful than others. I found these to be particularly helpful with my adventure into DIY hardware. 

* [How to build a 3D printer, The Ultimate Guide](https://youtu.be/qub5chyIQ0s)
    * This video thoroughly covers the details and considerations of common components of most CNC hardware.
* [Breadboarding & Prototyping for Electronics, Arduino & Raspberry Pi](https://youtu.be/Y3Kx2RlLXsY)
* [Schematic Diagrams & Symbols, Electrical Circuits](https://youtu.be/Dl1gFBNa0Ik)
* [How to wire a cheap power supply](https://youtu.be/Ls-6BeLHbA0)
* [DIY Dremel CNC electronics, software and firmware](https://youtu.be/xfQ0YosR6us)
* [How To Wire It! Stepper Motors](https://youtu.be/GgfgWU0bpHk)
* [Raspberry Pi Pico - Control the (I/O) World](https://www.youtube.com/watch?v=Zy64kZEM_bg&t=247s)
* [Raspberry Pi CNC Controller](https://www.youtube.com/watch?v=u35L0jGCqFc)

---

## Purchasing recommendations

Regardless of who you buy from, most of your hardware components will be manufactured in China; alas, it is tempting to get the best price and buy from Alibaba. Unfortunately, when you buy an open-source chip from Alibaba or another third-party seller, you are likely not supporting the developers who put time and energy into developing open-source hardware. If you have the financial means to pay slightly more to support open-source developers, please do. Not only will you help support the movement, but also exchanges are easier, and you typically receive much better technical support. Further, there have been reports of shortcuts in rip-off hardware that have led to safety hazards not present in original genuine open source release.  Nonetheless, open source is open source, so if your lab is in the dire straits, Aliexpress will almost always be the cheapest option. 

* Microprocessors and microcontrollers direct from designers
    * [Adafruit](https://www.adafruit.com/)
    * [Arduino](https://www.arduino.cc/)
    * [Raspberry Pi](https://www.raspberrypi.org/)
    * [Smoothieboard](http://smoothieware.github.io/Webif-pack/documentation/web/html/smoothieboard.html)
* Custom Printed Circuit Boards (PCBs)
    * [Fritzing](https://fritzing.org/) 
* Authorized resellers
    * [DigiKey](https://www.digikey.com/en/products) 
* Misc. Open Source Hardware
    * [OpenBuilds](https://openbuildspartstore.com/) 
* Third-party* resellers (\**usually*\)
    * [AliExpress](https://www.aliexpress.com/)
    * [Amazon](https://www.amazon.com/)

---

## Local resources 
[Back to top](#resources)

* [Corvallis Public Library](https://cbcpubliclibrary.net/3d-printing/)
3d printing available, literature, and a makers club. 
* [Electrical Engineering Capstone Student Projects](https://eecs.oregonstate.edu/industry-relations/capstone-and-senior-design-projects)
Request a senior EE student to help with your project. 
* [OPEnS Lab](https://github.com/OPEnSLab-OSU/OPEnS-Lab-Home/wiki)
Available help for your environmental sensing projects as well as access to 3d printing and laser cutting. 
* [OSU Library](https://guides.library.oregonstate.edu/3Dprinting)
3d printing and literature. 

---

## Insightful Reviews and Commentary 
[Back to top](#resources)

* [Harnessing the Benefits of Open Electronics in Science](https://arxiv.org/abs/2106.15852)
* [A Review of Raspberry Pi Usage in Scientific Research](https://www.raspberrypi.org/blog/raspberry-pi-a-versatile-tool-for-biological-sciences/)
* [Smoothieware vs. Marlin: Which Firmware is Better](https://www.3dprintingspot.com/post/smoothieware-vs-marlin-which-firmware-is-better)
* [A DIY approach to automating your lab](https://www.nature.com/articles/d41586-019-01590-z)
* [Building Research Equipment with Free, Open-Source Hardware](https://science.sciencemag.org/content/337/6100/1303.summary)
* [Science for All: How to Make Free, Open Source Laboratory Hardware](https://blogs.scientificamerican.com/guest-blog/science-for-all-how-to-make-free-open-source-laboratory-hardware/)
* [Economic savings for scientific free and open source technology: A review](https://www.sciencedirect.com/science/article/pii/S2468067220300481)

---

## Useful CAD Libraries and Open Hardware Repositories
[Back to top](#resources)

![Thingiverse](https://raw.githubusercontent.com/mswiseman/mswiseman.github.io/master/assets/img/thingiversesmall.png)

* [3D Plant Phenomics](http://3dplantphenomics.org/)
* [Grabcad](https://grabcad.com/library/)
* [Thingiverse](https://www.thingiverse.com/)
    * [Open-Source Lab](https://www.thingiverse.com/thing:182640)
    * [Plant Science DIY](https://www.thingiverse.com/mswiseman/collections/diy-hardware-for-the-plant-sciences)
* [GaudiLabs Open Hardware Projects](http://www.gaudi.ch/GaudiLabs/?page_id=19)
* [Open-Source Lab](https://www.appropedia.org/Open-source_Lab)
* [PLOS Open-Source Toolkit](https://collections.plos.org/collection/open-source-toolkit-hardware/)

---

## Books
[Back to top](#resources)

* [Fusion 360 for Makers](https://www.amazon.com/Fusion-360-Makers-Printing-Fabrication/dp/1680453556)
* [Practical Electronics for Inventors](https://www.amazon.com/Practical-Electronics-Inventors-Fourth-Scherz/dp/1259587541/ref=sr_1_1?dchild=1&keywords=practical+electronics+for+inventors&qid=1622040874&s=books&sr=1-1)
* [Encyclopedia of Electronic Components Volume 1](https://www.amazon.com/Encyclopedia-Electronic-Components-Capacitors-Transistors/dp/1449333893/ref=pd_sbs_7/134-5390653-5442422?pd_rd_w=MPp99&pf_rd_p=f8e24c42-8be0-4374-84aa-bb08fd897453&pf_rd_r=50ZDS4X0ENSBGA950ZMJ&pd_rd_r=c8ae5535-5a71-468f-947b-a63c9233195e&pd_rd_wg=J58Dv&pd_rd_i=1449333893&psc=1)
* [Make: Electronics: Learning Through Discovery](https://www.amazon.com/Make-Electronics-Learning-Through-Discovery/dp/1680450263/ref=pd_sbs_3/134-5390653-5442422?pd_rd_w=MPp99&pf_rd_p=f8e24c42-8be0-4374-84aa-bb08fd897453&pf_rd_r=50ZDS4X0ENSBGA950ZMJ&pd_rd_r=c8ae5535-5a71-468f-947b-a63c9233195e&pd_rd_wg=J58Dv&pd_rd_i=1680450263&psc=1)
* [Programming Arduino: Getting Started with Sketches](https://www.amazon.com/Programming-Arduino-Getting-Started-Sketches-ebook/dp/B01FJ24SZG/ref=zg_bs_157705011_3?_encoding=UTF8&psc=1&refRID=Q3EHVD9HG6EHVDP7VG9C)
* [Raspberry Pi Cookbook](https://www.amazon.com/Raspberry-Pi-Cookbook-Software-Solutions-ebook/dp/B07Z78XCTH/ref=zg_bs_157705011_2?_encoding=UTF8&psc=1&refRID=Q3EHVD9HG6EHVDP7VG9C)

---

## Other
[Back to top](#other)
* [OpenPlant](https://www.openplant.org/)
* [Protocol IO](https://www.protocols.io/)

---

## Contact?  
[Back to top](#resources)

Feel free to [email me](mailto:msw287@cornell.edu?subject=Open%20Hardware%20GitPage) with questions, comments, or if you're interested in collaboration. Follow my open liquid handler and modular PCR system build [here](https://mswiseman.github.io/gentlabottobot/). 

---

## Acknowledgments

I'd like to thank **David Florian** ([@DrDFlo](https://www.drdflo.com/)) for his help and feedback while navigating adaptation of [his Ottobot design](http://openliquidhandler.com/) for my application. Thank you to my fellow makers for all your feedback, my supportive lab mates (Briana Claassen, Teddy Borland, Mary Block, Steve Massie, and Nanci Adair), and my incredibly patient, kind, supportive, and brilliantly insightful adviser, **Dr. David Gent**. 

To be clear, I collaborate with people that aren't named David too :sweat_smile:. Updated March 15th, 2022. 


