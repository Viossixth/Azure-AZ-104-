## Lab 2b - Manage Governance via Azure Policy

<img width="1417" height="723" alt="image" src="https://github.com/user-attachments/assets/887df083-4eb3-48fd-874d-275feebd8f16" />

The aim of this lab is tofamiliarise myself with resource management in Azure. Using Azure locks, Azure policy and tags as a means of tracking, policing the creation of resources and managing them.

**Task 1: Create and assign tags via the Azure portal**

To create a tags i signed into the Azure Portal, selected Storage disks and the resource group available. I then click add tags, create the new tag

<img width="1190" height="614" alt="Screenshot 2026-03-27 205831" src="https://github.com/user-attachments/assets/cc8f6d0d-3f72-4df0-b30d-4c7eeeace18d" />
<img width="1190" height="613" alt="Screenshot 2026-03-27 205903" src="https://github.com/user-attachments/assets/f2e0ff7c-9bd9-4dc6-9fb9-e9188bd8e691" />
<img width="1191" height="612" alt="Screenshot 2026-03-27 210100" src="https://github.com/user-attachments/assets/22f1ea7a-43d5-4d55-a8c0-b2a51854257d" />

**Task 2: Enforce tagging via an Azure Policy**

To enforce an azure policy for tagging, on the main Azure Portal i searched for Policy and went to the policy page. I went to the definitions, selected the tags property under the category drop down menu.
I selected the "Require Cost Center tag and its value on resources" and created the new policy.

<img width="1192" height="615" alt="Screenshot 2026-03-27 211838" src="https://github.com/user-attachments/assets/4932adf0-af23-4385-a270-1fe8fb9d7776" />
<img width="1193" height="613" alt="Screenshot 2026-03-27 211920" src="https://github.com/user-attachments/assets/3359aabd-1c91-4d40-be09-7fbde034f5f0" />
<img width="1191" height="611" alt="Screenshot 2026-03-27 212005" src="https://github.com/user-attachments/assets/b7815146-9534-49b1-b7ab-b7e8d7f0418d" />

**Task 3: Apply tagging via an Azure Policy**
 
 To achieve tagging via an Azure Policy i searched for Policy on Azure Portal, go to the Authoring table and selected definitions.
 I looked for the "Require a tag and its value on resources"and clicked Assign Policy.
 I specified the scope and confirgured a few more settings and created the policy. I then went to storage accounts and created a new storage account.
 
<img width="1191" height="614" alt="Screenshot 2026-03-27 214158" src="https://github.com/user-attachments/assets/408e5ae8-c2b3-411f-a43a-1a19e1479ba5" />
<img width="1191" height="612" alt="Screenshot 2026-03-27 220933" src="https://github.com/user-attachments/assets/223ac883-e03a-4991-8fc3-e784464d2199" />
<img width="1193" height="614" alt="Screenshot 2026-03-27 221001" src="https://github.com/user-attachments/assets/5c3375d6-75d8-4eac-8d49-2dc2debd7ffa" />
<img width="1192" height="612" alt="Screenshot 2026-03-27 221032" src="https://github.com/user-attachments/assets/30c6105c-a1e5-4eac-a0b0-10a0de01fa8f" />
<img width="1189" height="610" alt="Screenshot 2026-03-27 221102" src="https://github.com/user-attachments/assets/616120e2-bfd9-4829-b66f-741d4de44b60" />

**Summary**

In this lab i learnt how to use Azure Policy as a means to govern my resources properly, to limit how resources are used and created. Tags were also created to keep track of new resources and making their management easy.
