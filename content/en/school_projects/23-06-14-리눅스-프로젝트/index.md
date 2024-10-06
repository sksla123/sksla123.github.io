---
title: Creating a Café Kiosk
subtitle: Creating a Café Kiosk
date: 2023-06-14
image:
  focal_point: 'center'
---

We developed a program that implements a café kiosk system, allowing users to select menu items and make payments through a multi-client and server communication process for ordering and payment.




<!--more-->

**Café Kiosk System: A Story of Developing an Efficient Order Processing System**



I worked on a project focused on a café kiosk system. Inspired by the kiosk systems commonly found in cafés, I developed a system that allows customers to select menu items and add various options to complete their orders. I aimed to efficiently handle customer orders through this system. In this post, I will discuss the features and usage of the system, as well as the communication protocols involved.



**Concepts of Projects**




The café kiosk system has become a familiar automated ordering method for us. I implemented this system based on socket communication, designing a structure that allows multiple clients to connect simultaneously and process orders smoothly. My goal was to create a program that efficiently manages the entire process, from menu selection to payment.




**How to use**




How to use Server


You can run the server in the terminal using the following command:


./KIOSK_server [[Server Name]] [[Name of DB]]




When the server starts, it will automatically create a DB file or open an existing one. Now, multiple clients are ready to connect. To stop the server, press Ctrl+\ and to modify products, press Ctrl+C.





Client Usage

You can run the client in the terminal using the following command:


./KIOSK_client [[Client Name]]



The client displays the message "Press any key to start" and waits for user input. Once input is received, it fetches category information from the server and displays it on the screen.




**Main Features**




Feature of Server



Multiple Client Connections: To ensure that multiple users can connect simultaneously without interruption, the fork() function is used to create child processes that handle the connections.

Product Quantity Management: When a product is sold out, a "sold out" message is sent to the client.

Payment Functionality: If the requested quantity is insufficient or the payment amount is insufficient, the purchase will not proceed.

Client Features:

Users can select products from their desired categories and proceed with purchasing and payment.

Cart Functionality: Users can add selected products to their cart for payment or return to the menu to add more items.


Communication Protocol:

This system operates through clear communication protocols between the client and server. Some key protocols include:





Protocol 0: The client and server exchange names to initiate communication.

Protocol 1: Request to terminate communication.

Protocol 2: Exchange of category information requests.

Protocol 3: Requesting product information within a specific category.

In addition to these, various communication protocols for requesting product details, option information, and processing payments have been designed to ensure the system operates reliably




**Add-on Features**




Input Error Management: Logic has been added to handle errors for invalid inputs or protocol violations.

Binary File DB: Data is managed in binary file format to enhance storage efficiency.

Client Input Timeout: If there is no input for 120 seconds, the client automatically restarts.

Menu Description Display: When a product is selected, users can immediately see the description, price, and remaining quantity.

Real-Time Cart Updates: Users can view the products added to their cart in real-time.



**Finally**



I believe the café kiosk system is a project with significant potential for further development. While creating a system that allows customers to order more easily and quickly, I learned a lot and gained a deeper understanding of socket communication and efficient order processing systems.