# SRS-of-Online-shopping-Application
   Detail study of online shooping app
   by #AmitPethkar
Software Requirement Specification(SRS) for
Online Shopping System(OSS)
1.	Introduction
  1.1  Purpose:
This document is meant to delineate the features of  OSS, so as to serve as a guide to the developers on one hand and a   software  validation document  for the prospective client on the other.
The Online Shopping System (OSS) for electronics item shop web application is intended to provide complete solutions for vendors as well as customers through a single get way using the internet.It will enable vendors to setup online shops, customer to  browse through the shop and purchase them   online without  having to visit the shop physically. The administration module will  enable a  system  administrator to approve and reject requests for new shops and maintain various lists of shop category.
  1.2 Scope:
This system allows the customer’s to maintain their cart for add or remove the product over the internet.
  1.3  Definitions:
OSS- Online shopping System (for electronics item shop)
SRS- Software Requirement Specification
GUI- Graphical User Interface
Stackholder- The person who will participate in system 
Ex. Customer, Administrator, Visitor etc.
1.4	References:
1.5	Overview:
This system provides an easy solution for customers to buy the product without going to the shop and also to shop owner to sale the product.
This proposed system can be used by any naïve users and it does not require any educational level,experience or technical expertise in computer field but it will be of good use if user has the good knowledge of how to operate a computer.
2.Overall Description:
The   Online   Shopping   system   (OSS)   application   enables vendors to set up online shops, customers to browse through the shops,  and  a system  administrator  to  approve  and  reject requests for new shops and maintain lists of shop categories. Also  the  developer  is  designing an  online  shopping  site  to manage the items in the shop and also help customers to purchase them online without visiting the shop physically.The online shopping system will use the internet as the sole method for selling goods to its consumers.
       2.1 Product Perspective:
This product aimed toward a person who don’t want to visit
the shop as he might don’t get time for that or might not interested in visiting there and dealing with lot of formalities.
       2.2 Product Functions:
OSS should support this use case:
 
      2.3 User Characeristics:
            User should be familiar with the terms like    login,register,order system etc.
     2.4 Principle Actors:
2	Principle Actors are Customer and Administrator.
     2.5 General Constraints:
          A full internet connection is required for OSS.
    2.6  Assumptions and Dependencies :
         Working of OSS need Internet Connection.
3.	Specific Requirements:
  
3.1	Functional Requirements:
      This section provides requirement overview of the system.
      Various functional modules that can be implemented by the system     will be -
3.1 Description:
3.1.1	Registration
If customer wants to buy the product then he/she must be
registered, unregistered user can’t go to the shopping cart.
3.1.2	Login
Customer logins to the system by entering valid user id and password for the shopping.
3.1.3	Changes to Cart
Changes to cart means the customer after login or registration can make order or cancel order of the product from the shopping cart.
3.1.4	Payment
           In this system we are dealing the mode of payment by Cash.We will 
        extend this to credit card,debit card etc in the future. 
3.1.5	Logout
                                         After ordering  or surfing for the product                             customer has to logout.                
3.1.6	Report Generation
After ordering for the product,the system will sent one copy of the bill to the customer’s Email-address and another one for the system data base.
3.2	Non-Functional Requirements:
          Following Non-Functional Requirements will be there in the insurance to the internet:
(i)	Secure access to consumer’s confidential data.
(ii)	24X7 availability.
(iii)	Better component design to get better performance at peak time.
(iv)	Flexible service based architecture will be highly desirable for future extension.Non-Functional Requirements define system properties and constraints.
Various other Non-Functional Requirements are:
	Security
	Reliability
	Maintainability
	Portability
	Extensibility
	Reusability
	Compatibility  Resource Utilization
3.3	Performance Requirements: 
           In order to maintain an acceptable speed at maximum number of uploads allowed     from a particular customer as any number of users can access to the system at any time.
Also the connections to the servers will be based on the attributes of the user like his location and server will be working 24X7 times.
3.4	T  e  c  h  n i  c  a l I   s  s  u  es:
This system will work on client-server architecture. It will require an internet server and which will be able to run PHP application. The system should support some commonly used browser such as IE, mozzila firefox,chrome  etc.
4.	Inter f  ace   
  Re  q  u i  re  m  e  nt:
Various interfaces for the product could be-
1). Login Page
2). Registration Form
3). There will be a screen displaying information about product that the shop having. 4). If the customers select the buy button then another screen of shopping cart will be opened.
5). After ordering for the product,the system will sent one copyof the bill to the customer’s Emailaddress
Software Interface:
1.Operating System:Windows7 Ultimate which supports networking.
2.JAVA development toolkit.
 
Hardware Interface:
Hardware requirements for insurance on internet will be 	same for both parties which are as follows:
Processor:Dual Core
RAM:2 GB
Hard Disk:320 GB
NIC:For each party
Communication Interfaces:
         The two parties should be connected by LAN or WAN for the communication purpose.
       SENDER    SENDER	               Communication channel        RECEIVER
5	.System Design Specification:
5.1	Architecture Design:
               5.1.1 Data Flow Diagram(DFD):
It is a way of representing system requirements in graphical  form;this led to modular design.A DFD describes a data flow(logical) rather than how they are processed.So they do not depend upon 
software,hardware,data structure or file organization.It is also known as ‘bubble sort’.
A DFD is a structured analysis and a design tool that can be used for flowcharting in place of ,or in association with ,information-oriented and processoriented system flowcharts.
A DFD is considered as an abstract of the logic of information-oriented or process-oriented system flowchart.The four basic symbols used to construct data flow diagrams are-
                               A rectangle represents a data source or destination.
                               A directed line represents flow of data.
                           An Oval represents a process that transforms into                                                                
streams.
                      	    An Open ended rectangle represents storage. 
The points at which data is transformed are called as nodes.The principle processes that take place at nodes are:
1.Combining data streams
2.Splitting data streams
3.Modifiying data streams
Databas e
                
CONTEXT ANALYSIS DIAGRAM(CAD)
      	 
 
 
 
 
E-R DIAGRAM
 
 
 
 

