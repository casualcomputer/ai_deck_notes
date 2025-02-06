# Checklist for Installing AI Applications

This checklist lists various considerations for installing Python-based, open-source web apps on work computers. Some web apps are self-contained and can run without the internet (local applications), while others require internet access for making API calls.

---

## 1. Verify Hardware Requirements
### Does the AI app require specialized hardware?
✅ **Yes** → Check the following:
- **GPU Requirements**  
  - Does the app require a specific type of GPU (e.g., NVIDIA, AMD)?  
  - Verify if the GPU must meet certain specifications (e.g., CUDA support, VRAM size, CUDA’s Compute Capability).
- **Dedicated Servers or Cloud Infrastructure**  
  - Does the app require access to dedicated hardware or cloud resources (e.g., AWS, Azure)?
- **System Specifications**  
  - Does your system meet the required RAM, CPU, storage, and network bandwidth for smooth operation?

### Can your current hardware support the app?
✅ **Yes** → Proceed to the next step.  
❌ **No** → Consider alternatives:
- 🔍 **Procurement:** Can you request additional hardware (e.g., high-performance laptops with GPUs)?  
- 🔍 **Department Resources:** Are there server computers (with the required hardware) within your department that you could access?  
- 🔍 **Cloud Access:** Can you leverage cloud infrastructure (e.g., AWS EC2, Azure) for GPU-heavy workloads?  

---

## 2. Check for Software, Dependencies, and API Requirements
### Does the AI app require additional software or libraries to run?
✅ **Yes** → List the necessary components (e.g., specific Python libraries, containerization software like Docker, Anaconda).  
❌ **No** → Continue to the next consideration.

### Does the AI app require external API access or internet connectivity?
✅ **Yes** → List the required API endpoints or external services (e.g., LLM API endpoints from AWS, Azure, or other cloud-based APIs).  
❌ **No** → Continue to the next consideration.

> **Note:** If the application requires external API calls, approval from your **IT Branch**, **AI Centre of Expertise**, or **Chief Data Office** may be required. Check with these teams before proceeding with installation.

---

## 3. Verify Department Approval
### Is the software (and its dependencies) approved by your department?
✅ **Yes** → Verify that the approved software and services are compatible with the AI app.  
❌ **No** → Can you request approval for the software and API usage?
- 🔍 **Who is responsible for approvals?** (e.g., IT Security, Procurement, Legal, AI Centre of Expertise, Chief Data Office)  
- 🔍 **Approval Process & Timeline:** What’s the process, and how long does it typically take? Does your project deadline fit within the approval timeline?

### Costs and Requirements for Software Approval:
- 🔍 **Licensing:** What are the licensing requirements and costs for the software?  
- 🔍 **Cloud Access or External Dependencies:** Does the app need cloud resources or APIs? Ensure this is compatible with your environment.  

---

## 4. IT Support for Setup and Configuration
### Can your team install and use the software and hardware independently?
✅ **Yes** → Can your team set up the software and hardware without IT support?  
❌ **No** → Consider:
- 🔍 **IT Staff Requirements:** Will you need specific IT staff (e.g., CS, IT support) for setup and maintenance?  
- 🔍 **Installation Restrictions:** Is there a policy restricting local installations, or is installation allowed in virtualized environments?  

---

## 5. Check Access and Network Requirements
### Are there any access or network-related barriers to running the AI app?
- 🔍 **Network Configuration:** Does the app require firewall changes, VPN access, or special network configurations?  
- 🔍 **External Dependencies:** Does the AI app need access to external data sources, cloud services, or APIs?  
- 🔍 **Special Permissions:** Are there any specific permissions needed for accessing GPUs, external APIs, or cloud infrastructure?  

---

## 6. Confirm Security and Compliance
### Does the software meet IT Privacy Impact Assessments/security standards?
- 🔍 **Security Assessment:** Has the software undergone a security review or Privacy Impact Assessment (especially if working with Protected B data)? Are there any concerns regarding data privacy, protection, encryption, or vulnerabilities?  

### Hardware Maintenance:
- 🔍 **Support for Hardware:** Does your department offer support for specialized hardware (e.g., GPUs)?  
- 🔍 **Software Updates:** What is the process for maintaining the software, especially if it’s running on specialized hardware?  
