## Lab 10 - Implement Data Protection

<img width="1609" height="737" alt="image" src="https://github.com/user-attachments/assets/cb8d4850-0412-429b-9c86-b4a48648d6ee" />

The main aim of this lab is to get acquainted with data recovery for accidental or data loss for an Azure Virtual Machine.

**Task 1: Use a template to provision an infrastructure**

For the first task of this lab, I had to deploy a custome template of resources. I logged into my Azure Portal and searched deploy custom template, I selected build your own template and uploaded the template and parameters.
I then configured the resource group, username and password. 

<img width="1365" height="647" alt="Screenshot 2026-04-05 212623" src="https://github.com/user-attachments/assets/8abaf7be-0194-4fdd-8e50-ce562f54bbe5" />
<img width="1365" height="645" alt="Screenshot 2026-04-05 213138" src="https://github.com/user-attachments/assets/c62b7748-29c5-4b36-bb87-38baaa2753e9" />
<img width="1365" height="647" alt="Screenshot 2026-04-05 213224" src="https://github.com/user-attachments/assets/2972705a-2d02-42d5-9a7b-d8dcdc8aa37f" />
<img width="1365" height="647" alt="Screenshot 2026-04-05 213335" src="https://github.com/user-attachments/assets/e9548257-13d7-4105-afb1-a602bb898496" />

**Task 2: Create and configure a Recovery Services vault**

Task 2 Involves creating a recovery services vault. On the Azure Portal i searched for Recovery services vault and created a new on the recovery services page.
During creation, I had to configure the resource group and vault name then i had to verify two things once the resource services vault was created.
I had to verify the storage replication type under backup configuration and I had to ensurte that the soft delete retention is 14 days under soft delete settings.

<img width="1365" height="646" alt="Screenshot 2026-04-05 214014" src="https://github.com/user-attachments/assets/c3527acb-a95c-49a6-b915-189cb5848ab1" />
<img width="1365" height="646" alt="Screenshot 2026-04-05 214616" src="https://github.com/user-attachments/assets/ffa60805-7daa-45e3-abd4-271d5968252d" />
<img width="1365" height="645" alt="Screenshot 2026-04-05 214937" src="https://github.com/user-attachments/assets/1643e5e4-cefd-44bb-8029-c19beb99df85" />
<img width="1365" height="645" alt="Screenshot 2026-04-05 214926" src="https://github.com/user-attachments/assets/02d875a8-2b48-4ccd-ab6a-c7a3c96bee01" />

**Task 3: Configure Azure virtual machine-level backup**

On the recovery services tab, I had to create a backup. This needed some additional configuration and creating a new policy. 
Once completed I had to check the status of the new backup, It had a backup pre-check but no last backup status. I then created a new backup, accepting the default values.

<img width="1365" height="646" alt="Screenshot 2026-04-05 215613" src="https://github.com/user-attachments/assets/b7498fa0-33a9-4d1c-a4ba-f420213060f9" />
<img width="1365" height="647" alt="Screenshot 2026-04-05 220225" src="https://github.com/user-attachments/assets/7289df97-311e-4742-8afa-f69fb2cdf3f9" />
<img width="1365" height="646" alt="Screenshot 2026-04-05 220459" src="https://github.com/user-attachments/assets/875df459-28d2-464e-a0c9-5da84f1a4818" />
<img width="1365" height="648" alt="Screenshot 2026-04-05 220704" src="https://github.com/user-attachments/assets/439638c0-cb88-491c-b84e-c603b33becd2" />
<img width="1365" height="612" alt="Screenshot 2026-04-05 220719" src="https://github.com/user-attachments/assets/4c4b774d-a711-4c89-a4d5-62fb213f7842" />

**Task 4: Monitor Azure Backup**

In task 4 of this lab i had to create a storage account. After configuring the account, I then had to add a diagnostic setting to my recovery services vault.

<img width="1365" height="646" alt="Screenshot 2026-04-05 221230" src="https://github.com/user-attachments/assets/599ac54c-1428-484d-b9ad-d6af4f89a1e1" />
<img width="1365" height="647" alt="Screenshot 2026-04-05 221548" src="https://github.com/user-attachments/assets/2cd7d096-d36c-4af0-8c1c-dc89d1a6dc00" />
<img width="1365" height="645" alt="Screenshot 2026-04-05 222108" src="https://github.com/user-attachments/assets/a82fad18-168a-472c-a661-c4c257b4f934" />
<img width="1365" height="645" alt="Screenshot 2026-04-05 222341" src="https://github.com/user-attachments/assets/18c4b6f0-b33a-43cd-9cdf-746ca67492f4" />
<img width="1365" height="645" alt="Screenshot 2026-04-05 223137" src="https://github.com/user-attachments/assets/82c54e33-3f7b-4e9a-af72-09babbf460d1" />
<img width="1365" height="646" alt="Screenshot 2026-04-05 225053" src="https://github.com/user-attachments/assets/1af2ebc9-7a8a-409b-b21a-9786cfd18ebb" />

**Task 5: Enable virtual machine replication**

I couldnt complete Task 5 due to a region access issue. On my Azure for students I can only create resources on the default region which is south africa north and can't create resources on other regions.
For this task enabling distaster recovery I would need to chose a second region and can't do that as south africa west isn't available to chose and the others i'm restricted from. 

**Summary**

This lab required me to create a VM from a custom template, create a resource services vault and a storage account. The resource services vault helps with distaster recovery and backups and the backups are stored on my storage account.
This setup enables disaster recovery and automatic backups. This helps with business continuity and aids developers to be able to track their changes and their growing number of resources.


