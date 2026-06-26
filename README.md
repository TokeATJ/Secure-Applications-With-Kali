This project documents the deployment and validation of a Kali Linux virtual machine within VMware Workstation. The objective was to establish a functional cybersecurity testing environment and demonstrate foundational Linux administration skills commonly used in penetration testing, digital forensics, and security operations.

---

## Environment

| Component | Description |
|------------|-------------|
| Operating System | Kali Linux |
| Hypervisor | VMware Workstation |
| User Account | Root |
| Network Configuration | DHCP |
| Interface Validation | ifconfig |
| Connectivity Testing | wget |

---

## Learning Objectives

- Deploy a Kali Linux virtual machine
- Verify network connectivity
- Practice Linux file management
- Understand Linux permissions
- Execute scripts from the terminal
- Navigate the Linux file system
- Perform basic user administration tasks

---

# Network Configuration Validation

The first step was validating that the Kali Linux virtual machine successfully received an IP address and could communicate externally.

## Commands

```bash
ifconfig

```

## Evidence

<img width="710" height="409" alt="image" src="https://github.com/user-attachments/assets/2af62431-80bb-4a3e-bcf9-358a5f9faae6" />

### Outcome

- Confirmed DHCP-assigned IP address
- Verified network adapter functionality
- Confirmed Internet connectivity

---

# File Creation and Editing

A text file was created and modified using basic Linux commands.

## Commands

```bash
cat myfile.txt
echo 'echo "inside the file";' > myfile.txt

```

## Evidence
<img width="642" height="596" alt="image" src="https://github.com/user-attachments/assets/e0e90ddc-2f7b-4961-8bca-b99ba17d4c4b" />
<img width="610" height="490" alt="image" src="https://github.com/user-attachments/assets/82c299ce-e4de-485a-9873-98ec93610831" />


### Outcome

- Created a new file
- Added content to the file
- Displayed file contents

---

# File Management and Permissions

The file was copied, renamed, granted execute permissions, and executed.

## Commands

```bash
cp myfile.txt myfile-copy.txt

mv myfile.txt script.pl

chmod g+x script.pl

./script.pl
```

## Evidence

<img width="616" height="483" alt="image" src="https://github.com/user-attachments/assets/cb37961b-c76e-45b6-992c-117e23a22961" />


### Outcome

- Copied a file
- Renamed a file
- Modified group execute permissions
- Executed a script

---

# Directory Management

Basic directory creation, deletion, and navigation commands were performed.

## Commands

```bash
rm script.pl

ls

mkdir newOne

rmdir newOne

cd ..

cd /
```

## Evidence

<img width="664" height="540" alt="image" src="https://github.com/user-attachments/assets/e595133a-41df-4cac-9d7a-ba3dca26bd9d" />


### Outcome

- Deleted files
- Created directories
- Removed directories
- Navigated the Linux filesystem

---

# User and System Validation

System-level commands were used to identify the logged-in user and current working directory.

## Commands

```bash
passwd

whoami

pwd

man touch
```

## Evidence

<img width="617" height="519" alt="image" src="https://github.com/user-attachments/assets/f20be6e5-0a6c-4f37-a621-4e0a65950da4" />


### Outcome

- Identified active user account
- Displayed working directory
- Accessed local command documentation

---

# Skills Demonstrated

- Kali Linux Administration
- VMware Workstation
- Linux Command Line
- File Management
- Linux Permissions
- Script Execution
- DHCP Troubleshooting
- Network Connectivity Validation
- Directory Navigation
- User Administration

---

# Security Relevance

Kali Linux is widely used by security professionals for penetration testing, vulnerability validation, incident response, and digital forensics. This lab established a working security workstation and reinforced the Linux fundamentals required for more advanced cybersecurity activities.

---

# Key Takeaways

- Successfully deployed a Kali Linux virtual machine
- Validated network connectivity and Internet access
- Practiced Linux file and directory management
- Learned Linux permission structures
- Executed scripts through the command line
- Built foundational skills required for offensive security and forensic analysis

---

# Resume Alignment

**Built and validated a Kali Linux virtualized security workstation, configured network connectivity, and performed Linux administration tasks including file management, permission modifications, script execution, and system navigation.**
