# Literature on the vehicleCAPTAIN
This page holds information on how to cite the vehicleCAPTAIN toolbox and on the suggested usage of abbreviations and naming.

Additionally, we provide sources for literature validating the platform, as well as noteworthy documented contributions.

## Citations
If you use the vehicleCAPTAIN toolbox for your work, please cite the main github [repository](https://github.com/virtual-vehicle/vehicle_captain).

If you want to cite the vehicleCAPTAIN toolbox in literature, please cite [this](https://link.springer.com/chapter/10.1007/978-3-031-54049-3_11) book chapter. This chapter discusses the development of the vehicleCAPTAIN toolbox.

Feel free to also cite related literature listed below.

## Naming
For cooperate design, please adhere to the suggestions for [naming](doc/NAMING.md).

## Validation
Publications that validate parts of the vehicleCAPTAIN toolbox will be added when finalized.

### 2024: Vehicle Communication Platform to Anything-VehicleCAPTAIN
**Citation**: Pilz, C. (2024). Vehicle Communication Platform to Anything-VehicleCAPTAIN. In: Karner, M., Peltola, J., Jerne, M., Kulas, L., Priller, P. (eds) Intelligent Secure Trustable Things. Studies in Computational Intelligence, vol 1147. Springer, Cham. https://doi.org/10.1007/978-3-031-54049-3_11

**Abstract**: Vehicle-to-everything (V2X) is on the verge of being integrated as an integral part of modern vehicles. However, the battle for the final V2X radio technology is still not decided, and the available message standards are complex, hindering research and development. Hence, in our work, we provide a toolbox for early-stage development within V2X, called vehicle communication platform to anything (vehicleCAPTAIN). The vehicleCAPTAIN toolbox comprises (i) a set of software that mitigates the need to adapt for different V2X hardware vendors by decoupling and simplifying implementation, (ii) a set of libraries that supports encoding and decoding of messages, and (iii) a set of software bindings to enable development with ROS2. All software is provided as free and open source (FOSS). Within this work, we prove the functionality of the toolbox with classic end-to-end tests, as well as Qosium, a quality-of-service testing application. Finally, we highlight the applicability and benefits of the vehicleCAPTAIN toolbox for early-stage V2X research and development.

**URL**: https://link.springer.com/chapter/10.1007/978-3-031-54049-3_11

**TL;DR**: this paper discusses the development of the vehicleCAPTAIN toolbox

### 2023.08.01: Collective Perception: a Delay Evaluation With a Short Discussion on Channel Load
**Citation**: C. Pilz et al., "Collective Perception: a Delay Evaluation With a Short Discussion on Channel Load," in IEEE Open Journal of Intelligent Transportation Systems, doi: 10.1109/OJITS.2023.3296812.

**Abstract**: Automated vehicles and vehicle-to-everything (V2X) communication open the window for sharing of sensor data. This paper aims to provide a systematic view of the delay chain involved. We implemented collective perception (CP) into two street legal automated driving demonstrators (ADDs) to provide insight into the components’ delay. The implementation allowed us to gather highly accurate Quality of Service (QoS) measurements for V2X communication in practical field environments and to gather a set of delay measurements for a working CP system, accompanied by scalability discussions. The results provide a basis for evaluating the delay impact of single components and the applicability of CP use cases from the perspective of time advantage.

**URL**: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10198493&isnumber=8957420

**TL;DR**: this paper confirms the applicability of the basic delay behavior of the vehicleCAPTAIN routing core and connected elements of the vehicleCAPTAIN toolbox.


## Documentation of Implementations
This chapter lists implementations of the vehicleCAPTAIN toolbox that where published in some form.
[comment]: <> (If someone has done implementations, e.g. bachelor/master thesis, it can be linked here)

### 2024: Performance Assessment Framework for Vehicle-to-Everything as a Sensor (V2XaaS)
**Citation**: Pilz, C. (2024). Performance Assessment Framework for Vehicle-to-Everything as a Sensor (V2XaaS). Doctoral Thesis. Graz University of Technology.

**Abstract**: Vehicle-to-Everything (V2X) communication can extend the Field of View (FoV) of a traditional
Automated Vehicle (AV) by extending the perception of onboard sensors with shared informa-
tion. This information can be active speed limits, accident notifications, or perception data
shared between vehicles. There are no limits on what can be shared. In fact, the community
encourages sharing information about one’s surroundings.
However, when using Vehicle-to-Everything–as–a–Sensor (V2XaaS), the Automated Driv-
ing (AD) stack in an AV must be aware of the currently provided quality of the information
shared via V2X communication to avoid degradation of overall performance and especially
safety. Specifically, oversharing information leads to loaded communication channels, and
sharing data with low accuracy may be useless.
Related research provides only in part an overview of the components involved V2XaaS
and their performance, let alone a metric to rate the quality of individual influencing factors
or the overall quality. Specifically, related research in the AD domain gives the impression of
primarily focusing on improving perception results and assuming that the V2XaaS framework
does not affect the quality of the data available. In contrast, the V2X domain gives the
impression of expecting perception data to be perfect and only having to deal with wireless
communication characteristics.
The work in this thesis aims to provide a sound foundation for integrating and evaluating
V2XaaS systems. This includes an overview of the components involved, the performance
linked to each component, and a metric to rate the Quality of Service (QoS) provided by the
surrounding V2X field.
The work defines the components of V2XaaS and their key performance indicators. This
analysis led to the setup of a demonstrator system for laboratory and field experiments that
was used to perform an extensive systematic analysis of components. This analysis aims to
provide well-founded ranges for the performance indicators, focusing on accuracy and delay.
Those well-founded areas are then used to create a metric rating the QoS of the surrounding
V2X field.
The resulting metric allows the AD system of an AV to adapt its behavior depending on
the quality of the surrounding V2X field, which in turn allows it to keep up or even improve
comfort, performance, and safety.
With the systematic evaluation, we aim to ease and broaden the application of V2XaaS.
Even more, the contributions we made allow AD systems to have an indicator of the QoS that
V2XaaS can provide at a specific moment.

**URL**: publication pending (research gate and TU Graz)

**TL;DR**: this thesis summarizes the development and usage of the vehicleCAPTAIN toolbox as part of a framework to assess the performance of V2X-as-a-sensor.

### 2023.09.24-28: Positional Accuracy Provided by State-of-the-Art Cooperative Awareness and Collective Perception
**Citation**: C. Pilz, A. Steinberger, L. Kuschnig, M. Schratter, T. Neumayr and G. Steinbauer-Wagner, "Positional Accuracy Provided by State-of-the-Art Cooperative Awareness and Collective Perception," 2023 IEEE 26th International Conference on Intelligent Transportation Systems (ITSC), Bilbao, Spain, 2023, pp. 541-548, doi: 10.1109/ITSC57777.2023.10422653.

**Abstract**: Cooperative awareness (CA) and collective perception (CP) deal with the exchange of perception data within vehicle-to-everything (V2X). The achievable and needed accuracy is not yet analyzed in detail. The baseline for accuracy is the data from simulations, recommendations provided by standards, or various perception datasets with a disconnect between localization accuracy and perception accuracy. We extended a state-of-the-art (SOTA) automated driving (AD) platform with CA/CP functionality in our work. We then deployed it on two street-legal AD demonstrators (ADDs) and did an extensive field test to acquire data. With the data, we show the achievable accuracy of SOTA systems and discuss the requirements for future implementations.

**URL**: https://ieeexplore.ieee.org/document/10422653

**TL;DR**: the work in this paper uses the vehicleCAPTAIN toolbox for exchange of CAMs and CPMs to extend the onboard field-of-view (FoV) of an automated vehicle (AV).

## Additional Media
Additional media referencing the platform
[comment]: <> (Feel free to add sources, where the vehicleCAPTAIN toolbox is mentioned)

### 2024.03.25: Winner of the Styrian Innovation Award (German Source)
AC Styria, Wolfgang Wachmann, "vehicleCAPTAIN toolbox“: Smarte Fahrzeug-Kommunikationsplattform gewinnt Innovationspreis Steiermark 20204", Presseinformation.

**URL**: https://acstyria.com/wp-content/uploads/VIRTUAL-VEHICLE_Presseinformation_vehicleCAPTAINtoolbox_Innovationspreis.pdf

**TL;DR**: the vehicleCAPTAIN toolbox won the _Styrian Innovation Award_.


### 2023.11.xx: Heise Medien (German Source)
Heise Medien (German Source), Dirk Bongart, "IT-Unternehmen in Österreich stellen sich vor", eine Themenbeilage von Heise Medien, Vehicle to Everything, Autonomes Hupen, p.14.

**URL**: https://www.mittelstandswiki.de/pdfviewer/itk-unternehmen-aus-oesterreich-stellen-sich-vor-ausgabe-2023-01/

**TL;DR**: the vehicleCAPTAIN toolbox is mentioned as platform for R&D in the V2X domain.