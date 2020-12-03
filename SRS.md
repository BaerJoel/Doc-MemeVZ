## Meme-VZ
<img src="memevzlogo new.png"/>

## Table of contents
- [Table of contents](#table-of-contents)
- [Introduction](#1-introduction)
    - [Purpose](#11-purpose)
    - [Scope](#12-scope)
    - [Definitions, Acronyms and Abbreviations](#13-definitions-acronyms-and-abbreviations)
    - [References](#14-references)
    - [Overview](#15-overview)
- [Overall Description](#2-overall-description)
    - [Use Case Diagram](#22-use-case-diagram)
	- [Technology Stack](#23-technology-stack)
- [Specific Requirements](#3-specific-requirements)
    - [Functionality](#31-functionality)
    - [Usability](#32-usability)
    - [Reliability](#33-reliability)
    - [Performance](#34-performance)
    - [Supportability](#35-supportability)
    - [Design Constraints](#36-design-constraints)
    - [Online User Documentation and Help System Requirements](#37-on-line-user-documentation-and-help-system-requirements)
    - [Purchased Components](#purchased-components)
    - [Interfaces](#39-interfaces)
    - [Licensing Requirements](#310-licensing-requirements)
    - [Legal, Copyright And Other Notices](#311-legal-copyright-and-other-notices)
    - [Applicable Standards](#312-applicable-standards)
- [Supporting Information](#4-supporting-information)


## 1. Introduction
The Software Requirements Specification (SRS) describes the following functions and quality requirements of the App MemeVZ in more detail.

### 1.1 Purpose
This SRS describes all specifications for "memeVZ". MemeVZ is a tribute to the popular SchülerVZ which was discontinued in 2013. It is a newer version for the younger generation to exchange ideas in a slightly different way. With MemeVZ we want to provide a new platform for viewing and sharing memes with people all over the world. Our goal is to reach the unreached with good qualtity content to laugh at. Everyone knows that a little laughter can cure anything.
“Find people that have the same kind of humor as you and you will never be alone” we say. To achieve all this we hold on to our Slogan: “Humor for humanity”.
In this document the usage of MemeVZ will be explained. Furthermore reliability, reaction speed and other important characteristics of this project will be specified. This includes design and architectural decisions regarding optimization of these criteria as well.

### 1.2     Scope
This software specification applies to the whole "MemeVZ" application. As already explained, MemeVZ is a tribute to the popular SchülerVZ which was discontinued in 2013. Share and display your favorite memes with a DH-wide community. Show what your humor is all about and make everyday life at dh a little bit funnier and amusing.

### 1.3     Definitions, Acronyms and Abbreviations

| Abbrevation | Explanation                            |
| ----------- | -------------------------------------- |
| SRS         | Software Requirements Specification    |
| UC          | Use Case                               |
| n/a         | not applicable                         |
| tbd         | to be determined                       |
| UCD         | overall Use Case Diagram               |


### 1.4     References

| Title                                                              | Date       | Publishing organization   |
| -------------------------------------------------------------------|:----------:| ------------------------- |
| [MemeVZ Blog](http://memevz.wordpress.com)    | 01.10.2020 | MemeVZ Team   |
| [GitHub](https://github.com/BaerJoel/MemeVZ-Pink-)              | 01.10.2020 | MemeVZ Team |

### 1.5     Overview
With MemeVZ we want to provide a new platform for viewing and sharing memes with people all over the world. Our goal is to reach the unreached with good qualtity content to laugh at. Everyone knows that a little laughter can cure anything.

“Find people that have the same kind of humor as you and you will never be alone” we say. To achieve all this we hold on to our Slogan: “Humor for humanity”.

## 2.           Overall Description
### 2.1 	Use Case Diagram
<img src="Use Case Diagram (4).png"/>

### 2.2 	Technology Stack

Project Managment:
*   Version management: Git
*   Repository manager: GitHub
*   project management: JIRA - Kanban

IDE:
*   Android Studio (Based on Android Studio)

*   Testing:


## 3.                  Specific Requirements
### 3.1     Functionality
This section explains the different use cases that can be seen in the UCD.
The scope until December contains the following points:
* Register/Login
* Upload pictures
* Show pictures
* Swipe picture

#### 3.1.1	Register/Login
Data to create a profile which can be edited later.

#### 3.1.2	Upload pictures
Upload images and store them in the database for a certain time.

#### 3.1.3	Show pictures
Images are displayed to other users. 

#### 3.1.3	Swipe picture
The Swipe function allows the evaluation of memes (Tinder).

### 3.2               Usability
MemeVZ should be a young social media platform, which are platforms like Facebook/Twitter and Tinder in one. These sites have been active for years, so we believe that our site is user friendly and easy to understand.

#### 3.2.1	No practice necessary
Our goal is to make the app as easy as possible to get a good feeling directly if you use it.

#### 3.2.1	tbd


### 3.3     Reliability
We assume that the app will run permanently.

#### 3.3.1          tbd
tbd

### 3.4     Performance
#### 3.4.1          App perfomance
The general goal when it comes to the performance of our app is that all Android phones (Android 8.1 Oreo) play the app smoothly and the posted pictures are displayed in an appropriate time. 

#### 3.4.2          tbd

### 3.5     Supportability
tbd
[This section indicates any requirements that will enhance the supportability or maintainability of the system being built, including coding standards, naming conventions, class libraries, maintenance access, maintenance utilities.]

#### 3.5.1          <Supportability Requirement One>
tbd
[The requirement description goes here.]

### 3.6     Design Constraints
Our goal is to create a simple user-friendly app. This should be possible through a simple and straightforward design. 

The supported Platforms will be:
Android 8.1 and higher
Java ? and higher

#### 3.6.1          Minimalistic
A simple design that everyone understand. That only works if you think minimalist.

### 3.7     On-line User Documentation and Help System Requirements
tbd
[Describes the requirements, if any, for on-line user documentation, help systems, help about notices, etc.]

### 3.8     Purchased Components
tbd
[This section describes any purchased components to be used with the system, any applicable licensing or usage restrictions, and any associated compatibility and interoperability or interface standards.]

### 3.9     Interfaces
tbd
[This section defines the interfaces that must be supported by the application. It should contain adequate specificity, protocols, ports and logical addresses, etc. so that the software can be developed and verified against the interface requirements.]

#### 3.9.1          User Interfaces
tbd
[Describe the user interfaces that are to be implemented by the software.]

#### 3.9.2          Hardware Interfaces
tbd
[This section defines any hardware interfaces that are to be supported by the software, including logical structure, physical addresses, expected behavior, etc. ]

#### 3.9.3          Software Interfaces
tbd
[This section describes software interfaces to other components of the software system. These may be purchased components, components reused from another application or components being developed for subsystems outside of the scope of this SRS but with which this software application must interact.]

#### 3.9.4          Communications Interfaces
tbd
[Describe any communications interfaces to other systems or devices such as local area networks, remote serial devices, etc.]

### 3.10     Licensing Requirements
tbd
[Defines any licensing enforcement requirements or other usage restriction requirements that are to be exhibited by the software.]

### 3.11     Legal, Copyright, and Other Notices
tbd
[This section describes any necessary legal disclaimers, warranties, copyright notices, patent notice, wordmark, trademark, or logo compliance issues for the software.]

### 3.12     Applicable Standards
tbd
[This section describes by reference any applicable standard and the specific sections of any such standards which apply to the system being described. For example, this could include legal, quality and regulatory standards, industry standards for usability, interoperability, internationalization, operating system compliance, etc.]

## 4.                  Supporting Information
[The supporting information makes the SRS easier to use.  It includes:

•               Table of contents

•             Index

•               Appendices

These may include use-case storyboards or user-interface prototypes. When appendices are included, the SRS should explicitly state whether or not the appendices are to be considered part of the requirements.]
