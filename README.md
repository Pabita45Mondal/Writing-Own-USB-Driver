# 🧠 USB Driver – Linux Kernel Programming

This project demonstrates how to **write and load a simple USB driver** in the Linux kernel.  
It provides a hands-on understanding of how the **Linux USB subsystem** works — including driver registration, probe/disconnect functions, endpoint handling, and kernel logging.

---

## 📘 Overview

This example USB driver is designed for educational purposes.  
It helps you understand the step-by-step process of creating a kernel module that detects and interacts with a USB device connected to your system.

Key operations demonstrated:
- Registering and deregistering a USB driver with the kernel.
- Handling **probe()** and **disconnect()** callbacks.
- Matching a USB device by Vendor ID (VID) and Product ID (PID).
- Logging device connection and removal events.
- Building and loading a kernel module using `make`.

---

## 🧩 Concepts Covered

| Concept | Description |
|----------|-------------|
| **Kernel Modules** | Writing loadable kernel modules (`.ko` files). |
| **USB Subsystem** | Understanding the Linux USB architecture (Host ↔ Device ↔ Interface ↔ Endpoints). |
| **Driver Registration** | Using `usb_register()` and `usb_deregister()`. |
| **Device Matching** | Binding drivers using `usb_device_id` and `MODULE_DEVICE_TABLE`. |
| **Probe and Disconnect** | Handling device plug-in and removal events. |
| **Logging** | Using `printk()` and viewing logs with `dmesg`. |
| **Build System** | Creating a Makefile to compile the driver against kernel headers. |

---

## ⚙️ File Structure

