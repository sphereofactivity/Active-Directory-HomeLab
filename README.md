# Active Directory Home Lab

Welcome to the **Active Directory Home Lab** repository! This guide provides a simple, step-by-step walkthrough on how to set up an Active Directory (AD) environment in a home lab. Whether you are learning about AD for personal development, testing configurations, or exploring more advanced features, this repository offers an easy-to-follow guide for setting up a basic Active Directory setup on your own hardware or virtual machines. This write up specifically follows a single device home lab using virtualization but can be replicated on a multi-device setup. 

## Purpose

This repository serves as a reference for users who want to quickly get up and running with a basic Active Directory environment. It is designed for beginner users looking to explore AD, its components, and its functionality in a controlled, self-hosted environment.

By following this guide, you will:

- Set up a Domain Controller (DC) to manage Active Directory.
- Create and configure a default user profile.
- Understand how AD setup works and gain hands-on experience with its management tools.

## Features

- **Step-by-Step Setup:** Detailed instructions on how to install and configure the necessary components.
- **Minimal Hardware Requirements:** You can run this lab on modest hardware or in a virtualized environment. My device uses the minimum recommended specs for both AD and Windows 11 for this example.
- **Beginner-Friendly:** Ideal for those new to Active Directory or those looking to practice basic AD administration tasks.

## Prerequisites

Before getting started, you will need:

- **Computer(s) or virtual machine**: This lab can be set up on physical machines, or using virtualization platforms like VirtualBox, VMware, or Hyper-V but will be demonstrated using VMWare Workstation.
- **Windows Server 2025**: This can be found at this [Microsoft help document for Windows Server 2025](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2025)
- **Windows 11 Pro ISO**: You can create a Windows 11 Pro ISO file if owned currently at this [Windows Media Creation Tool](https://support.microsoft.com/en-us/windows/create-installation-media-for-windows-99a58364-8c02-206f-aa6f-40c3b507420d)
- **Basic Networking Knowledge**: Basic understanding of networking (IP addresses, subnetting, etc.) is helpful but not required. 


## Guide Overview

The setup guide is split into the following sections:

1. **Tools and Software Needed**  
   A brief overview on the required tooling.
   
2. **Initial Setup Steps**
   Setting up the Virtual machine station and custom network for the machines to communicate on and brief installation tips for preparing to install.
   
4. **Install**  
   Installation of both Windows 11 and Server 2025. 

5. **Windows Server 2025 Domain Controller Configuration**  
   Configuring setup of your domain controller and deployment configuration.

6. **Creating Domain Users**  
   Creating a domain user to connect to the server and setting up their profile.

7. **Attaching Windows to the Domain Controller**  
   Step-by-step guide on how to join a Windows client machine to your AD domain for testing and management.

## Getting Started
Simply open the markdown files in the directory to follow the steps on how to proceed with set up.

## Features coming
- Group Policy Management
- Organizational Units
- Shared folders and permissions

For any questions or assistance, I can be reached at elkan.dsilva@gmail.com
