## Lab 03 - Manage Azure resources by using Azure Resource Manager Templates
<img width="1572" height="737" alt="image" src="https://github.com/user-attachments/assets/705bf205-3e3a-4f72-a19e-b4bf138ca65d" />

The main focus of this lab is using resource automation deployments. Resource automation deployments ease the process of creating new resrources, use a template for less administrative overheads and create consistency.

**Task 1: Create an Azure Resource Manager template**

To familiarise myself with ARM Templates, i decided to create a new disk in the old manual way and when completed I will look at the template to understand how to create them for in future. The templates are in JSON.

<img width="1365" height="648" alt="Screenshot 2026-03-28 090117" src="https://github.com/user-attachments/assets/b1c4ba7c-552e-4364-8b6e-a828b1f38c67" />
<img width="1365" height="646" alt="Screenshot 2026-03-28 090831" src="https://github.com/user-attachments/assets/c4674616-afe7-4ce7-ac77-00529ffa19a6" />
<img width="1365" height="646" alt="Screenshot 2026-03-28 091442" src="https://github.com/user-attachments/assets/3731c813-30d3-4b79-ba7c-6ecc2b45457e" />
<img width="1365" height="767" alt="Screenshot 2026-03-28 092433" src="https://github.com/user-attachments/assets/c51b4982-95cc-4711-82cb-d8ccd893e75c" />

**Task 2: Edit an Azure Resource Manager template and redeploy the template**

For the second task of this lab I had to use the downloaded template of the disk created in task 1. I used the template as a basis for the new disk i want to create. I altered the template to create a new disk and then deployed it.
It was successfully deployed and now i have two disks, one created manually and the other from a JSON Template.

<img width="1365" height="648" alt="Screenshot 2026-03-28 095142" src="https://github.com/user-attachments/assets/61f553a3-10b3-40fa-9ad9-3e533d5d3b71" />
<img width="1365" height="767" alt="Screenshot 2026-03-28 095357" src="https://github.com/user-attachments/assets/96db9b28-140a-4987-a65f-de120062a67a" />
<img width="1363" height="645" alt="Screenshot 2026-03-28 095848" src="https://github.com/user-attachments/assets/601463d3-b41f-4eab-bc37-fb6b2dde458f" />
<img width="1364" height="644" alt="Screenshot 2026-03-28 100029" src="https://github.com/user-attachments/assets/096ad615-d4e4-4c14-b08c-cf008440ad44" />
<img width="1365" height="647" alt="Screenshot 2026-03-28 100126" src="https://github.com/user-attachments/assets/0b569b45-42ed-46de-9db1-6d5c3b35e9dd" />
<img width="1365" height="647" alt="Screenshot 2026-03-28 100144" src="https://github.com/user-attachments/assets/964b259b-5afe-448a-af01-c6fa04199bc4" />

**Task 3: Configure the Cloud Shell and deploy a template with Azure PowerShell**

For task 3 i had to use ClouShell to deploy a template downloaded from task 1. I had to go to the CloudShell button, configure the space and wait for it to commence. Then I had to upload the template and use the editor to make some changes.
Once that was complete, i used a script to deploy the new template and then verify if the new resources were created.

<img width="1365" height="646" alt="Screenshot 2026-03-28 101151" src="https://github.com/user-attachments/assets/189ca4bb-c938-42de-b230-335f59b98cdb" />
<img width="1365" height="600" alt="Screenshot 2026-03-28 102321" src="https://github.com/user-attachments/assets/68a5f5bd-c739-4b4c-b0e5-9032fb3aa5ac" />
<img width="1365" height="647" alt="Screenshot 2026-03-28 102403" src="https://github.com/user-attachments/assets/69e74332-c160-4aa2-8d28-b56f7edb6002" />
<img width="1365" height="647" alt="Screenshot 2026-03-28 102905" src="https://github.com/user-attachments/assets/10178139-4efe-4547-9b94-6f48f306ff8c" />

**Task 4: Deploy a template with the CLI**

Similar to what i did in Task 3, I used the Command Line Interface to deploy a new resource. I used Bash this time instead of PowerShell.
With Bash, i first confirmed if the template was available and then used the editor to make some changes. Then i used a script to deploy the new resource and validated if they were succesfully created.

<img width="1365" height="646" alt="Screenshot 2026-03-28 103533" src="https://github.com/user-attachments/assets/843293ca-db34-4339-9c1d-224afc42c830" />
<img width="1365" height="646" alt="Screenshot 2026-03-28 103703" src="https://github.com/user-attachments/assets/342fe891-0094-4961-b243-2d10e22a0f0f" />
<img width="1365" height="647" alt="Screenshot 2026-03-28 103708" src="https://github.com/user-attachments/assets/45b4dc5c-6bde-4ede-a1db-7eff2900595c" />

**Task 5: Deploy a resource by using Azure Bicep**

For task 4 i have to use a bicep template to deploy resources. I uploaded the template and made the neccesary changes, saved it. On the Bash terminal i ran the deployment script and also ran a script to show all the available resources and it showed 5 different resources.
Each resource for each task of this lab.

<img width="1365" height="646" alt="Screenshot 2026-03-28 104648" src="https://github.com/user-attachments/assets/f5784628-f1f4-43a3-bbb1-939dc79f90c7" />
<img width="1365" height="648" alt="Screenshot 2026-03-28 105743" src="https://github.com/user-attachments/assets/321155b4-7a33-48e0-9882-620e37e3ee67" />

**Summary**

The purpose of this lab was to gain hands on experience with the tools and techniques to deploy resources. I showcased 5 different ways to deploy an azure disk from using a manual and lengthy deployment to using a JSON template or a Bicep template.
I also used the CLI, using both bash and powershell. I also gained familiarity with the scripts used to check iffiles are present, how to deploy them and validating if everything is done well.
