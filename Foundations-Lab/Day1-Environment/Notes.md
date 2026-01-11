\# Day 1 - Virtual lab Environment Notes



\## Date

11-01-2026



\## Objective

Document the setup and initial observations of a Windows virtual machine environment

for hands-on cybersecurity labs.



\## Environment Details

* Hypervisor: VMware Workstation 17 Pro
* Hypervisor Version: 17.6.4 build-24832109
* Host OS: Windows 11 Pro (21H2)
* Guest OS:
* VM Resources: 2GB Ram, 2 CPU cores, 60GB storage
* Snapshot: Day1-Clean-Baseline



\## Tasks Completed

1. Installed VMware hypervisor
2. Created and installed a Windows 10 VM

3\. Configured VM resources (RAM, CPU, Storage)

4\. Completed Initial Windows setup (username, password, updates)

5\. Took baseline screenshots of:

   - VM running

   - OS version

   - Snapshot confirmation

6\. Took snapshot of clean VM

7\. Installed VMware Tools to optimise usage of the VM

8\. Observed system processes, services, and users



\## Observations

* Windows default settings allow basic user interaction immediately.
* Default processes and services can be observed in Task Manager.
* Snapshots provide a reliable baseline to return to after experiments.



\### Processes

* 'explorer.exe' - Windows Explorer, default GUI process
* `svchost.exe` – Host for multiple Windows services
* `winlogon.exe` – Responsible for user login sessions

\*(Note: all default processes were running; no suspicious activity observed)\*



\### Services

* Windows Update service running
* DHCP Client running
* Event Log service running

\*(Default services; baseline behavior noted)\*



\### Users

* Administrator account created during setup
* Default Guest account disabled
* User account enabled



\## Lessons Learned

1\. Always start with a clean baseline VM.

2\. Document all configuration steps and resources.

3\. Snapshots are critical to maintain a safe lab environment.

4\. Understanding the host vs guest relationship is essential for lab security.



\## Evidence

* hypervisor-installed.png
* snapshot-baseline.png
* task-manager.png
* user-information.png
