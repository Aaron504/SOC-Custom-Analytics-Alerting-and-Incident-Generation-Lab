# SOC Custom Analytics Alerting and Incident Generation Lab
<p align="center">

![Screenshot 2024-10-13 165544](https://github.com/user-attachments/assets/ec1cb1a7-9cbe-4eec-ae4d-0cc2acfc4d0e)

</p>

In this lab, I configured multiple custom analytics rules in Azure Sentinel to monitor and detect potential security threats. These rules were designed to trigger alerts and generate incidents based on both simulated attack traffic from an "attack-vm" and real-time malicious traffic from the Internet. The lab involved understanding the logic behind each custom rule, setting up appropriate alerting mechanisms, and validating the effectiveness of the rules by monitoring triggered incidents. This project showcases my ability to implement advanced threat detection, alerting, and incident response within a SOC environment.






<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Microsoft Sentinel
- Log Analytics Workspace

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1 - Import all of our Sentinel Analytics Rules
- Step 2 - Select the “CUSTOM: Brute Force SUCCESS - Windows” Alerts and “Edit” it:


<h2>Deployment and Configuration Steps</h2>

- Import all of our Sentinel Analytics Rules
![Screenshot 2024-10-13 163302](https://github.com/user-attachments/assets/e95559c3-46b6-4f5d-a87e-eb157416807f)
![Screenshot 2024-10-13 163447](https://github.com/user-attachments/assets/1da80746-d8de-4228-a80c-894caa645019)

- Select the “CUSTOM: Brute Force SUCCESS - Windows” Alerts and “Edit” it:
![Screenshot 2024-10-13 163807](https://github.com/user-attachments/assets/ef90f88d-2cb6-4542-9e36-8e6068308f00)

- Here you can see incidents are being generated from the query list we imported in the previous steps
![Screenshot 2024-10-13 165041](https://github.com/user-attachments/assets/9a0ada66-3816-46b8-9ef9-922877e0a242)





