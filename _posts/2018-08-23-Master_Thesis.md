---
layout: post
title:  "Master Thesis: Convolutional Neural Network Quantisation for Accelerating Inference in Visual Embedded Systems"
date:   2018-08-23 12:19:24 +0100
categories: kth eit master-school thesis
---
# Convolutional Neural Network Quantisation for Accelerating Inference in Visual Embedded Systems
> Independent thesis Advanced level (degree of Master (Two Years)), 20 credits / 30 HE credits

[[Link to record](http://urn.kb.se/resolve?urn=urn:nbn:se:kth:diva-240404)]

* Jan 2018 – Aug 2018
* _BitSim AB, KTH, EIT Digital Media Technology_ 
 


* **Series**: TRITA-EECS-EX ; 2018:581
* **National Category**: Engineering and Technology
* **Identifiers**
    * URN: urn:nbn:se:kth:diva-240404
    * OAI: oai:DiVA.org:kth-240404
    * DiVA, id: _diva2:1272130
* **External cooperation**: BitSim AB
* **Supervisors**: Wu, Hanwei
* **Examiners**: Flierl, Markus


## Abstract [sv]
Framstegen inom djupinlärning har gjort det möjligt att uppnå många datorvisionsuppgifter med hög noggrannhet. För att uppnå sådana prestationer har neurala nätverk utformats gradvis med djupare struk- turer. Även om denna utvecklingsmetod har lett till att överträffa kom- plexa uppgifter, har det också medfört en ökad efterfrågan på höga beräkningsresurser. Samtidigt har det uppstått ett behor av att utfö- ra djupinlärnings tekniker på begränsade resursenheter, vilket kräver lokal databehandling och förmåga att bearbeta vid kanten.

Nätverks reduktion är ett genomförbart tillvägagångssätt för att åt- gärda problem och förbättra djuplärares prestanda på inbyggda sy- stem och lågt resurskrävande enheter. I synnerhet är nätkvantisering- en föreslagen som en mångsidig och effektiv metod för nätverksre- duktion. Det möjliggör tillnärmning av neurala nätverks parametrar och behandlingsenheter, vilket accelererar exekveringstiden utan nog- grannhet förlust. Algoritmer för nätverkskvantiseringsresultat kom- pletterande med andra nätverksreduceringstekniker och kan applice- ras på redan utformade modeller.

Studien av nätkvantisering i detta arbete måste införas som ett led i ett projekt i utveckling av ett visuellt inbyggt system inom avancerad fö- rarassistanssystem. Detta projekt utnyttjar djupinlärning för att utföra objektdetekteringsoperationer i realtid. Vidare antas kvantisering för att påskynda inferringen av neurala nätverk specifikt på Zynq MPSoC plattformar.

Utvärderingar av olika kvantiseringsalgoritmer som är anställbara för detta arbete har lett till valet av en modell som är utformad för hårdva- ra: Vi har reproducerat en sådan modell utanför sitt inhemska ramverk och analyserat den i förhållande till andra modeller och på olika platt- formar. De uppnådda prestationerna visar kvantiteten som en nät- verksreduktionsteknik för en ökad acceleration. I synnerhet är kvan- tiseringsresultaten mycket effektiva inom inbyggda system för han- tering av heltal i stället för flytande punkter och dess lämplighet för förbättrade hårdvaruutformningar.

## Abstract [en]
The progress within the field of _Deep Learning_ has enabled the realisation of many _Computer Vision_ tasks with a high level of accuracy. To attain such achievements, neural networks have been designed gradually with deeper architectures. While this approach has lead to outperforming complex tasks, it also entailed an incremental demand for high computational resources. Oppositely, it has emerged at the same time the need of performing Deep Learning techniques on limited-resource devices, requiring local computing and ability of processing at the edge.

_Network reduction_ represents a feasible approach for addressing this issue and enhancing Deep Learning performances on embedded systems and low-resources devices. In particular, _network quantisation_ is here proposed as a versatile and effective method of network reduction, complementary with similar techniques and applicable on top of already-designed models.

The study of network quantisation in this work has to be inserted as part of a project consisting of the development of a visual embedded system within the field of _Advanced Driver-Assistance Systems_. This project exploits Deep Learning for performing object detection operations in real-time. Furthermore, quantisation is adopted to accelerate the inferring of neural networks specifically on _Zynq MPSoC_ platforms.

Evaluations of different quantisation algorithms employable for this work have led to the selection of a model designed on hardware. We have reproduced such a model outside its native framework and analysed it with respect to other models and on different platforms. The achieved performances prove the validity of quantisation as network reduction technique for the inference acceleration and suitable for improved hardware designs.

## Random pics from the project
![tinier-yolo2](/assets/img/2018-08-23-Master_Thesis/tinier-yolo.png)
![zynq-architecture](/assets/img/2018-08-23-Master_Thesis/zynq-architecture.png)
![preparation](/assets/img/2018-08-23-Master_Thesis/preparation.jpg)
