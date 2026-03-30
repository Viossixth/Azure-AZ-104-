## Lab 05 - Implement Intersite Connectivity

<img width="1828" height="759" alt="image" src="https://github.com/user-attachments/assets/a4bd113e-288b-4cf3-b1a3-18a1c2a0046f" />

**Task 1 & 2: Create two virtual machine in two virtual networks**

In this task of the labm i had to create two virtual networks ManufacturingVnet and CoreServicesVnet with their associated subnets.

<img width="1365" height="645" alt="Screenshot 2026-03-30 195242" src="https://github.com/user-attachments/assets/dd22adc8-98c9-4cb3-8d3e-a0bce1427ea3" />
<img width="1365" height="647" alt="Screenshot 2026-03-30 200244" src="https://github.com/user-attachments/assets/0fe60033-92f0-48b6-b8ff-7eb2f10edad2" />
<img width="1365" height="648" alt="Screenshot 2026-03-30 201015" src="https://github.com/user-attachments/assets/726d0c36-b3bf-454d-94ba-d4296552123d" />
<img width="1365" height="645" alt="Screenshot 2026-03-30 201024" src="https://github.com/user-attachments/assets/ca7c6b3a-d6d8-426c-8e09-8b90676e3e27" />
<img width="1365" height="645" alt="Screenshot 2026-03-30 201733" src="https://github.com/user-attachments/assets/7c0eb6fd-37a8-4613-9848-115d11dfbaf6" />

**Task 3: Use Network Watcher to test the connection between virtual machines**

In this step i had to use a network connectivity test to determine if there is a connection between the two virtual machines. There was no connection between the two VM's.

<img width="1365" height="647" alt="Screenshot 2026-03-30 201149" src="https://github.com/user-attachments/assets/9e702a5d-b07d-4458-b595-6142ebb258bc" />
<img width="1365" height="648" alt="Screenshot 2026-03-30 201627" src="https://github.com/user-attachments/assets/ea48ccb7-cff5-458c-b200-4441cf24e724" />

**Task 4: Configure virtual network peerings between different virtual networks**

As seen in task 4 there is no connection between the two virtual machines since they are in two different networks. To solve this the virtual networks have to communicate first.
Virtual network peering accomplishes this.

<img width="1365" height="647" alt="Screenshot 2026-03-30 201853" src="https://github.com/user-attachments/assets/97fe5ca6-2a4b-43a0-9227-40c10bed7177" />
<img width="1365" height="649" alt="Screenshot 2026-03-30 202105" src="https://github.com/user-attachments/assets/992509eb-c776-4874-a80c-e1a09231abcd" />
<img width="1365" height="646" alt="Screenshot 2026-03-30 202129" src="https://github.com/user-attachments/assets/066f693f-d767-439e-8c2a-b99ca7f2349e" />

**Task 5: Use Azure PowerShell to test the connection between virtual machines**

 In this part of the task i take note of the private IP address of the CoreServicesVM. I then go over to the ManufacturingVM and run a command script to test the connection between the two virtual machines.
 
<img width="1365" height="646" alt="Screenshot 2026-03-30 203225" src="https://github.com/user-attachments/assets/364bab0b-58e5-4160-b557-9e970d3aa33a" />
<img width="1363" height="647" alt="Screenshot 2026-03-30 203711" src="https://github.com/user-attachments/assets/3aa96a2b-0512-4c55-a162-52ef5b2649b1" />

**Task 6: Create a custom route**

For the final part of this lab, i have to connect two subnets, the Perimeter subnet and the internal CoreServices subnet and attach a virtual appliance where all the traffic will be routed to in the Perimeter subnet.

<img width="1365" height="645" alt="Screenshot 2026-03-30 211452" src="https://github.com/user-attachments/assets/a8fe08fa-b09a-491b-a1da-d42dc442884f" />
<img width="1363" height="646" alt="Screenshot 2026-03-30 211444" src="https://github.com/user-attachments/assets/771fbef1-c060-49b1-98d6-0d0dff2f778b" />
<img width="1365" height="643" alt="Screenshot 2026-03-30 211057" src="https://github.com/user-attachments/assets/c31f5e69-b9fa-4dda-bc53-6ffc941ea6ef" />
<img width="1365" height="646" alt="Screenshot 2026-03-30 205751" src="https://github.com/user-attachments/assets/c0db75ac-4b69-4fb3-bf87-9c4e4f343eea" />





