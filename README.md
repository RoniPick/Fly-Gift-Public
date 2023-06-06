# FlyGift

**FlyGift is a React application designed to provide an easy and reliable platform for employers to purchase gift cards for their employees. The application integrates a search engine, payment APIs, and various client functionalities.**

## Table of Contents
1. Introduction
    - Purpose
    - Scope
    - Overview
2. System Overview
3. System Architecture
4. Data Design
5. Component Design
6. Human Interface Design

## Introduction

### Purpose

This project aims to create an application that allows employers to purchase gift cards for their employees, improving employee morale and fostering loyalty. The application will provide a comfortable and reliable platform for employees to receive gift cards, search for flights, purchase flight tickets, and save points for future use.

### Scope
The FlyGift application will offer the following features and technologies:
- React JS application.
- Database for secure data storage.
- Client-side functionality for data safety.
- Integration with a flight search engine.
- Integration with payment, SMS confirmation, and email confirmation APIs.

### Overview
The current approach to matching holiday gifts for employees often results in dissatisfaction, with 77% of recipients unsatisfied with the gifts received. FlyGift aims to address this by introducing a new type of gift card that allows employees to search for and purchase flight tickets. The application will offer a user-friendly interface and seamless integration with various APIs for payment, SMS confirmation, and email sending.

## System Overview
The FlyGift application authenticates users through a database and directs them to the relevant portal. Users can access the User Portal, which includes functionalities such as the Flight Search Engine, Secure Payment, and Email Validation APIs.
The simplified functionality flow is as follows:
User -> Authentication -> Validation Token -> Connects to personal data -> Opens User Portal -> Access to all application functionalities.

## System Architecture
The FlyGift application follows a client-server architecture, with the React application serving as the client-side and a database managing the server-side.

The system architecture is divided into the following components:

- User Authentication
- Flight Search Engine
- Payment API Integration
- Email Confirmation API Integration
For a detailed description of the system architecture and component breakdown, please refer to the Architecture document.

## Data Design
The application utilizes a database to store user information, flight data, and purchase history. The database structure is designed to ensure data integrity, security, and efficient retrieval. For more details on the data design, please refer to the software design document.

## Component Design
The component design of the FlyGift application involves multiple React components working together to provide seamless user experience and functionality. The components are organized in a modular and reusable manner, allowing for easy maintenance and future scalability.

## Human Interface Design
The FlyGift application's user interface aims to provide an intuitive and user-friendly experience. The design focuses on simplicity, easy navigation, and clear presentation of information.
