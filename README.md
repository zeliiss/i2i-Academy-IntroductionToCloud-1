# # i2i Academy - Introduction to Cloud - Assignment 1

## Purpose
This project is part of my i2i Academy internship training.
The goal is to create a Virtual Machine on Google Cloud Platform (GCP) 
and test the connection to it.

## What I Did
- Created a Virtual Machine on Google Cloud Platform
- Tested the network connection by pinging the VM's public IP address
- Connected to the VM using SSH
- Created a text file on the VM and checked its content

## Environment
- Cloud Provider: Google Cloud Platform (GCP)
- Operating System: Debian Linux
- Connection Method: SSH

## Note
Screenshots and detailed documentation of this homework are 
submitted separately via Google Classroom, as required by the 
course guidelines.
## Network Connection Test (Ping)
I opened Command Prompt on my computer and used the ping command to 
check if I could reach my Virtual Machine over the network.

Command:
ping 34.79.147.190

Result:
The VM replied successfully to all 4 packets with 0% packet loss, 
which means the network connection to the VM is working correctly.

## Connecting to the VM and Creating a File (SSH)
I connected to my Virtual Machine using SSH (browser-based SSH from 
Google Cloud Console). After connecting, I created a text file 
containing the required message and added a short personal note, 
then checked the content using the following commands:

Command 1 - Create the file with the required text:
echo "Hello i2i Academy!" > hello.txt

Command 2 - Add a personal note to the same file:
echo "This file was created by Zelis during the i2i Academy internship." >> hello.txt

Command 3 - Read (display) the content of the file:
cat hello.txt

Result:
The file was created successfully and the terminal displayed both 
lines of text, which confirms that the file creation and reading 
process worked as expected.
