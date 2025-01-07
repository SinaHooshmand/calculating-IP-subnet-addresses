**Networking and Conversion Utilities**

This repository contains Python-based utilities for performing a variety of networking and number conversion tasks, including IPv4 subnet calculations, CIDR-to-decimal conversions, and hexadecimal conversions.

**Features**

1. Binary Calculator

Converts an integer to its binary representation.

Formats binary output for better readability.

2. IPv4 Subnet Addressing

Calculates key subnet details based on an IP address and subnet mask:

  Subnet ID
  
  Broadcast Address
  
  First Host Address
  
  Last Host Address

3. CIDR to Decimal Conversion

Translates CIDR notation (e.g., /24) into decimal subnet masks (e.g., 255.255.255.0).

Displays CIDR ranges for Class A, B, and C networks.

4. IPv6 AUI-64bit Address Calculation

Converts a MAC address into the Interface Identifier (EUI-64 format) used in IPv6 addressing.

5. Hexadecimal to Octal Conversion

Converts a hexadecimal number into its octal equivalent.

6. Hexadecimal to Binary Conversion

Converts a hexadecimal number into its binary representation.

**How to Use**

Run the script

Execute the Python script to launch the menu-driven application.

Choose a utility

Upon running, you will see the following options:
  1. Binary Calculator
  2. IPv4 Subnet Addressing
  3. CIDR to Decimal Conversion
  4. IPv6 AUI-64bit Address Calculation
  5. Hexadecimal to Octal Conversion
  6. Hexadecimal to Binary Conversion

Follow the prompts

Input the required data when prompted. For example:

Enter an integer for binary calculation.

Provide IP address and subnet mask for IPv4 subnet addressing.

Specify a MAC address for IPv6 AUI-64 conversion.

**Prerequisites**

Python 3.x

A basic understanding of networking concepts (IP addresses, subnets, etc.) is recommended.

**Example Usage**

**IPv4 Subnet Addressing**
  Define IP address:
  1: 192
  2: 168
  3: 1
  4: 10
  
  Define subnet mask:
  1: 255
  2: 255
  3: 255
  4: 0
  
  Output:
  IP address:         192.168.1.10
  Subnet Mask:        255.255.255.0
  Subnet ID:          192.168.1.0
  Broadcast Address:  192.168.1.255
  First Host Address: 192.168.1.1
  Last Host Address:  192.168.1.254

**CIDR to Decimal Conversion**
  Choose which key you want to check! (CAUTION CIDR NUMBERS START FROM 9 TO 32):
  Input: 24
  
  Output:
  Decimal number of subnet(/24) is:  255.255.255.0

**Contribution**

Contributions are welcome! If you have additional features or optimizations, feel free to submit a pull request.
