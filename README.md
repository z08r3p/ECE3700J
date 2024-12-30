java c
ECE3700J Introduction to Computer Organization
Lab 4 – Pipelined Processor
Purpose
This lab is intended to help you better understand the concepts of   pipelined architecture   as well   as how different instructions are executed by a pipelined processor. For simplicity purpose, we   assume   the hazard problems are all resolved by stalls in software,   so your modeled hardware   doesn’t   have to worry about hazards.
Tasks
This lab is similar to and based on the   single-cycle processor lab,   except you   will   model   a pipelined   processor in Verilog HDL that executes a bigger subset of   RISC-V instructions including:
•         The arithmetic-logical instructions   add,   addi,   sub,   and,   andi,   or,   sll,   slli,   srl,   srli,   and   sra
•         The memory-reference instructions   lw,   sw,   lb,   lbu, and   sb
•         The   jumping instructions beq, bne, bge, blt,   jal, and   jalr
Your modules must be simulated with a Verilog simulator and   synthesized by using Xilinx   synthesis   tool. This means your Verilog code must be synthesizable.   A simple RISC-V assembly testing   program without any hazard will be provided to verify that your processor can execute those instructions continuously and correctly.
FPGA   hardware implementation is NOT required for this lab.
Team Organization
This lab is a team effort. Each team should   consist   of   3   students,   randomly   grouped.   The   work   should be appropriately divided and distributed among all team members.   Students   are   not   allowed   to   switch   teams   without   permission   of   the   instructor.
Deliverables
•          Demonstration   – Every   team   should   demonstrate   to   the   teaching   group   the   following before your lab   session ends:
1)      Simulation results of   the top-module of   your design
2)      RTL   schematic   of   your   Verilog   design   generated   with   Xilinx   Vivado   software.
Each代 写ECE3700J Introduction to Computer Organization Lab 4 – Pipelined Processor
代做程序编程语言 team member should be prepared for an oral exam   on this   lab   during the   demonstration.
•          Lab   report   – The   lab   report   should   be   a   written   report   including:
1)       Brief   description   of   all   aspects   of   the   modeling   and   implementation   of   the   processor;
2)         Screen shots and brief   explanations of   simulation results for each of   the   instructions:   add, addi,   lw,   sw, beq, and   jal.
3)       RTL   schematic   of   your   Verilog   model   generated   with   Xilinx   Vivado   software;
•          Peer   Evaluation   – Each   team   member   is   required   to   provide   a   peer   evaluation   for   the   team
effort in this lab. The marks of   the peer evaluation should be   integers   ranging between   0   to   10,   inclusively, with   10 indicating the biggest contribution. A mark should be given to each   team   member   including   yourself   according   the   team   member’s   contribution   based   on   your   observation. A   brief   description   of   contribution   of   each   team   member   should   also   be   provided,   as shown in the   following   table.
Name
Level   of   contribution
(0 ~   10)
Description   of   contribution
(yourself)
   
   
(your lab partner   1)
   
   
(your lab partner 2)
   
   
•          Source   Files – All   your Verilog   source   files   and   any   other   supporting   files   should be   submitted   as appendix to the lab   report.
This is a 2-week lab. The full score   for this   lab   is   500 points.   All   required   documents   should be   submitted on Canvas before 22:00pm, July 6, 2024.
Grading
•            Lab   report: 40%
•            Demonstration: 40%
-                Working Verilog model   (simulation):   30%
-                  Individual oral exam:   10%
•            Source files and peer evaluation: 20%

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
