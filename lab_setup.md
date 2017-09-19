# Lab topology for IPspace network automation course

## Introduction
This document explains the toplogy used for the lab part of the IPspace network automation course.

## Components
I am using Cisco VIRL version 1.3 on ESXi version 5.5.
On the same ESXi host I have a Ubuntu 17 VM that has ansible, git and emacs.

## Lab topology in VIRL
In Cisco VIRL I have 2 IOSv Layer 2 devices, 2 CSR1000V and 2 NX-OSv devices.
All the devices are accessible over SSH on the mgmt port from the Ubuntu VM running ansible.
