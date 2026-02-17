# ansible-setup-vagrantfile
An ansible Vagrantfile for our setup


## Instructions

    Install Vagrant and VirtualBox: Make sure you have Vagrant and VirtualBox installed on your system.

    Create and Initialize the Vagrant Environment:
        Save the above Vagrantfile to a directory of your choice.
        Open a terminal and navigate to the directory containing the Vagrantfile.
        Run vagrant up to start and provision the VMs. This process will download the necessary Vagrant boxes and configure the VMs according to the Vagrantfile.<img width="1916" height="1001" alt="image" src="https://github.com/user-attachments/assets/ba46d679-7b8d-497b-aa39-d31e8e2c6e47" />


    ## Access the VMs:
        You can SSH into any of the VMs using the following commands:



    ```
    vagrant ssh master
    vagrant ssh node1
    vagrant ssh node2
    vagrant ssh node3
    ```
