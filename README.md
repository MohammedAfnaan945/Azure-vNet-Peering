# Azure-vNet-Peering

**📘 Overview**

This project demonstrates the creation and configuration of two virtual networks (vNet-1 and vNet-2) in Microsoft Azure and how to establish VNet Peering between them. VNet Peering enables seamless communication between resources in different virtual networks.

**🎯 Purpose of the Project**

-Understand how to create multiple VNets within the same Azure region.

-Learn how to peer two virtual networks for private internal communication.

-Simulate a real-world scenario of network segmentation and internal communication setup across subnets and VNets.

-Strengthen Azure Networking fundamentals through hands-on practice.

**🔄 Steps Performed:**

**Step1- Created a resource group VNet-Demo in the South India region.**
<img width="1920" height="1020" alt="Screenshot 2025-07-23 172630" src="https://github.com/user-attachments/assets/4e6b8094-5d69-4f58-bd63-ac9d6206bc6c" />

**Step2- Created two separate virtual networks:** (vNet-1 with subnet range 10.0.0.0/16) and (vNet-2 with subnet range 10.1.0.0/16)

<img width="1920" height="1020" alt="Screenshot 2025-07-23 172223 - Copy" src="https://github.com/user-attachments/assets/a746332a-d043-4908-8ad4-b04523ff328c" />
<img width="1920" height="1020" alt="Screenshot 2025-07-23 172615" src="https://github.com/user-attachments/assets/700aabd9-cdb6-4862-90b1-f39f33ae373f" />

**Step3- Configured VNet Peering between vNet-1 and vNet-2:** Enabled access from vNet-1 to vNet-2 and Verified Peering State as Connected
<img width="1920" height="1020" alt="Screenshot 2025-07-23 173035 - Copy" src="https://github.com/user-attachments/assets/423a2f30-1937-45b6-929e-bca1e81c2c82" />
<img width="1920" height="1020" alt="Screenshot 2025-07-23 173053" src="https://github.com/user-attachments/assets/38ae726c-0496-41b8-894b-f14da8eac744" />

**✅ Outcome**: 

-Successful deployment and peering of two virtual networks.

-Demonstrated the ability to configure secure private network communication between VNets.

-Gained deeper insights into Azure Networking.



**📌 Technologies Used**:

Microsoft Azure Portal, Azure Vnet, Vnet Peering, Resource Groups


**👨‍💻 Author**

Mohammed Afnaan
