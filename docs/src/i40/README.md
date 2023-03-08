
<audio autoplay="autoplay" controls="controls">
<source src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1368538705&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true" type="audio/mp3" />
seu navegador não suporta HTML5
</audio>

## Simulaton-based approaches applied in the context of Industry 4.0

One of the relevant topics for I4.0 is simulation, simulation is a fundamental technique for analyzing behavior of complex systems. Simulation can be used to minimize the cost associated with it. The development of experiments with the current system, to observe the behavior of processes in the real world, or with the construction of a physical model.

Advantages of using simulation approaches include: running tests quickly and cheaply without interrupting the actual system (risk-free shipping
environment), compressing or expanding time for a particular observation, and use of animation (visualization of dynamic systems) to facilitate model communication and validation.

There are different approaches to simulation.

<div align="center">

![Alt text](/SimulationI40.drawio.png "Simulation 4.0")

</div>

The figure above provides an overview of these approaches in the I4.0 context and bellow we will detail each of these concepts.

[[I want a free clas - schedule](https://calendly.com/jackson-veiga-1/30min)]

### Agent-Based Modeling and Simulation (ABMS)
> is considered a relatively new approach to model complex systems composed of interactive and autonomous agents. ABMS is defined as a set of elements (agents) characterized by attributes that interact with each other through "appropriate rules" for a given environment.
The agent is a complex software unit capable of operating autonomously and following a set of rules.
ABMS has an important participation as a model to achieve CPS and simulation i4.0.

### Discret Event Simulation (DES)
> It is defined as "state variables that change only at the discrete points in time when the event occurs". The event consists of the occurrence that changes the state of the system. The system state variable represents all the information needed to describe the behavior of the system at a given point in time. DES is process-oriented, developed primarily using process flowcharts, and operates at discrete times. The level of abstraction of DES models is generally medium to low.

### System Dynamics (SD)
> is a continuous simulation approach to analyzing dynamic systems over time, using stock and flows and feedback loop diagrams and differential equations to represent systems component relationships. The use of stock and flow diagrams implies a quantitative approach (rigid modeling), while the qualitative approach, also called light operations research, involves only the use of influence diagrams (feedback loop).

### Virtual Reality (VR)
> is a virtual experience in which a user is immersed in a responsive virtual environment. This refers to a set of ICT technologies (ie, expression technology, interaction creation technology, authoring technology, collaboration technology) that allow the user to experience a virtual environment in an experimental simulation environment.

### Augmented Reality (AR)
> is a set of technologies (e.g., capturing device, display devices, interaction device, tracking system) that allows the direct or indirect view of the real-time physical world environment to be augmented (i.e., enhanced) by adding of virtual computers.

### Artificial Inteligency (AI)
> AI-Simulation is a domain of computer science related to the simulation of intelligent behavior in computers. Its subfields include machine learning, deep learning, natural language processing, computer vision, cognitive computing. AI can also be described as a set of techniques for modeling and simulating environmental systems, which includes artificial neural networks, fuzzy models, reinforcement learning, automata and metaheuristics.

### Petry Net Simulation (PT)
> is a graphical and analytical discrete event simulation used to model and simulate flexible manufacturing systems. The PN formalism is suitable for representing concurrent, asynchronous, distributed, parallel and stochastic systems. In general, a PN consists of four elements: places — represented by circles, transitions — represented by rectangles, edges — represented by direct arrows, and tokens — represented by small solids (Pishing et al., 2018).

### Hybrid Simulation (HS)
> combination of simulation with optimization approaches, ie simulation-optimization. there are four types of hybridization: sequential — the output of one model is the input for another model; enriching - restricted use of another method by a dominant; interaction — models interact cyclically without domain; and integration — where it is not easy to distinguish the beginning of one method and the end of another method. There are different types of HS models in the literature, such as DES-ABMS (Farsi et al., 2019), SD-ABMS (Nassehi & Colledani, 2018), DES-VR (Turner et al., 2016), ABMS-Data Science ( Houston et al., 2017), Simulation-Big data (Vieira et al., 2019b), PN-AI (Drakaki & Tzionas, 2017) and multilevel simulation (Delbrügger et al., 2019)

### Digital Twins (DT)
> refers to the digital representation of an ical system and the seamless integration between physical and digital spaces (Cimino et al., 2019). DT is commonly defined as “a multiphysics, multiscale, probabilistic, ultra-fidelity simulation that reflects, in a timely manner, the state of a matching twin in historical data, real-time sensor data, and physical model”.

> It was initially developed within the aerospace industry than extended to the manufacturing field. DT is a hybrid approach, built into four levels:
geometry, physics, behavior, and rule:  The first two levels involve mainly kinematics and geometric simulation, also referred to as continuous simulation.  Levels three and four involve different simulation approaches, such as DES, ABMS, and AI techniques

### Virtual Commissioning (VC)
> VC is a digitization method to accelerate the commissioning of a new production process through an environment. Known as a test method that uses simulation models and emulated controllers during the development and validation of new manufacturing systems. VC integrates different technologies such as 3D CAD, DES and PLC. DT models were also incorporated into the commissioning process. The DT models, along with the PCL design, provide an accurate view of how the design of automated systems will perform prior to physical commissioning when hardware and PLCs are put together.

[[I want a free clas - schedule](https://calendly.com/jackson-veiga-1/30min)]


## Pratical Guild to join in Industry 4.0 - I4.0

I4.0 sought to unify and standardize different technologies so that traditional systems reach the concepts of "Advanced Manufacturing". The main aspects for migrating these systems deal with Cyber ​​Physical integration and virtualization of the different components so that they can be perceived in the virtual world.

>The virtualization of assets is standardized with concepts of AAS - Asset Administration Shell according to the guidelines of the I4.0 initiatives.
AAS is a concept that enables the Digital Twin - GD, in which it is a virtual copy of physical assets and components for bilateral communication of manufacturing objects.

The GD enables a better understanding of physical objects through digital models, the novelty will be that now there is an exchange between physical assets and virtual objects - virtual communication, as well as horizontal communication between different applications of the I4.0 systems.

>Virtual Objects - I4.0 Assets are enabled with the AAS concepts that standardize the different components of I4.0 - I4.0C.
With the transformation of traditional systems, I4.0 virtual systems can reach the factory of the future - Advanced Manufacturing Systems.
Now that we understand the potential of using AAS for asset virtualization and the use of digital applications, we can see the existing challenges for migrating from traditional manufacturing systems.

The current - traditional systems must be equipped with technologies and tools to achieve the GD.

>In this work, we will explore a methodology with defined steps and stages for the migration of traditional systems until we reach the AAS models, finally, a case study is conceived seeking to conceptualize the new approaches of digital models with the concepts of I4.0.


## Methodology used to define the method steps

### Legacy Systems

Traditional manufacturing systems were called in this article Legacy Systems - specifically designed to meet individual demands. Thus, legacy systems have their own architectures and specific production systems.

> In traditional manufacturing systems, distributed control systems are commonly used, supported by Programmable Logic Controls (PLCs) and basic programming languages ​​such as Ladder, Blocks, List. As mentioned in the introduction to this material, these systems need to be transformed into digital models to reach I4.0.

> The first stage of this work classifies an integration proposal that allows interoperability in unified languages ​​of the I4.0 components. The I4.0 standards describe the RAMI 4.0 - Reference Architecture Model for I4.0, being a three-dimensional model that contains layers, life cycle and traditional manufacturing hierarchy standard.

> The interoperability of traditional assets is possible using the AAS specified in I4.0. Before starting the manipulation and vision of the AAS, we will study models and architectures to connect the physical part (Traditional System) with the virtual components (Connected World - I4.0).

[[I want a free clas - schedule](https://calendly.com/jackson-veiga-1/30min)]

### First Step - Integration of Legacy Systems

RAMI 4.0 addresses guidelines for developing applications in the I4.0 context. Legacy systems that use classic control architectures need to be transformed into virtual models with AAS support.

> Currently, different works propose the gradual migration of legacy systems, for example the IMPROVE or PERFoRM projects, however it is observed that these present specific proposals or a very generic architecture that must be followed to design the models for each use case.

> Taking into account the approaches and concepts mentioned, the first stage of the methodology of this work deals with the "INTEGRATION" of legacy systems from manufacturing to AAS. In this sense, we will now discuss the means for interface, the protocols that should be used, such as OPC-UA.

We will then follow the layered model of RAMI 4.0 to meet the standardization requirements of the languages ​​of the legacy system, the I4.0 language - OPC-UA. Thus physical assets will now be considered I4.0 - I4.0C components.

> I4.0C must be unique, identifiable and meet communication requirements. An I.4.0 according to the descriptions of I4.0 can range from a sensor to an entire work plant, therefore, in this study we will consider I4.0C workstation modules, such as: Robotic Arm, Handling Station, Packing Machine

[[I want a free clas - schedule](https://calendly.com/jackson-veiga-1/30min)]

#### Details of RAMI 4.0 Layers for communication migration from Legacy Systems.

The I4.0 Guidance X document simplifies the layers responsible for applications and integration tools for exchanging data between the physical and virtual element of the AAS.

> The OPC-UA is used as a standardization protocol for the different languages ​​of legacy systems. Allowing data exchange between these layers uses standard XML or JSON protocol.

#### Framework for transforming legacy assets into AAS

In this study, we will use a basic structure of AAS that exchange data with legacy devices. Thus we consider: a) Active Workstation; b) Asset Product; c) Active Integrator.

> The workstation actually deals with the existing legacy system, the active product refers to hardware inserted in the control system that collects data from the flow of the part in the workstations, while the active integrator is also a second board containing the OPC tools -UA and XML models for collecting and converting data to virtual models, finally there is a computer containing the I4.0 framework with images of each physical asset using AAS concepts (we will not detail this in this first step).

> The PC asset deals with orchestrators and frameworks containing AAS, the "Integrator" asset allows connecting heterogeneous field protocols via OPC-UA from workstations and product assets, enabling the flow of data between the physical layer and the functional layer - containing the AAS.

> Finally, in the lower part of the figure, the industry's legacy control systems were designed. Note that these are equipped with a port for OPC-DA communication via Ethernet TCP/IP. Thus, in the Integrator, the Matrikon-OPC tool was used for the communication of the assets - Station.

> Figure-x is about the simplified flow of information between station assets, integrator asset and PC-AAS asset.

[[I want a free clas - schedule](https://calendly.com/jackson-veiga-1/30min)]

#### Simulation for Interoperability of Traditional Systems using OPC-UA

Unified Architecture (OPC UA) is a service-oriented, platform-independent architecture that integrates all the functionality of classic OPC-UA.

> Open Platform Communication (OPC) is a series of open standards and applications developed by the OPC Foundation, an international organization with a goal to develop a platform independent, secure and interoperable data exchange standard for automation. In 2008, the OPC Foundation published the Unified Architecture, which has the potential to be an integration standard for M2M, as a communication protocol defined by IEC62541.

> The Unified Architecture (OPC UA) server can host the AAS and provide a semantic data space for each asset. For this, one can determine the specific data, identification, data capacity with its metadata, in the domain of that architecture.

> Physical connection is the first phase of a Plug and Produce arrangement where the I4.0 component needs to be connected to a production system via wired or wireless methods. The connection process allows an asset to be identified by a Plug & Produce system to initiate automated process configuration.

> The second step will be the generation of the OPC UA configuration file after creating the information model. It incorporates the information model for the field device, which encompasses the OPC UA Base Node Set, device mate specific node set, and the device information model.

The framework protocols of OPC UA communication presented a structure of messages and characteristics of data transport that met the needs of integration between several manufacturers that made up the autonomous automated manufacturing cell.

> PLCs (Programmable Logic Controllers) are an important control element in manufacturing configuration systems and there are many experts in the market who can interface and program such industrial computers. However, very few of them know how to connect PLCs to the IT world (e.g. cloud, augmented reality, mobile or web apps, etc.).

> These devices can use wireless communication over standardised network protocols to communicate relevant data from each physical system back to a central server for monitoring and analysis. The results of this analysis can then be relayed back to the physical system to enable more autonomous operation, increase accuracy, improve maintenance and improve uptime. But the focus of this work is to achieve integration with AAS.

[[I want a free clas - schedule](https://calendly.com/jackson-veiga-1/30min)]

For a practical demonstration of the integration of traditional industry systems to virtual components, we present the basic theoretical aspects and software tools that are used in educational case studies:

> a) The Codesys or SoftPLC software will allow the simulation of the traditional PLC;
> b) OPC Communicator - allows the generation of publish/subscriber messages
> c) UA-Gateawy - used for standardization of OPC-UA protocols
> d) OPC-UA Expert or NodeRED - for reading data and creating standard UA models.

The studies deal with the control of systems, an environment for running the control system is needed:

 > We will use a computer to simulate the PLC Control. As in [2] industry-PC can be turned into an automation system by a PLC runtime
system, also known as a runtime system, which allows you to cyclically automate and control technical operations, process sequences, and similar procedures

### Second Step - Modeling of the virtual part of the AAS.

After enabling the traditional systems to be perceived by the new I4.0 systems, it is necessary to design the AAS models.

 * In this step, we use the concepts of the I4.0 guidelines:

> An AAS can be a physical asset or not, for example, processes, products, stations, controllers, resources, drawings, etc. In this study we will focus on the standardization of resources using AAS. The Asset Administration Shell (AAS) is the composition of the "Asset" and the "Administration Shell", this one is conceived as a meta-model made up of different sub-models that describe the attributes of the asset - resource.

> The main parts of an AAS are the header - responsible for standardized identification and the body - which makes up the other sub-models of the asset's domain.

> The AAS comprises a minimal set of submodels that allowed the “asset” to perform a specific function.

 * A sub-model deals with specific aspects of the resource, for example:

 > means of communication, functionalities and services, standard identifiers.


 [[I want a free clas - schedule](https://calendly.com/jackson-veiga-1/30min)]

### Step Three - Integration of data from the traditional system with the virtual part of the AAS

Industry 4.0 has to provide horizontal, vertical and full integration and interoperability.

> This is not easy task due to the low level of flexibility of automation technology, high specificity of industrial assets and the lack of interoperability perability between heterogeneous systems.

> A major challenge will be the standardization of virtual assets focused on this work. It is noted that traditional manufacturing systems needed to comply with the new regulations for them to achieve interoperability and enable integration with their representation as a digital twin throughout its lifecycle.

We should keep an eye on the definitions and standards for smart manufacturing. Currently different models are proposed such as RAMI4.0, IIRA or SME.

> The Asset Administration Shell (AAS) of the German I4.0 initiative, was proposed by The German platform Industrie 4.0, which aims to describe a
electronically active in a standardized way, allowing for interoperability bility between different assets in a plant.


   [[I want a free clas - schedule](https://calendly.com/jackson-veiga-1/30min)]
   [Brief in Whatsapp](https://wa.me/+5511992451218)

### Step Four - AAS Construction Practice Test

Traditional environments are characterized by processes that cooperate to achieve a certain goal.

> The difference of traditional systems for i40 is that normally the engineering of these applications are static and pre-defined.
In I4.0 there is the life cycle axis in which the assets walk in different stages in the value chain.

* A comparison between traditional manufacturing and I4.0:

> In traditional systems, processes are designed
   a) Define engineering procedures
   b) The equipment is specified
   c) Work plan, standards and operations are defined
   d) Finally, the plant is implemented, prepared and delivered to the customer.

* In case of divergence, check all previous steps.

> At I4.0 we talk about the concept of Digital Twin - DG. This can be designed from the following steps:
   a) Define content and objectives
   b) Digital models are created to help specialists in planning. At this stage, the functions of the objects can be related to the resources.
   c) Electronic manufacturing catalogs are consulted, allowing the selection of equipment aspects.
   d) The simulation can be validated, automatic orders for equipment are generated, models and integration for digital operation are tested.
   e) Finally, the I4.0 models are generated at runtime, each component receives a "Ainistracao Shell"

After completing this step, these models are ready to communicate with traditional systems:

> Note two distinct life cycles. Thus, an architecture is needed that proposes how to integrate Los. Here we will stick to RAMI4.0. The standardization of these I4.0 components can be called I4.0C

   * How do I make an AAS?

   AAS is nothing more then the virtualization form of I4.0C.

   > This is made up of several submit them..

   > AAS allows the asset to realize different use cases for each specific application of traditional systems

   Here we will mention some use case examples, so we will stick to one of them to better exemplify the problem.


* The first use case presents the implementation of AAS in an industrial setting. The use case considers a plant composed of a robotic arm, a grinding machine and a layer of semantic harmonization [1]

> The first use case features the creation of two AAS - Robotic Arm and Grinding Machine. The interoperability between these virtual assets is tested using a semantic integrator.

> This demonstrator was based on a SainSmart Robotic Arm11, a Raspberry Pi and a controller board for the Adafruit12 servants

* At the hardware control level we have:

> The robotic arm has 4 axes controlled by four servants. The function of the Raspberry Pi is to control the movement, through a standard keyboard connected by USB, and to serve the information model of the RoboticArm. The keystrokes will be transformed into the appropriate signals for the servants through the Adafuit Servo Hat card. This small board is connected above the Raspberry Pi and adds the necessary interfaces to control the servos via pulse-width modulation (PWM) signals.

> At the AAS level were designed:

* Robotic Arm: submodels for Identification, Documentation and Condition Monitoring.

 > Submodel Documentation: manufacturer, model, serial number. The documentation
submodel contains information about the files that document the asset (data sheet, maintenance manual).

* Condition Monitoring submodel:
 > properties like AxisType and which are relevant to our demonstrator like such as the movement profile and the actual position of each axis of
the RoboticArm

#### AAS implementation

   [Brief in Whatsapp](https://wa.me/+5511992451218)
   [[I want a free clas - schedule](https://calendly.com/jackson-veiga-1/30min)]

### Step Five - Bonus application development for data exchange between AAS.

   [Brief in Whatsapp](https://wa.me/+5511992451218)
   [[I want a free clas - schedule](https://calendly.com/jackson-veiga-1/30min)]



[1] Towards an Asset Administration Shell scenario: a use case for interoperability and standardization in Industry 4.0
[2] Educational Case Studies for Pilot Engineer 4.0 Programme: Monitoring and Control of Discrete-Event Systems Using OPC UA and Cloud Applications

[[I want a free clas - schedule](https://calendly.com/jackson-veiga-1/30min)]
