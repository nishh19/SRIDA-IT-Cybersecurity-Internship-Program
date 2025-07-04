# 🐧 Ubuntu Setup on VMware

| **OS**   | Ubuntu 22.04 LTS              |
|----------|-------------------------------|
| **RAM**  | 4 GB                          |
| **Disk** | 25 GB (Dynamically Allocated) |

---

## 🛠️ Setup Steps

1. **Download Ubuntu ISO:**  
   [https://ubuntu.com/download/desktop](https://ubuntu.com/download/desktop)

2. **Create a New VM in VMware Workstation Player:**
   - Choose **"Ubuntu (64-bit)"** as the OS type
   - Allocate the following resources:
     - **RAM:** 4 GB  
     - **CPU Cores:** 2  
     - **Disk:** 25 GB (Dynamic allocation)

3. **Boot and Install Ubuntu:**
   - Start the VM with the Ubuntu ISO
   - Follow on-screen instructions for default installation

4. **Run System Updates:**

   ```bash
   sudo apt update && sudo apt upgrade
