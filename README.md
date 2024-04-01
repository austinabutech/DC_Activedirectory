# DC_Activedirectory
Setup a basic home lab comprise of active directory and PowerShell script to create users and Add a client computer 
![Network diagram for project](https://github.com/austinabutech/DC_Activedirectory/assets/163788570/9daea1f1-1d03-4452-87ec-287f44cbb545)
<h2>Languages and Utilities Used</h2>
- <b>Windows server 2019</b><br> 
- <b>Windows 10 iso</b><br>
- <b>Virtual Box</b> 
<h2>Set up Internal and External network adaptor</h2>

![Internal network](https://github.com/austinabutech/DC_Activedirectory/assets/163788570/87c0fcf4-141e-43bb-bd58-af15c95b29d7)
<b>External obtain internet from internet, while second adaptor will obtain internet from the server</b><br> 
![NAT adaptor](https://github.com/austinabutech/DC_Activedirectory/assets/163788570/d29ef8e2-064e-4de2-84c3-63d15850735a)


![Name adaptors](https://github.com/austinabutech/DC_Activedirectory/assets/163788570/3a06651a-8346-427d-adef-ab65be56c66a)

<h2>After installing server, rename to DC domain controller </h2>

![Rename Server DC(Domain controller)](https://github.com/austinabutech/DC_Activedirectory/assets/163788570/25f9aca5-f127-46cb-b8f4-c9e6fc8d6e60)


![Configuring Internal NIC](https://github.com/austinabutech/DC_Activedirectory/assets/163788570/ac7b983b-fd29-4638-b67d-cbb90e52ca9c)


![Install active directory service on server](https://github.com/austinabutech/DC_Activedirectory/assets/163788570/6e71081a-52fd-4a71-a872-a47f46504134)


![Configuring Active Directory](https://github.com/austinabutech/DC_Activedirectory/assets/163788570/663de4d1-c6d0-42e6-8334-d00c88ca60f8)


![Create new OU(organizational unit)](https://github.com/austinabutech/DC_Activedirectory/assets/163788570/d621672f-70b3-4437-8495-9c32a811d4d1)


![Created new user and made it admin](https://github.com/austinabutech/DC_Activedirectory/assets/163788570/6bf7161b-1a9b-439e-8dbd-9ff1b4b19eec)

<h2>Install RAS(Remote Access Server)</h2>
<b>Enable users to connect remotely to a network or computer over a network connection, enabling access to resources as if they were physically connected to the network.</b>


![image](https://github.com/austinabutech/DC_Activedirectory/assets/163788570/33eff61c-af6c-48a3-9d79-6329c2165cae)

<b>Routing and Remote access enabled.</b>


![image](https://github.com/austinabutech/DC_Activedirectory/assets/163788570/eeafe6ea-2ee0-47e7-807c-ee20af9c1eb3)

<b>Setup DHCP.</b>

![image](https://github.com/austinabutech/DC_Activedirectory/assets/163788570/ee162f47-355d-4773-a329-fc80b44a7fa9)

<b>Address scope for DHCP</b>
![image](https://github.com/austinabutech/DC_Activedirectory/assets/163788570/40ef8308-e21e-44ef-948e-3f21eed067dc)

<b> Powershell script to create users</b
![image](https://github.com/austinabutech/DC_Activedirectory/assets/163788570/6a7bc39f-b626-47fb-8146-15a073835dd8)



![image](https://github.com/austinabutech/DC_Activedirectory/assets/163788570/6f93acbf-55b0-4f22-aa21-118abb15f70b)

<b>Client1 windows 10 iso setup on VM</b>

![image](https://github.com/austinabutech/DC_Activedirectory/assets/163788570/98016160-f5bd-4ff4-8cec-e6fe1be29167)

<b>Rename windows 10 CLIENT1 and add to your active directory</b>

![image](https://github.com/austinabutech/DC_Activedirectory/assets/163788570/da2e1633-bd96-4a3c-999c-8efe0f2a80d5)





