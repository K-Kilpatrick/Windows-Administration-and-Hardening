# Windows-Administration-and-Hardening
Module 7: Introduction to Windows and CMD, PowerShell Scripting, Windows Active Directory Domain Services

Module Description
In our introduction to the Windows operating system, we will learn Windows-based system administration. We will cover the Windows operating system and command line by performing basic system administration tasks. We will depart from the standard command line by using the PowerShell command-line scripting language to create and execute scripts. We will also manage Active Directory Domain Services and secure a Windows Server domain.

Module Objectives

Day 1: Introduction to Windows and CMD

Leverage the Windows Command Prompt (CMD) to navigate and manage directories and files.

Use wmic and Task Manager to manage processes and retrieve system info.

Create, manage, and view user information using the command-line tool net.

Manage password policies using gpedit.

Optionally, schedule tasks using Task Scheduler.

Day 2: PowerShell Scripting

Use basic PowerShell cmdlets to navigate Windows and manage directories and files.

Use PowerShell pipelines to retrieve Windows system event logs.

Combine various shell-scripting concepts such as cmdlets, parameters, piping, conditions, and importing files with data structures.

Day 3: Windows Active Directory Domain Services

Explain how Active Directory is used to manage enterprise-scale environments.

Define domain controllers as servers that manage AD authentication and authorization.

Use Active Directory tools to create organizational units, users, and groups.

Create and link Group Policy Objects that enforce domain-hardening policies.

Lab Environment
This module will use an online Azure lab environment (labs.azure.com). This environment consists of a Windows RDP Host machine that houses two nested virtual machines: a Windows 10 machine and a Windows Server machine. Use the following credentials:

Windows RDP Host Machine

RDP login credentials for labs provisioned prior to 9/12/23

Username: azadmin

Password: p4ssw0rd*

RDP login credentials for labs provisioned after 9/12/23

Username: azadmin

Password: p@ssw0rdp@ssw0rd

Windows 10 Machine (used on Day 3)

Username: sysadmin

Password: cybersecurity

Windows Server Machine (used on Day 3)

Username: sysadmin

Password: p4ssw0rd*

Module Checklist
Before beginning to prep this week's lesson, be sure you have the following accessible within your lab. Please notify the curriculum team as soon as possible if any of the following is not available.

 Windows 10 Machine

 Windows Server Machine

What to Be Aware Of

Don't forget to shut down your virtual machines and your Windows Azure lab at the end of each class and when they are not in use.

You will be provided 30 hours of Azure lab access.

If you exceed that quota, you will be provided an additional 10 hours.

If you exceed those additional hours, you will be provided an additional 5 hours.

Once you exceed the final quota, you will not be provided any additional hours. It is extremely important that you preserve your allotted hours by shutting off your machines at the end of each class.

The following document contains a list of common Windows issues that may occur during this module. Review the content to prepare for potential troubleshooting:

Windows Lab Environment Guide

Security+ Domains
This module covers Windows-based portions of the following domains on the Security+ exam:

2.0 Architecture and Design

3.0 Implementation

For more information about these Security+ domains, refer to the following resource: Security+ Exam Objectives

Additional Reading and Resources
 
These resources are provided as optional, recommended resources to expand on and solidify the concepts covered in this module.

Day 1 Resources

SANS - Windows Command Line Cheat Sheet

HowToGeek: Task Manager Guide

SS64: Windows Environment Variables

SS64: Command-line Overview of wmic

Digital Trends: 32-bit vs 64-bit

Microsoft | Docs: wmic

Digital Citizen: Net User Commands

wikiHow: How to Add Users from CMD

Microsoft | Docs: Windows Release Information

Microsoft | Docs: net user

Microsoft | Docs: net localgroup

Microsoft | Support: Microsoft's net accounts documentation

Microsoft | Docs: Security Identifiers

Day 2 Resources

Microsoft | Docs: PowerShell Cmdlet Overview

SS64: PowerShell Parameters

Microsoft | Docs: PowerShell Pipelines

Chocolatey.org: Why Chocolatey?

Chocolatey.org: How to Use Chocolatey

Chocolatey.org: Choco Uninstall

Whatis.com: Circular Logging

Day 3 Resources

Microsoft | Docs: Active Directory Domain Services

Microsoft | Docs: Creating Active Directory Users

Microsoft | Docs: Creating Organizational Units

Microsoft | Docs: Active Directory Security Groups

Microsoft | Docs: Creating GPOs

Petri.com: Create and Link Group Policy Object

Homework Resources

Microsoft | Docs: Access Control Lists

Module 7: Challenge
This module's Challenge assignment can be found in Canvas.

For the Challenge, students will expand on domain-hardening Group Policy Objects and testing them. They will also create a PowerShell script to automate the retrieval of access control lists.

Looking Forward
Next week, we'll be moving on to our Networking Unit! We will start by learning the fundamentals of network configurations, designs, protocols, and data communication.
