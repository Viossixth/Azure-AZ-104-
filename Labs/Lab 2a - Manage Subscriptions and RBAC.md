## Manage Subscriptions and RBAC

<img width="1606" height="449" alt="image" src="https://github.com/user-attachments/assets/436b6883-1442-4ccb-90e2-16c7561f1d87" />

## Job skills

**Task 1: Implement management groups.**

A Management group is a group intended for a particular set of resources to be managed and used by staff who have the relevant access. It aids in promoting Role Based Access.
Management groups allow for segmentation for resources/subscriptions giving a set of users a specific set of resources which they are only permitted/ need to use for their role.

<img width="1365" height="647" alt="Screenshot 2026-03-27 164604" src="https://github.com/user-attachments/assets/143d13f7-60e6-4584-b843-dca7293c2334" />

**Task 2: Review and assign a built-in Azure role.**

Task 2 comprises of creating a role for the Helpdesk team. I must add the Virtual Machine Contributor role to the management group and add the Helpdesk group as a member with that role to the management group.

<img width="1365" height="647" alt="Screenshot 2026-03-27 164604" src="https://github.com/user-attachments/assets/54b323d7-a69b-4106-bd34-56bc7cef521c" />
<img width="1365" height="647" alt="Screenshot 2026-03-27 165627" src="https://github.com/user-attachments/assets/ec191ce4-bdba-4025-acd2-314306059901" />
<img width="1365" height="646" alt="Screenshot 2026-03-27 165701" src="https://github.com/user-attachments/assets/d7628ce9-f0a1-4400-810a-b802d7df9e41" />

**Task 3: Create a custom RBAC role.**
 For this section i created a custom Role Based Access Control role, i used a standard role but customised it according to my needs.
 
<img width="1365" height="645" alt="Screenshot 2026-03-27 170932" src="https://github.com/user-attachments/assets/af4fb701-a46a-499a-9bea-30dd1b51dff1" />
<img width="1365" height="646" alt="Screenshot 2026-03-27 170441" src="https://github.com/user-attachments/assets/d1f05c0f-1f74-4e73-8fbb-eebc1fe488b4" />
<img width="1365" height="646" alt="Screenshot 2026-03-27 170910" src="https://github.com/user-attachments/assets/03872dc7-008d-4f3f-b739-46ca1abe64c1" />

**Task 4: Monitor role assignments with the Activity Log.**

For this section I went to the Activity Log within the Management group to review if any changes had taken affect. The screenshot shows the custom role that was created earlier and previous activity.

<img width="1365" height="645" alt="Screenshot 2026-03-27 174233" src="https://github.com/user-attachments/assets/cf99283b-d62d-409c-ac84-e86ddd9e7d23" />

**Summary**

In this lab i created a management group to enforce the principle of least priviledge and to make sure the resources that users have access to are aligned with their scope of work.
RBAC is an essential part of security and Management groups are one way to enforce it.
