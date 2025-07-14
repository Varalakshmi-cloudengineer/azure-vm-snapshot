# Azure VM Snapshot (Live Snapshot)

This project demonstrates how to create a **snapshot of a running Azure Virtual Machine's OS disk**, without stopping the VM.

## 🛠️ What Was Done

- Navigated to the Virtual Machine > Disks > OS Disk.
- Created a full snapshot while the VM was **still running**.
- Snapshot type used: **Full**
- Storage type selected: **Standard HDD**
- Snapshot was created in the same region as the VM.

## 💡 Why Take a Snapshot While Running?

- In real-time environments, it's sometimes necessary to take a backup **without stopping production VMs**.
- Although stopping the VM ensures full data consistency, snapshots while running are still valid for backup, cloning, and disaster recovery.

## 📸 Screenshots Included

- VM Overview
- Disk overview
- Snapshot creation form
- Confirmation of snapshot creation

## ✅ Status

Snapshot created and verified successfully from a running VM on the Azure portal.

## 🔐 Notes

- This snapshot can be used to create a new managed disk or a new VM.
- Useful for quick backups during maintenance windows or before risky operations.
