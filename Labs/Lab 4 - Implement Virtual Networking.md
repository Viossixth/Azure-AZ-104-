## Lab 04 - Implement Virtual Networking

This lab focuses of Virtual Private networks, using subnetting to create a bigger pricvate network and ensuring security using network security groups.

**Task 1: Create a virtual network with subnets using the portal**
To complete task 1 i have to create a virtual network with two subnets on the Azure Portal. After sucessfully created the Virtual Network i downloaded the resource template.

<img width="1365" height="646" alt="Screenshot 2026-03-28 173133" src="https://github.com/user-attachments/assets/e168d4e1-2fc8-448e-a914-43ff53a3dc8e" />
<img width="1365" height="646" alt="Screenshot 2026-03-28 173811" src="https://github.com/user-attachments/assets/7c49e97e-b130-4fbf-8dc9-959da34913cf" />
<img width="1365" height="646" alt="Screenshot 2026-03-28 174033" src="https://github.com/user-attachments/assets/492d5ade-f4ac-442b-96b5-fe85c4821b10" />

**Task 2: Create a virtual network and subnets using a template**

For task 2 i had to create a new virtual network and two subnets using the template i downloaded from task 1. I changed the names and CIDR Ranges of the Vnet and subnets. I had to ensure that the JSON formatting tules were followed and correct.
It took a lot of tries but i finally got it right.

<img width="1365" height="646" alt="Screenshot 2026-03-28 180618" src="https://github.com/user-attachments/assets/d19961cd-3a20-4e3a-a45d-eeb35eacd16c" />
<img width="1364" height="647" alt="Screenshot 2026-03-28 182642" src="https://github.com/user-attachments/assets/88499f0f-1aaf-4d5f-812c-daf5499d2d4b" />
<img width="1365" height="645" alt="Screenshot 2026-03-28 184138" src="https://github.com/user-attachments/assets/854b9d04-d635-4256-80db-6b2f9ce3d315" />

**Task 3: Create and configure communication between an Application Security Group and a Network Security Group**

For task 3 i had to configure an Applications ecurity group and a network security groups. To my knowledge security groups, filter out traffic by creating inbound and outbound rules chose what to allow or deny.
Secondly i had to configure the Inbound and Outbound rules of the Network Security group.

<img width="1365" height="647" alt="Screenshot 2026-03-28 185203" src="https://github.com/user-attachments/assets/0ca93a6a-4e1f-494d-9662-2f845e3b39e5" />
<img width="1365" height="646" alt="Screenshot 2026-03-28 185305" src="https://github.com/user-attachments/assets/099f1d55-b232-42ba-b14e-7eb217e2eb7d" />
<img width="1365" height="646" alt="Screenshot 2026-03-28 185016" src="https://github.com/user-attachments/assets/4dd0ee0d-a5b9-4603-8a42-eadc301a7c18" />
<img width="1363" height="645" alt="Screenshot 2026-03-28 190238" src="https://github.com/user-attachments/assets/362fffca-7c1e-4c58-b0e3-c042b7752d60" />
<img width="1365" height="645" alt="Screenshot 2026-03-28 185802" src="https://github.com/user-attachments/assets/c59ee3fa-5036-429b-9698-b600018e60c5" />

**Task 4: Configure public and private Azure DNS zones**

In this part of the lab i created a public and private dns zones. A public dns zone can be reached by anyone from the internet whilst a private one can't and can be accessed by an asoociated virtual network.
A DNS Zone allows for domain name resolution, whereby a name such as Ginion-Project.com is resolved into an IP Address. Azure has this service and was used to create a dns zone for Ginion-Project.com .
This was later made into a public and private dns zone. 

<img width="1365" height="647" alt="Screenshot 2026-03-28 190629" src="https://github.com/user-attachments/assets/7a77003a-6695-46dc-b143-9e1f4279fca7" />
<img width="1365" height="647" alt="Screenshot 2026-03-28 190751" src="https://github.com/user-attachments/assets/01dd94b9-18a3-47c3-b99e-68211d02a5ea" />
<img width="694" height="190" alt="Screenshot 2026-03-28 191942" src="https://github.com/user-attachments/assets/bab23085-8770-4f35-883a-7110584f1e69" />
<img width="1365" height="647" alt="Screenshot 2026-03-28 192311" src="https://github.com/user-attachments/assets/7f5ad360-6742-4851-90b5-4a300b76c4cf" />
<img width="1365" height="647" alt="Screenshot 2026-03-28 192509" src="https://github.com/user-attachments/assets/e5bbdec6-49ee-438d-9063-7223286a096a" />
<img width="1365" height="644" alt="Screenshot 2026-03-28 192647" src="https://github.com/user-attachments/assets/84ce9f52-fbf7-47fd-af9d-027c263da989" />

**Summary**

This was a challenging lab, where i had to deal with Virtual Networks, ASG's ,NSG's Azure DNS Zones and recordsets. It was fascinating and intruiging at the same time. Altering the template came with its issues and its part of understanding and mastering JSON form templates.
Having a real world scenario such as creating a dns zone and validating it made me appreaciate the work that Infrastructure Engineers do and how computers simplify life. If it wasn't for them using the internet would be more difficult. I leave this lab having gained real life experience and gained more confidence to use Azure.






