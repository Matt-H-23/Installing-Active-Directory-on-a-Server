# Installing Active Directory on a Server 🖥️
-This lab illustrates how to install **Active Directory** on a Windows Server
### Step 1: Opening the Server Manager
- To open the **Server Manager**, select the Windows icon on the bottom left hand side, and from there you should see the **Server Manager** application on the right hand side. Go ahead and open it
![Accessing the Server](https://github.com/user-attachments/assets/2ff0aff9-3b29-4152-80f0-4dbb1b9670c9)

### Step 2: Installing Active Directory Domain Services
- Within the **Server Manager**, you are going to select **Manage** -> **Add Roles and Features** (Click **Next** until you get to 'Server Roles') -> when you get to **Server Roles** go ahead and only select **Active Directory Domain Services**
 ![AD](https://github.com/user-attachments/assets/760bbf9a-d012-4243-be4f-3df0a3f62ea1)
![Installing AD](https://github.com/user-attachments/assets/dae84a79-201f-463e-815c-0042360b7cad)
- Continue to click **Next** until you reach the the page where it asks you to install the services
- **NOTE**: Sit back and relax, it might take a couple of minutes for the services to install
![Installation](https://github.com/user-attachments/assets/42f3e154-2ad0-4372-a668-d838da9e1314)

### Step 3: Promote the Server to a Domain Controller
- After the installations of the services are completed, on the top of the **Server Manager** you are going to click on the flag with the **Caution Symbol**, and lauch the setup wizard to promote the server to **Domain Controller**
![Loom Screenshot 2025-06-06 at 08 27 25](https://github.com/user-attachments/assets/089582d2-d322-4b15-bc30-1d72baa82029)
- Upon starting the **Wizard**, select **Add New Forest**, and for the sake of fluidity, I named this one **Cyber.local** to match my locally configured AD Server on VirtualBox. However, you as the user can name it as you please. 
![Loom Screenshot 2025-06-06 at 08 28 05](https://github.com/user-attachments/assets/6e16233d-5fbf-452a-b7ba-e4798a8e80a0)
- After you click **Next**, you will be prompted to add a password for the **Domain Controller** account
![Loom Screenshot 2025-06-06 at 08 28 40](https://github.com/user-attachments/assets/59f80fa9-6464-4571-b436-3ca0607d8375)
- Click **Next** until you get stopped for the system to go through its prerequisite checks for the system
- After its finished, click **Install** on the bottom right of the wizard, and after its completed, the server will automatically restart
![Loom Screenshot 2025-06-06 at 08 30 07](https://github.com/user-attachments/assets/00e149d5-36e8-4827-a878-14fd7cd71d07)
![Loom Screenshot 2025-06-06 at 08 31 32](https://github.com/user-attachments/assets/71bc4c04-85ee-4616-b87c-b48438b8085d)

## Demo Video
- [Installing AD](https://www.loom.com/share/5ffa3356ddbd4546a3db115f6dea7bd6?sid=11ccc3da-2dc6-4be7-a745-04e7701c08ff)
