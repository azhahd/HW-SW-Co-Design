# HW-SW Co-Design with MicroBlaze & ARM

This project demonstrates a comprehensive hardware-software co-design process completed using both softcore and hardcore processors. The MicroBlaze softcore processor was used to control 16-bit LEDs via the AXI GPIO block, driven by 16-bit input switches. The hardware was successfully configured on the Artix-7 FPGA using the Digilent Nexys A7 board. Additionally, the ARM Cortex-A9 hardcore processor was instantiated on a Zynq FPGA, incorporating BRAM and GPIO IP blocks to handle performance profiling for applications such as “Hello World” and matrix operations. Custom IP blocks were designed and integrated, facilitating seamless interaction between programmable logic and embedded processing units.

The project demonstrated the advantages of this hybrid approach, where the MicroBlaze processor effectively managed basic input-output tasks while the ARM Cortex-A9 provided deeper analysis and profiling capabilities. This configuration emphasized the adaptability of the system, leveraging both processors to achieve balanced and efficient performance. The waveforms and results confirmed that the hardware and software components functioned harmoniously, addressing potential bottlenecks and ensuring smooth operation.

The significance of this project lies in its clear illustration of how hardware and software integration can optimize embedded system performance. By blending softcore and hardcore processors, this design offered a flexible solution capable of supporting varied applications. The outcome provided a strong basis for further exploration in real-world scenarios where versatile and efficient embedded systems are critical.

Lab Summaries

Lab 1 focused on the creation and configuration of the MicroBlaze soft processor, demonstrating control over 16-bit LEDs using switch inputs and verifying the setup through C code execution.

Lab 2 expanded on this by profiling application performance using the ARM Cortex-A9 processor on the Zynq FPGA, analyzing its interaction with BRAM and GPIO IP blocks for efficient data handling.

Lab 3 demonstrated the creation of custom IP blocks and their integration with the Zynq-7000 hardware processor to build a robust and adaptable embedded system, successfully combining software and hardware components for optimal functionality.
