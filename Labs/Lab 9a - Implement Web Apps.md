## Lab 9a - Implement Web Apps

<img width="1284" height="706" alt="image" src="https://github.com/user-attachments/assets/2d89da1d-787a-48d2-9d5e-bcafb1c7749d" />


**Task 1: Create and configure an Azure web app**

To start this lab i had to create a new Azure wb app. I configured it's settings including creating a new resource group, pricing plans and runtime. The web app was created as shown by the screenshot.
I then accessed the Azure web app to see it's contents.

<img width="1365" height="647" alt="Screenshot 2026-04-03 192238" src="https://github.com/user-attachments/assets/94001208-366e-4a24-842f-110e23a1993c" />
<img width="1365" height="645" alt="Screenshot 2026-04-03 194034" src="https://github.com/user-attachments/assets/d7b60772-363b-480d-8598-d72453612f75" />

**Task 2: Create and configure a deployment slot**

In this task I created a new deployment slot for my web app. The deployment slot allows me to test new updates and swap production with the testing slot to bring the updates live. 

<img width="1365" height="646" alt="Screenshot 2026-04-03 194528" src="https://github.com/user-attachments/assets/8119aff5-c8d0-4cec-a1d5-1fcf642942a1" />
<img width="1365" height="646" alt="Screenshot 2026-04-03 194951" src="https://github.com/user-attachments/assets/bded32ee-6b85-435d-b380-ae8d721fd8db" />
<img width="1365" height="647" alt="Screenshot 2026-04-03 195122" src="https://github.com/user-attachments/assets/a8a62eed-f76c-49b5-b567-96aace7d6783" />

**Task 3: Configure web app deployment settings**

In this section, I configured the web app deployment setting. I added new content to the testing slot by adding code from an external git repo. I had to insert the git repo link and specify the branch.
I then accessed the testing slot to see if my changes are live in the testing slot and it displayed "Hello World" which shows my updates to the testing slot are live.

<img width="1365" height="646" alt="Screenshot 2026-04-03 195352" src="https://github.com/user-attachments/assets/238a189e-4b6f-4d4c-9a7e-318e448b3028" />
<img width="1365" height="646" alt="Screenshot 2026-04-03 195524" src="https://github.com/user-attachments/assets/45ea3f24-0177-4597-9db0-d8c5bd0d5739" />
<img width="1365" height="647" alt="Screenshot 2026-04-03 195542" src="https://github.com/user-attachments/assets/ad87e5a6-4bb8-44e2-a17e-dd628b179d28" />

**Task 4: Swap deployment slots**

In this section, I swapped the testing and production slot to bring my updates live. I did this and it worked perfectly and verified the production slot. 
When i accessed it's web app link it displayed 'Hello World" and previsouly in step 1 it displayed the default Azure message to show it's live and ready to display content.

<img width="1365" height="645" alt="Screenshot 2026-04-03 195841" src="https://github.com/user-attachments/assets/72aefc89-81c9-4031-a89b-6c60af946ca9" />
<img width="1365" height="644" alt="Screenshot 2026-04-03 200006" src="https://github.com/user-attachments/assets/f366e25a-29e5-40c1-b692-0fdce459676d" />
<img width="1365" height="644" alt="Screenshot 2026-04-03 200213" src="https://github.com/user-attachments/assets/aacf05ab-1d0c-4959-bb75-03ed80114a1d" />
<img width="1365" height="646" alt="Screenshot 2026-04-03 200220" src="https://github.com/user-attachments/assets/0ab66f5d-3ab8-4ce8-ac27-d2f073438ae0" />

**Task 5: Configure and test autoscaling of the Azure web app**

I couldn't do task 5 due to a region mismatch for my Azure subscription. Essentially I am unable to use any other region except southafricanorth in my Azure Student Subscription. I'll contact support and request for more regions.











