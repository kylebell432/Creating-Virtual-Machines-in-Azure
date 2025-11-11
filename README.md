# Creating-Virtual-Machines-in-Azure

<img width="1200" height="627" alt="image" src="https://github.com/user-attachments/assets/83cfd68e-e19c-419b-a8b6-f64384786f09" />


This walkthrought is going to briefly go over what it would look like if you wanted to create a virtual machine using Microsoft Azure.
A virtual machine (VM) is an operating system running inside of another operating system (Windows inside of Windows). They are useful for testing out stuff without "dirtying up" your Computer.



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Remote desktop installed
- A free/paid microsoft azure account


<h2>Creating the virtual machine steps</h2>

<img width="992" height="500" alt="image" src="https://github.com/user-attachments/assets/c902ccf4-4797-4da5-924e-f3dd3d33014a" />

Create a resource to have a place for your virtual machine and make sure that you use the same region for both the group and the machine.
</p>
<br />

<img width="729" height="822" alt="Screenshot 2025-11-11 113655" src="https://github.com/user-attachments/assets/2f8f5224-22bc-4d58-b75b-7e8cd2101468" />

Now create a virtual machine within the group you created and make sure that you have it filled out the same way in the image above. Also at the bottom of the page make sure you clicke on the licensing agreement or it will not work.
</p>
<br />

<img width="901" height="359" alt="Screenshot 2025-11-11 114434" src="https://github.com/user-attachments/assets/d2a9e6d9-22fb-4e70-b178-a6063137b1e0" />

<img width="542" height="298" alt="image" src="https://github.com/user-attachments/assets/a9f31269-a937-44e5-82cf-ede86d603bfc" />


Once you VM is create of use it open remote desktop and put the public ip address that you VM has. After using the username and password you created you should be able to use the AM like a normal computer.
</p>
<br />
