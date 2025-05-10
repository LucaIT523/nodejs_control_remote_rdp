<div align="center">
   <h1>nodejs_control_remote_rdp</h1>
</div>



### **1. Core Architecture**

This code implements **Windows Remote Desktop Services automation** through WinRM protocol integration. 

It provides centralized user lifecycle management with policy-based credential control.



------

### **2. Key Components**

#### **2.1 WinRMMng Class**

**Core Features**:

- WinRM command execution ,
- 10-second command timeout control,
- Multi-stage user management operations.

**Critical Methods**:

```
javascriptCopycreateRDPUser()      // User creation + RDP group assignment

changeRDPUserPasswd()// Password rotation

deleteRDPUser()      // Account removal

deleteRDPSession()   // Active session termination

```

#### **2.2 AutoCreateAndDelUser_RDP**

- Policy-driven user provisioning
- Temporary vs permanent credential management
- Credential storage integration


This implementation demonstrates a robust Windows RDP automation solution suitable for enterprise environments requiring centralized remote access management. 

The combination of active session management and policy-driven credential rotation makes it particularly effective for temporary access scenarios.



### **Contact Us**

For any inquiries or questions, please contact us.

telegram : @topdev1012

email :  skymorning523@gmail.com

Teams :  https://teams.live.com/l/invite/FEA2FDDFSy11sfuegI