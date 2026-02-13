<h1>Windows Server 2022/2025</h1>

<hr>

<h2>Table Contents:</h2>

<ul>
  <li>Installing Windows Server</li>
  <li>Active Directory</li>
</ul>

<br>

<h2>Installing Windows Server</h2>

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/ce2f1bba-bea3-427e-b20a-346d0b281932" />

*Figure 1: Windows Installation* 

<br>
<p>I download Windows 11 iso file from the official Microsoft website. 
I create a virtual machine name Windows Server 2025 and went through changing memory ram processor, iso file path file, size of gigabyte,
number of cores, and Display setting. After creating the first virtual machine, the picture shows from above shows at the beginning of installation.
I accept the agreement, select the Desktop Windows 2025, and create three different partitions.
</p>




<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/357167cf-d567-4d83-bf7a-29823b914207" />

<hr>

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/1caf71c4-d8ed-4dc5-a293-58d8679d37c5" />




<h2>After adding Active Directory</h2>

![Screenshot from 2025-02-10 23-24-41](https://github.com/user-attachments/assets/e75a5e14-e27b-47c0-a007-abd51b7c5fa9)

<p>
  I use Windows Server 2022 from the official Microsoft website as my domain controller VM and called OrionWolfTech
  After the Windows Server 2022 installation is finished, I went to the Windows general setting and renamed to the computer name in the system section called OrionWolfDC as my domain controller.
  In the next picture, I opened the Server manager and went to Add role to install Active Directory and other components.
  
</p>

<h2>Installing Active Directory</h2>

![Screenshot from 2025-02-10 23-31-53](https://github.com/user-attachments/assets/ac3b5dfc-ee40-48bb-9f6e-4c02fed8f909)

<p>
  A yellow triangle warnning icon showed up and this is where I setup my domain after installing Active Directory along with 4 components come with.
  In the picture, I selected add new forest radio button because I don't have other domain exist and I have to create new domain.
  After it setting up my domain, I go through other steps such as setup password for root domain credential and other procedure.
</p>


<h2>Promoting domain controller</h2>

![Screenshot from 2025-02-10 23-32-38](https://github.com/user-attachments/assets/457c2928-8c7e-44d4-9b8e-e476659d973c)

<p>
  After finish adding Active Directory and promoting my Windows Server 2022 VM Domain, I opened Active Directory: Computers and Users and created few OU and users.
</p>


