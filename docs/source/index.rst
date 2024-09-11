Welcome to Group 8's documentation!
===================================

This is where we will be putting in our lab documentation for the various projects.

Check out the :doc:`usage` section for further information, including
how to :ref:`introduction` the project.

Section 1: Hardware Information (5 points) 
HW Report: A short hardware report obtained using a command line tool. 
sudo lshw | less 

Tool(s) used: Which tool(s) were used to generate the report? 
Github, ReadTheDoc 

Tool Installation: What steps/commands were used to install the tool(s) 
Install python: sudo apt-get install python3
Install Sphinx: pip install Sphinx 


Section 2: OS Install (5 Points) 
Install process: OS Info and installation method 
OS: Ubuntu Server 20.04, installed via usb stick 


Section 3: Network Configuration (5 Points) 
Configuration: Detailed information of the network configuration used -> Is this of the multipass as well or just the ubuntu server? 


Justification: Reason for the network configuration choice 


Connectivity: (cmd tools only) Clear details of how you tested connectivity and what tools were used for the test and its installation details. 
ping 1.1.1.1 to test internet, network is dhcp 

Section 5: Cloud-init (10 Points) 
Which cloud-init files were configured and why? 
Cloudinit test file for multipass 
Cloudinit file for baremetal configuration 


.. note::

   This project is under active development.

Contents
--------

.. toctree::

   usage
   api
