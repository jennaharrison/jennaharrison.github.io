---
layout: project
type: project
image: img/fpga/fpga-logo.jpg
title: "FPGA Digital Logic"
date: 2026
published: true
labels:
  - Verilog
  - FPGA
  - Digital Logic
  - Hardware
summary: "Designed and programmed digital logic circuits on an FPGA board using Verilog, including multiplexers and switch-controlled LEDs."
---

I worked with an FPGA development board to design and implement digital logic circuits using Verilog. These projects gave me hands-on experience programming hardware and testing digital circuits using the physical inputs and outputs on the board.

### 1-Bit Multiplexer

<img class="img-fluid" src="../img/fpga/multiplexor1.jpg" style="width="200px;">

Created a 1-bit 2-to-1 multiplexer in Verilog. The circuit uses a switch to select between two inputs and displays the selected output on the FPGA board.

### 2-Bit Multiplexer

<img class="img-fluid" src="../img/fpga/2bit-multiplexor.jpg" style="width="200px;">

Expanded the multiplexer to two bits, allowing the circuit to select between two 2-bit inputs. This project helped me apply digital logic concepts to a bigger data path.

### Switch-Controlled LEDs

<div style="display: flex; gap: 20px;">
  <img class="img-fluid" src="../img/fpga/led-switch2.jpg" style="width="200px;">
  <img class="img-fluid" src="../img/fpga/led-switch1.jpg" style="width="200px;">
</div>

Connected the FPGA board's input switches to its output LEDs using Verilog dataflow modeling. Each switch controls a corresponding LED, demonstrating how changing the switch inputs changes the LED outputs.
