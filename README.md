# Lab-2
# Lab #1, 19110054, Mai Dang Quang, INSE331280E_01FIE
**Question 1**:
Setup a set of vms/containers in a network configuration of 2 subnets (1,2) with a router forwarding traffic between them. Relevant services are also required:
- The router is initially can not  route traffic between subnets
- PC0 on subnet 1 serves as a webserver on subnet 1
- PC1, PC2 on subnet 2 acts as client workstations on subnet 2
**Answer 1**:
## Create a virtual machine named `PC0`
<img width="500" alt="Screenshot" src="https://github.com/user-attachments/assets/f36ef931-d687-49c8-bb37-4931c199866f"><br>

## Create a subnet 
*In VMWare main menu, click Edit and then Virtual Network Editor*
<img width="500" alt="Screenshot" src="https://github.com/user-attachments/assets/4f88da6c-60ab-4ff0-868c-a3eda4be7ce5"><br>

*In the bottom, click Change setting to edit network*
*Click VMnet0 and change to Host-only for temporary*
<img width="500" alt="Screenshot" src="https://github.com/user-attachments/assets/6be43dfb-86d6-4e49-8f83-e59a258e153e"><br>

*Click Add Network, Select and unrelated network, in this case is VMnet2 and click Ok*
<img width="500" alt="Screenshot" src="https://github.com/user-attachments/assets/5e402a38-9a94-481c-b85b-157401996c7c"><br>

*Set VMnet2 to Bridged to and choose a new virtual adapter and then click Apply*
<img width="500" alt="Screenshot" src="https://github.com/user-attachments/assets/b670671f-3626-4adc-8927-a6c733b43801"><br>

*Comeback to VMnet0 and set to Bridged and choose Automatic and then click Apply*
<img width="500" alt="Screenshot" src="https://github.com/user-attachments/assets/789ebabe-dfb1-4e43-8db1-ab1075297d1b"><br>
