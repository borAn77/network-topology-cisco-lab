{\rtf1\ansi\ansicpg1252\cocoartf2867
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;\f1\froman\fcharset0 Times-Roman;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Cisco Packet Tracer \'96 Multi-Site Network Topology\
\
## Network Topology\
\
![Network Topology](topology.png)\
\
This project demonstrates the design and configuration of a multi-site enterprise network using Cisco Packet Tracer.\
\
\pard\pardeftab720\partightenfactor0

\f1 \cf0 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 The topology simulates three geographically separated offices connected through a routed WAN backbone.\
\
## Network Sites\
\
The network consists of three branch locations:\
\
- London\
- Wroclaw\
- York\
\
Each site includes a Local Area Network (LAN) with multiple client computers connected through a switch to a local router.\
\
## Devices Used\
\
### Routers\
- Router0 \'96 London gateway router\
- Router1 \'96 Wroclaw gateway router\
- Router2 \'96 York gateway router\
- Router3 \'96 Core router\
- Router4 \'96 Core router\
- Router5 \'96 Core router\
- Router6 \'96 Core router\
\
### Switches\
- 3 access switches (one per site)\
\
### End Devices\
- 18 PCs total\
\
London LAN\
- PCIT-1 to PCIT-6\
\
Wroclaw LAN\
- PCSALE-1 to PCSALE-6\
\
York LAN\
- PCMARKET-1 to PCMARKET-6\
\
## Network Architecture\
\
Each branch follows this structure:\
\
PCs \uc0\u8594  Switch \u8594  Local Router \u8594  WAN Core Network\
\
The WAN backbone is formed by interconnected routers (Router3, Router4, Router5, Router6), allowing communication between the different branch offices.\
\
## Key Concepts Demonstrated\
\
- Multi-site network design\
- Router-to-router WAN connections\
- LAN segmentation\
- Routing between different network segments\
- Enterprise-style topology structure\
\
## Tools Used\
\
- Cisco Packet Tracer\
- Cisco 1941 routers\
- Cisco 2960 switches\
\
## Author\
\
Boran Gedik}