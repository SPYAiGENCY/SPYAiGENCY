# Hardware Chips and Boards Overview

This page provides a comprehensive overview of various hardware platforms, detailing the architecture types, manufacturers, SoCs, form factors, GPUs, memory types, and other related specifications. This information is useful for understanding the breadth of chips and boards offered in the market.

## 1. Architecture Types

The architecture of a processor determines the fundamental design and capabilities of a chip. The following are common architecture types:

- **ARMv7 (184)**
  - Description: ARMv7 is a 32-bit architecture used in a variety of embedded and consumer devices.
  - Common use cases: Mobile devices, embedded systems.
  
- **ARMv8 (180)**
  - Description: ARMv8 is the 64-bit successor to ARMv7, providing better performance and support for more memory.
  - Common use cases: High-performance mobile devices, servers, and IoT systems.
  
- **x86_64 (75)**
  - Description: A 64-bit architecture used primarily in personal computers and servers.
  - Common use cases: Desktops, laptops, and servers.
  
- **RV64 (13)**
  - Description: RISC-V 64-bit architecture, an open-source and growing alternative to ARM and x86.
  - Common use cases: Development boards, research, and experimentation.
  
- **ARMv7-m (9)**
  - Description: A lower-power version of ARMv7 for microcontrollers.
  - Common use cases: IoT devices, embedded systems.
  
- **MIPS32 (9)**
  - Description: A 32-bit architecture used in various embedded and networking devices.
  - Common use cases: Routers, set-top boxes, and printers.
  
- **ARMv6 (6)**
  - Description: Older 32-bit ARM architecture, now largely superseded by newer ARM versions.
  - Common use cases: Legacy devices and low-cost embedded systems.

- **Xtensa (2)**
  - Description: A configurable processor architecture, often used in custom embedded systems.
  - Common use cases: Custom chips in consumer electronics, networking, and IoT.

## 2. Manufacturers

These are the key manufacturers of processors and single-board computers (SBCs):

- **FriendlyElec (33)**
  - Known for producing cost-effective SBCs and development boards with various ARM-based SoCs.

- **Xunlong Software (33)**
  - Manufacturer of the popular Orange Pi series of SBCs.

- **DFI (27)**
  - Specializes in industrial-grade embedded systems and SBCs.

- **Sinovoip (18)**
  - Maker of the Banana Pi series, known for SBCs with ARM processors.

- **MYIR Tech (18)**
  - Provides embedded SBCs based on ARM architectures for industrial use.

- **Raspberry Pi Foundation (16)**
  - Famous for the Raspberry Pi line, offering low-cost, versatile SBCs for various applications.

- **Hardkernel (16)**
  - Makers of the Odroid series, which includes powerful SBCs for high-performance applications.

- **Pine64 (12)**
  - Known for the Pine64 series, including affordable SBCs and laptops.

## 3. System on Chip (SoC)

These SoCs power various development boards and devices:

- **Rockchip RK3399 (25)**
  - A powerful SoC featuring a 6-core CPU and Mali-T860 MP4 GPU. Common in mid-to-high-end SBCs.

- **AllWinner H3 (15)**
  - Popular SoC in affordable SBCs like the Orange Pi, featuring a quad-core ARM Cortex-A7 CPU.

- **AllWinner A20 (12)**
  - Dual-core ARM Cortex-A7 processor, often found in older budget boards.

- **AllWinner H5 (9)**
  - A quad-core ARM Cortex-A53 SoC offering better performance than the H3.

- **Rockchip RK3328 (8)**
  - A low-cost quad-core ARM Cortex-A53 processor with Mali-450 MP2 GPU.

- **Samsung S5P4418 (7)**
  - Used in devices like the Odroid-XU4, offering high performance and multi-core processing.

- **Broadcom BCM2835 (6)**
  - The SoC used in the original Raspberry Pi models.

- **Rockchip RK3566 (5)**
  - A newer Rockchip SoC with improved performance for modern applications.

## 4. Form Factor

Form factors determine the size and mounting style of the board. Some common form factors include:

- **None (408)**
  - Refers to chips and boards that are not tied to a specific form factor.

- **Pico-ITX (30)**
  - A compact form factor commonly used in embedded systems and compact computing devices.

- **Raspberry Pi (15)**
  - The form factor used by Raspberry Pi boards, known for versatility and widespread use.

- **Raspberry Pi Zero (9)**
  - A smaller, more compact version of the Raspberry Pi, ideal for low-cost projects.

- **PINE64 Model A (7)**
  - A form factor used for Pine64 boards, known for low-cost computing solutions.

- **96boards CE v1.0 (7)**
  - A standard form factor used by the 96Boards initiative, offering various configurations for development.

- **Mini-ITX (4)**
  - A larger form factor, often used for desktop and compact PCs.

- **Framework Laptop 13 Mainboard (3)**
  - The base board used in the Framework laptop, a modular system designed for repairability.

## 5. GPUs (Graphics Processing Units)

Different SBCs and chips come with varying levels of graphics power. Some of the most common GPUs are:

- **None (114)**
  - Some boards may not have an integrated GPU, relying on external graphics processing.

- **Mali-400 MP2 (33)**
  - Found in many ARM-based SBCs, providing decent graphics performance for basic tasks.

- **Mali-T860 MP4 (26)**
  - A higher-end GPU used in more powerful ARM processors like the RK3399.

- **VideoCore IV (13)**
  - The GPU used in Raspberry Pi devices, offering moderate 3D performance.

- **Intel HD Graphics (10)**
  - Integrated graphics used in many x86 platforms, providing good general performance for media and 2D/3D applications.

- **Mali-400 (8)**
  - Another version of the Mali-400, found in lower-cost devices with basic graphics needs.

- **Imagination BXE-4-32 MC1 (6)**
  - A graphics solution used in a variety of embedded devices, offering a balance of power and efficiency.

## 6. Memory / RAM (on Board or Expanded)

Memory is crucial for the performance of a device. Here are the most common types of memory found:

- **DDR (5)**
  - Standard DDR memory found in older and budget boards.

- **DDR2 (9)**
  - Slightly faster and more efficient than DDR, used in a variety of embedded systems.

- **DDR3 (144)**
  - Common in modern boards, offering a good balance of performance and power consumption.

- **DDR3l (76)**
  - A low-power version of DDR3, often used in embedded systems and laptops.

- **DDR4 (60)**
  - The latest generation of DDR memory, offering improved performance over DDR3.

- **LPDDR4 (98)**
  - Low-power DDR4, often found in mobile devices and energy-efficient SBCs.

## 7. Networking and Wireless Capabilities

Networking capabilities are essential for many projects. Here’s a summary of common options:

- **Ethernet / LAN**
  - Provides a wired connection to local networks.

  - **Power over Ethernet (PoE):**
    - **Yes (23)**: Supports PoE, allowing both power and data to be transmitted over a single Ethernet cable.
    - **No (82)**: Does not support PoE.

- **Wireless Capabilities**
  - **Wi-Fi (269)**: Many modern boards come with integrated Wi-Fi.
  - **Bluetooth (213)**: Used for short-range wireless communication with other devices.
  - **Modem (34)**: Provides cellular connectivity for IoT and remote applications.

## Conclusion

This overview highlights the diversity of chips, boards, and related hardware technologies available in the market. It is crucial to consider the architecture, manufacturer, SoC, memory, and networking capabilities when choosing the right solution for your project.
