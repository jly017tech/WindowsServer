<h1>Windows Server 2022/2025</h1>

<hr>

<h2>Table Contents:</h2>

<ul>
  <li>Installing Windows Server</li>
  <li>Server Manager</li>
  <li>Active Directory and Services</li>
  <li>Promoting Domain Controller</li>
  
</ul>

<h2 align="center">Installing Windows Server</h2>


<div align="center">
  <table>
    <tr>
      <td valign="bottom">
        <img src="https://github.com/user-attachments/assets/ce2f1bba-bea3-427e-b20a-346d0b281932" width="620" height="300" alt="Step 1" /><br>
        <sub><b>Fig 1:</b> Initial Boot</sub>
      </td>
      <td valign="bottom">
        <img src="https://github.com/user-attachments/assets/357167cf-d567-4d83-bf7a-29823b914207" width="620" height="300" alt="Step 2" /><br>
        <sub><b>Fig 2:</b> OS Selection</sub>
      </td>
      <td valign="bottom">
        <img src="https://github.com/user-attachments/assets/1caf71c4-d8ed-4dc5-a293-58d8679d37c5" width="620" height="300" alt="Step 3" /><br>
        <sub><b>Fig 3:</b> Partitions</sub>
      </td>
    </tr>
  </table>
</div>



<p>I download Windows 11 iso file from the official Microsoft website. 
I create a virtual machine name Windows Server 2025 and went through changing memory ram processor, iso file path file, size of gigabyte,
number of cores, and Display setting. After creating the first virtual machine, the picture shows from above shows at the beginning of installation.
I accept the agreement, select the Desktop Windows 2025, and create three different partitions. It took 2-3 minutes finishing installing Windows 2025 Desktop GUI.
Once it finishes installation, the virutal machine reboots and shows a administrator and password page.  
</p>

<h2>Server Manager </h2>

![Screenshot from 2025-02-10 23-24-41](https://github.com/user-attachments/assets/e75a5e14-e27b-47c0-a007-abd51b7c5fa9)

<p>
  The first step is I rename the computer name to HuskyTech-DC, so it will add in the Windows Active Directory: Users and Computers after setting up static IP address,
  DHCP server, and DNS server.
  
</p>

<h2>Installing Active Directory and other services</h2>

![Screenshot from 2025-02-10 23-31-53](https://github.com/user-attachments/assets/ac3b5dfc-ee40-48bb-9f6e-4c02fed8f909)

<p>
  A yellow triangle warning icon showed up and this is where I setup my domain after installing Active Directory along with 4 components come with.
  In the picture, I selected add new forest radio button because I don't have other domain exist and I have to create new domain.
  After it setting up my domain, I go through other steps such as setup password for root domain credential and other procedure.
</p>

<br>

<img width="1599" height="853" alt="Screenshot from 2026-02-13 08-18-16" src="https://github.com/user-attachments/assets/5e4ecc11-76b5-411b-8850-528fcc9da42a" />
        <sub><b>Fig 3:</b> Server roles</sub>



<h2>Promoting domain controller</h2>

![Screenshot from 2025-02-10 23-32-38](https://github.com/user-attachments/assets/457c2928-8c7e-44d4-9b8e-e476659d973c)

<p>
  After setting up OrionWolfDC Domain, I go ahead promote and went through each steps and click start and restarting the computer once it checks its prequisities. 
</p>


