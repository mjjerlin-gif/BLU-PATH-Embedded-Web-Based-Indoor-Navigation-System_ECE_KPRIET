# BLU-PATH-Embedded-Web-Based-Indoor-Navigation-System
BLU-PATH is an embedded web-based indoor navigation system using the BRD2605A board. It hosts a local Wi-Fi network and webpage that helps visitors locate campus facilities such as libraries, departments, and offices. Users connect via QR code and receive navigation guidance without requiring internet access or a mobile application. 

# BLU-PATH: Embedded Web-Based Indoor Navigation System

## Project Description

**BLU-PATH** is an embedded web-based indoor navigation system designed to help visitors, students, and staff easily locate facilities within a campus environment. Traditional GPS and online map services can identify the overall campus location but often fail to provide navigation to specific indoor or campus destinations such as libraries, department blocks, principal offices, laboratories, auditoriums, and administrative offices.

The proposed system utilizes the **Silicon Labs BRD2605A (SiWx917) development board** as a standalone Wi-Fi Access Point and embedded web server. When a visitor enters the campus, they can scan a QR code displayed at the entrance or connect directly to the BLU-PATH Wi-Fi network. Upon connection, a browser-based navigation portal is automatically accessed without requiring any mobile application installation.

The web portal provides an interactive campus directory where users can select their desired destination. The system then displays a predefined route map, location details, and navigation instructions to guide the user to the selected destination. Since all navigation data is hosted locally on the BRD2605A board, the system operates independently of internet connectivity, making it reliable, low-cost, and easy to deploy.

BLU-PATH offers a scalable solution for educational institutions, corporate campuses, hospitals, industrial facilities, and public buildings where indoor navigation is required. The project demonstrates the integration of embedded systems, Wi-Fi networking, HTTP web services, and user-friendly web interfaces to create a smart navigation platform.

---

## Problem Statement

Visitors entering a large campus often face difficulties locating specific departments, offices, laboratories, libraries, or service centers. Existing GPS-based navigation systems provide only the campus location and do not offer detailed indoor or campus-level guidance. This leads to confusion, delays, and dependency on staff assistance.

---

## Proposed Solution

BLU-PATH establishes a local Wi-Fi network and hosts a navigation webpage directly from the BRD2605A board. Users connect to the network, access the webpage, select a destination, and receive location-specific navigation information through an interactive web interface.

---

## Objectives

* Provide campus-level navigation without GPS.
* Host navigation webpages using the BRD2605A embedded web server.
* Enable QR code-based user access.
* Display campus maps and destination information.
* Operate without internet connectivity.
* Improve visitor experience and accessibility.

---

## Hardware Requirements

* Silicon Labs BRD2605A (SiWx917) Development Board
* USB Power Supply
* QR Code Display Board
* Mobile Phone / Tablet

---

## Software Requirements

* Simplicity Studio
* WiseConnect SDK
* Embedded HTTP Server
* HTML, CSS, JavaScript
* Wi-Fi Access Point Configuration

---

## Working Principle

1. BRD2605A starts as a Wi-Fi Access Point.
2. A visitor scans the BLU-PATH QR code.
3. The phone connects to the BLU-PATH Wi-Fi network.
4. The embedded web page opens automatically.
5. The user selects a destination.
6. The system displays the route map and navigation details.
7. The user follows the displayed guidance to reach the destination.

---

## Outcome

A visitor can independently navigate within the campus using only a smartphone browser, without downloading any application or requiring internet access. The system provides a simple, low-cost, and efficient indoor navigation solution hosted entirely on the BRD2605A embedded platform.
