# Who/Where/How/...

## Who am I

Hi, I'm a software developer with a high proficiency in C/C++, a great experience in embedded development, and a keen interest in everything electronics. I hope that my github will portray my experience and know-how

<details>
<summary><b>Click here for more information</b></summary>

## What do I do best

I'm great at investing myself fully into what I do. I like to own my code. Said differently, I get involved, I'm passionate about what I do.

On the upsides, it means that, if I understand the _why_ and the context of what I do, I'm capable of great throughput of high quality of code.

But it does also mean that I don't perform as well in "mindless" code-production. I need to understand the environment my code will fit in, its purpose, its destination.

## How I work collaboratively

I'm, by heart, a team-first/project-first kind of person. I thrive when whatever I'm working on is successful. And thrive even more when I see that my help was useful.

I'm always happy to help, and I will ask for help.

A healthy team environment is a must for me.

## Where am I

Well, I'm mostly looking in Paris area right now, but I have an open door for interesting opportunities in Finland

## What should you do to get the most out of me

Communicate directly what you need. Give me the tools and the extent I can work within. Be ready to explain _why_ X and not Y. It is necessary for me to understand deeply the framework I evolve in, so I _need_ to be able to question the framework.

</details>

# Experience

## Work experience

I have worked as a software consultant in quite a few different projects, both small and big, France and Finland, high-pace and low-pace.

Those various experiences have allowed me to be flexible in how I approach projects. Agile method ? Small team ? Industrialisation ? R&D ? I can adapt.

I'm also well educated in the constraints of international teams, and find pleasure in multicultural interactions

<details>
<summary><b>Click here for more information</b></summary>

---

### Asvestis

#### C++ software developer -- _2023_ (France)

#### Main topic

Designing a stack for high precision high frequency positioning

#### Main production

- Linux kernel fix
  - Investigation around regmap in Linux kernel
  - Designed a workaround
- Made a prototype for high speed IMU sampling
  - Understanding 9dof IMU datasheet
  - Made a workaround to make magnetometer work

<details>
<summary><b>Click here for more information</b></summary>

#### Context

Asvestis is an automotive startup aiming at building a mesh network between
cars

They have specifically a focus in synergy (decisions made simultaneously by multiple operators)

For this goal, they had an interest in knowing exactly where each agent is from each other

#### Result

- Showcased high samplerate IMU by reproducing music
- Made 3 presentations

#### Keywords

vs code, C, C++, I2C, SPI, Linux, kernel driver

</details>

---

### Varaani Works Oy

#### C/Embedded Software developer -- _2021-2022_ (Finland)

#### Main topic

Middle layer between embedded software and high level programming

#### Main production

- Shared memory abstraction
  - Versionning of shared memory structure
  - Protection against non structured access
- Communication between cores
  - Polling to detect changes of shared variables
  - Interrupts through Mailboxing
  - Low latency

<details>
<summary><b>Click here for more information</b></summary>

#### Context

The customer wanted to develop a new platform.

They didn't have internal resources for embedded development

The goal was therefore to implement an abstraction layer between embedded details and high level
language

#### Result

- Prototype made in 2 weeks

#### Keywords

Git, C, Embedded Systems, DSP

</details>

---

### Kaukolab

#### Entrepreneur -- _2021_ (Finland)

#### Main topic

Making physics experiments accessible through Internet

#### Main production

- Making a prototype showcasing a pendulum
  - Writing firmware
  - Streaming video through WebRTC
  - Designing a Domain Specific Language
- Improving prototype
  - Designing a step motor controller PCB
  - Programming firmware
- Improving business understanding
  - Followed business course

<details>
<summary><b>Click here for more information</b></summary>

#### Context

COVID has shown demand in remote learning

However, some skills cannot easily be taught through Internet, such as making lab experiments

Learning through computer simulations is too limited in scope. Learning through videos is too
disconnected.

The goal of Kaukolab was to robotize a lab, and offer a Web interface to interact with it

#### Result

Appeared on Lahti Talenthub promotional videos

#### Keywords

Git, Kicad, puppeteer,
C, C++, Python, TypeScript,
Node.js, webrtc,
PCB design

</details>

---

### Unikie (Nokia)

#### Software consultant -- _2019-2020 _ (Finland)

#### Main topic

Participation to improvement of Nokia Baseband 5G in a Agile environment

#### Main production

- Continuous test improvements
  - Add Robot Framework Tests28
  - Add JSON Syntax Checker
- Bug tracking
  - Automation for git bisecting
  - Blackbox debugging
- Python script to sanity check captured packets
  - Added Yocto rules
  - Parsed PCAP

<details>
<summary><b>Click here for more information</b></summary>

#### Context

Nokia had decided speeding up 5G development was of business interest

It meant high speed development with many teams involved, making it difficult to keep different parts
working together

A performant Continuous Integration system was needed and designed

I worked in a team focused on improving the CI in Baseband Layer 1

#### Result

- Added 10 Robot tests
- Sanity checker integrated into CI
- Found and solved a bug only appearing once in twenty executions
- Automatized build process

#### Keywords

Gitlab CI, BitBucket, ARM, Git, GitLab, JIRA, Wireshark,
C, Python,
RobotFrameWork, Yocto,
Agile,
LTE

</details>

---

### Auticonsult (EDF)

#### C++ software consultant -- _2016-2019_ (France)

#### Main topic

Improving a Load Flow calculator, with the goal of outputting Electric Network
configuration meeting some electrical constraints, to help Electricity Distribution Conductors

#### Main production

- Speed/memory optimization
  - Memoization of results
  - Refactoring of legacy code
- Improving Results reproducability
  - Creating System tests
  - Log parsing and data extraction
  - Adding telemetry to logs
  - Using TCP packet capture
  - Designing a UX to visualize logs
- Topology computation
  - Mixed-linear-programming based load flow
  - Doxygen based documentation
- Computing Production offset
  - Implementation of a specification
  - Testing of code with specificator

<details>
<summary><b>Click here for more information</b></summary>

#### Context

Electricity distribution is hard, it has to meet various constraints : physical (overcurrent), economical (offsetting production) or usability (undervoltage)

To do so, a whole software suite is available to conductors to help them manage those constraints

Within this software suite, the conductor can request the computation of forecasted electrical
transits, of topology changes meeting some field-constraints, of production/consumption offset, and
many other computation.

This project focused specifically on these constraints

#### Result

- 6x speed / 10x memory optimization
- all developments have been deployed
- reduced technical debt

#### Keywords

Doxygen, GCC, SVN,
C++,
Qt, Qt4, Memoization, Mixed Linear Programming, Transcompiling,
TCP/IP

</details>

---

### AaERS (aide aux énergies renouvellables et solaires)

#### Software developer -- _2015-2016_ (France)

#### Main topic

Simulation of the efficiency of a heat-engine

- Based on SciPy NumPy
- With visualization

#### Main production

- Heat engine simulator
  - Modeling problem through differential equations
  - Solving differential equations through scipy
- Simulation for Solar panel concentrator
  - Writing a 2d ray tracing software

<details>
<summary><b>Click here for more information</b></summary>

#### Context

AaERS was a Electricity/Plumbing company with a vested interest in renewable
energies. It aimed at providing customers with efficient way of generating energy, with a specific
interest in heat-engines

#### Result

- Met requirements and helped future developments

#### Keywords

Scipy, Python

</details>

</details>

## Showcase

I have made, over the years, quite a few projects, some purely computer related, some based on electronics, some unrelated to technology

Here are the main ones

<details>
<summary><b>Click here for more information</b></summary>

### Electronics

#### Paillaas ( [Kaukolab](#kaukolab) )

I had decided in 2021 to leave my job and start a business, Kaukolab, to develop tools for better remote learning :

I have fond memories of session of lab work during my studies. Unfortunately, they are hard to do with remote learning. The only offers I saw on the market during my research were either based on simulations, with lots of simplification compared to the real world, or based on a few video of real experiments, but with almost no user input. Part of the experience of lab work is to experiment, break things, discover what is true and not simply check what you know is true is true.

My idea was to have real physical experiments users could connect to through Internet

Features :

- pcb design
- puppeteering
- micropython
- domain specific language
- reactive HTML
- ...

[Available on github](https://github.com/jollie-fin/paillaas)

#### Speedomobile

This project goal is to have a fun plateform to showcase the following :

- sensor fusion
- persistence of vision
- spatial pollution measurement
- video stream enhancement
- non trivial Rust project
- PCB design

It consists, in a way, in a "let's put every components I can find" kind of project

It can be considered as the v2 of [ebike controller](https://github.com/jollie-fin/tsdz2-esp8266), in the sense that my goals are to transform my recumbent bike in a super bike :

More specifically, I want to

- Control my ebike
- Map the air quality along my travel
- Have high resolution positionning, to help OSM mapping
- Transform my bike into a christmas-tree, with Persistence of Vision
- Be able to live stream my journeys

[Available on github](https://github.com/jollie-fin/speedomobile)

#### AVR Assembly

A compilation of various projects I worked on as a teen. Various levels of usefulness !
[Available on github](https://github.com/jollie-fin/avr-assembly)

#### Wifi lamp

A wifi enabled lamp, made from a bunch of LED-ribbons on aluminium profiles and driven by an ESP8266, with web app

Finland is famously dark in winter, so I wanted to have a big lamp with natural white, that could fill up a living room with nice warm light.

Designed around an ESP8266 on a protoboard, some mosfet drivers, two mosfets. Probably not ok EMI-wise...

A wifi interface is available to change brightness, enable or disable alarm clock, etc.

A nice feature is that the color temperature change depending on the brightness. It starts orangy, yellow, white, and even gets a slight blue hue. Perfect for waking up.

Some cares have been taken to reduce standby power consumption (<1W)

[Available on github](https://github.com/jollie-fin/sunlamp-esp8266)

#### Ebike controller

An ESP8266 based controller to setup electric assist on a TSDZ2 ebike motor that was sold defective, with web app.

Why exchange under warranty when you can make a replacement part that is worst 😁

[Available on github](https://github.com/jollie-fin/tsdz2-esp8266)

### C++

#### Enoria-relay

With the rising energy crisis, the local parish was looking to reduce energy expanditure around heating. The easy approach "first one put on, last one put off" was not sufficient because their buildings are old : they take a while to heat up.

The following idea was suggested. Since the room occupancy schedule is available online through Enoria, why not programmatically put on and off the heater based on the schedule ?

[Available on github](https://github.com/jollie-fin/enoria-relays)

#### Range-based libiio client

A smart C++-23 abstraction-layer for libiio userspace interface.

[Available upon request](mailto:)

#### Compress

An old attempt at compressing an image by cross-producting with noise pattern. Results were not impressive to say the least.

[Available on github](https://github.com/jollie-fin/compress/)

### Correlation

This code simulate interferences between multiple microphones or multiple sound sources, ignoring reverb

Given :

- A list of microphones position in space
- A list of sound sources

it will calculate time-of-flight of each source-microphone, and add the source file to the output file shifted in time by this time-of-flight

it can also properly shift by a fractional amount of frame through sin x/x interpolation

C++ level is beginner level

[Available on github](https://github.com/jollie-fin/correlation)

#### Gopro analyzer

This project extract and transform gopro metadata

Desired workflow :

- Dump a lengthy gopro-footage
- Retrieve metadata
- Adjust colorimetry on the fly, based on an xml file
- Include an map based on OSM in the video
- Include some telemetry in the video
- Export the resulting video, to be uploaded on youtube

It's basically imitates some features of OBS Studio, without the realtime aspect

[Available on github](https://github.com/jollie-fin/slowtv)

### Python

#### Topo2photo

A tool to generate maps from opendata

My niece is really into maps. And I wanted to print out some nice map of part of the world. Why pay/download for hi-res images when one can make it themselves from scratch !

So I have plunged into the deep end of opendata to gather satellite images from CopernicusHub, Google Cloud Storage, Amazon open access... to generate arbitrary photorealistic maps

This tool retrieve some images and warp them according to some projection

It can :

- Rasterize a shapefile
- Assemble a mosaic, with invisible seams
- Correct seams due to BSDF issues with [homonim](https://github.com/leftfield-geospatial/homonim), based on [world esa map](https://viewer.esa-worldcover.org/worldcover/)
- Retrieve from Amazon S3 (through boto3) or Google Storage API mosaic images, lazily
- Cache files accordingly
- Use [Maja](https://gitlab.orfeo-toolbox.org/maja/maja) to process Sentinel L1C data into L2A

Once finished, the goal is to orchestrate all those elements into a nice XML->high resolution imagery

[Available on github](https://github.com/jollie-fin/topo2photo)

#### Earth2mars

I got this idea after participating to [Robot Uprising 2020](https://robotuprising.fi/). The competition revolved around programming a robot to solve some mazes and puzzles.

Soon after, I got this interesting idea :

- The competition was streamed on twitch, but to be fair, it was also a bit boring to watch. What is thrilling is programming the robot, not just watch them
- Why not give control of a robot to the twitch chat ?

It was my first try at controlling a robot from _The Internet_

##### Stack

I had a Discord bot running on an RPI. It was looking for specific keywords the players would write on a specific channel, such as :

- Go forward by x amount
- Turn
- Grab
- Lift

Upon recognition, it would transmit instructions to a micropython firmware running on a EV3 LEGO brick through an ssh connexion

- The robot would then move accordingly

A webcam would then stream a videofeed back to my nieces

[Available on github](https://github.com/jollie-fin/earth2mars)

### Rust

#### Small prototype for a code challenge

[Available upon request](mailto:)

### Go-lang

A thread-based modular synthesizer, as a showcase of Go-lang

This project was, first and foremost, a way to teach myself Golang with its special approach to thread and communication

I see a parallel between Go's channels and wire in a modular synthesis. They both transmit a signal between A and B, that is produced on one side, and consummed on the other

[Available on github](https://github.com/jollie-fin/sound-of-procrastination)

### Web development

I don't have _nice-to-share_ project, but I can compile some snippets upon request

</details>

## Educational experience

I had the privilege to follow a theory-oriented computer science master. Of note, we have studied :

- mid-level linear algebra (Cayley–Hamilton theorem, vectorial spaces, non R based linear algebra, group...)
- distributed systems (OpenMPI, spontaneous election, graph discovery...)
- theory of compilation (Lex, Yacc, continuation transpiling, functional programming...)
- formal proof (CoQ)
- algorithms (linear programming, ACM, complexity analysis, FFT)
- theory of networking (packet exchange, Aloha protocol, jitter, latency...)
- physics (electro-magnetism, mechanics, thermodynamics...)

(Please note that some unforeseeable circumstances have prevented me from actually getting the master diploma. So I am only a bachelor, officially)

## Keywords

C, C++, Qt, C++17, Rust, Go, PHP, python, micro-python, ASM, embedded, Agile, low-level, FPGA, SQL, Kicad, PCB design, typescript, ReactJS, Puppeteer, wireshark, python, django, memoization, concurrent programming, linear algebra, mixed linear programming, optimization, firmware, arduino, SPI, I2C, 5G, TCP, DSP, Fourier transform, entrepreneur, start-up, OpenMP, OpenMPI, LeX, Yacc, robotics
