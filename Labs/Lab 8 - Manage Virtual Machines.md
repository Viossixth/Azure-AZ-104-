## Lab 08 - Manage Virtual Machines

**Task 1: Deploy zone-resilient Azure virtual machines by using the Azure portal**

To start this lab, I had to configure and create two Azure Virtual Machines. I logged into the Azure Portal and configured them, as shown in the screenshots.

<img width="1365" height="647" alt="Screenshot 2026-04-01 101535" src="https://github.com/user-attachments/assets/1f0a7257-33e8-4532-b70f-2bf852d6f05b" />
<img width="1365" height="648" alt="Screenshot 2026-04-01 103943" src="https://github.com/user-attachments/assets/0324b33b-1e19-4b5d-906f-2c03c1b35514" />

**Task 2: Manage compute and storage scaling for virtual machines**

In this step of the lab, I had to resize the virtual machine. This is also known as Vertical Scaling, resizing and changing the type of Virtual Machine. 
I then created a new disk and attached it to the Virtual Machine. Then i decoupled the VM, changed if from a standard HDD to a standard SSD. To change the disk isn't possible when its attached to the VM.
Then I re-attached the disk to the VM.

<img width="1365" height="644" alt="Screenshot 2026-04-01 115421" src="https://github.com/user-attachments/assets/4e8ca008-c9f2-4446-a042-36811ebb5974" />
<img width="1365" height="645" alt="Screenshot 2026-04-01 115852" src="https://github.com/user-attachments/assets/08b6aa2b-5252-47d4-b45b-750910eff1ae" />
<img width="1365" height="645" alt="Screenshot 2026-04-01 120131" src="https://github.com/user-attachments/assets/2a4e1454-77e3-47a4-8d05-834fb027132b" />
<img width="1365" height="643" alt="Screenshot 2026-04-01 120242" src="https://github.com/user-attachments/assets/5aecdce0-14a9-475b-b1ef-93cf2a56ba28" />
<img width="1365" height="647" alt="Screenshot 2026-04-01 120535" src="https://github.com/user-attachments/assets/0f9be247-ff02-435c-9dd4-7a45b0d7ecbc" />

**Task 3: Create and configure Azure Virtual Machine Scale Sets**

For task 3 I created a Virtual Machine Scale sets, using the configuration instructions from the lab.

<img width="1365" height="647" alt="Screenshot 2026-04-01 121822" src="https://github.com/user-attachments/assets/b43d03f7-8a49-405f-8753-0181817b85ac" />
<img width="1365" height="647" alt="Screenshot 2026-04-01 133527" src="https://github.com/user-attachments/assets/4033404e-5cd9-4fc5-96d9-b379c1ce4190" />

**Task 4: Scale Azure Virtual Machine Scale Sets**

In this part of the lab, I configured the scale set rules and conditions. This allows the Virtual Machine set to scale up or down depending on the conditions present. 

<img width="1365" height="645" alt="Screenshot 2026-04-02 220152" src="https://github.com/user-attachments/assets/3796c93e-4e70-4e0b-9afd-686339bef1da" />
<img width="1365" height="646" alt="Screenshot 2026-04-02 221028" src="https://github.com/user-attachments/assets/684103c3-daf5-41e9-bafb-dd164b51aa87" />

**Task 5: Create a virtual machine using Azure PowerShell**

For this part of the lab I have to create a virtual Machine using the CLI. I logged into PowerShell, used the script template to create a new VM and waited for deployment. Once finalised, i validated if it's up and running. Once i saw the confirmation on the CLI and Azure Portal, i deallocated it on the cli. I also confirmed to see if it's deallocated.

<img width="1365" height="647" alt="Screenshot 2026-04-02 222340" src="https://github.com/user-attachments/assets/6477bfa1-5536-4d8f-89ed-25bf8faf97b4" />
<img width="1365" height="647" alt="Screenshot 2026-04-02 222424" src="https://github.com/user-attachments/assets/897d1dfc-637f-45cb-8165-6f795f1d3e64" />
<img width="1365" height="648" alt="Screenshot 2026-04-02 222446" src="https://github.com/user-attachments/assets/b02789f0-5e4c-486d-894b-3403f8e8b702" />
<img width="1365" height="648" alt="Screenshot 2026-04-02 222503" src="https://github.com/user-attachments/assets/4650c88f-4e65-41a6-b309-9a6255db64f6" />
<img width="1365" height="648" alt="Screenshot 2026-04-02 222518" src="https://github.com/user-attachments/assets/dbbf1236-edce-43ac-b77e-697553365c3c" />
<img width="1365" height="646" alt="Screenshot 2026-04-02 222817" src="https://github.com/user-attachments/assets/1592c522-c56a-4822-b259-feb0344e85f4" />
<img width="1364" height="646" alt="Screenshot 2026-04-02 222834" src="https://github.com/user-attachments/assets/b0198bf8-d6c1-4c2e-93cd-1dc3d4824016" />
