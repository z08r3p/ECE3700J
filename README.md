java c
ECE3700J Introduction to Computer Organization 
Lab 5 – Resolving Hazards
Purpose 
This lab is intended to take care of   data hazards and   control hazards   that   may   arise   in pipelined processors by adding forwarding mechanism, hazard detection components, and   signals   for   stalls in   hardware. 
Tasks 
This lab is based on the pipelined processor lab. You will add the necessary forwarding paths, hazard detection components, and stall mechanisms to the pipelined processor designed in previous      lab to avoid stalls in software program. For data hazard,   consider the   cases   that   have been   discussed      in the lectures only. For control hazard, assume branch is   always not taken.   The   entire   design   should   be modeled in Verilog HDL. 
The design must be simulated with a Verilog simulator of   your   choice   and   synthesized by using   Xilinx synthesis tool, meeting the following requirements:
•            Simulation results must be error-free
•          An   RTL   schematic   must   be   produced   from   the   synthesis   tool FPGA   hardware implementation is NOT required for this lab.
A simple RISC-V assembly testing program with data and control hazards will be provided for you   to verify that your processor can execute those instructions continuously and correctly.
Team Organization 
This lab is a team effort. Each team should   consist   of   3   students,   randomly   grouped.   The   work should be appropriately divided and distributed among all team members.   Students   are   not   allowed   to   switch   teams   without   permission   of   the   instructor. 
Deliverables 
• Demonstration – Every   team   should   demonstrate   to   the   teaching   group   the   following before your lab   session ends:
1)      Simulation results of   your design by executing the given RISC-V assembly program;
2)      RTL schematic generated by the synthe代 写ECE3700J Introduction to Computer Organization Lab 5 – Resolving HazardsSQL
代做程序编程语言sis tool.
Each team member should be prepared for an oral exam   on this   lab   during the   demonstration.
• Lab report – The   lab   report   should   be   a   written   report   including:
1)       Brief   description   of   all   aspects   of   the   modeling   and   implementation   of   the   processor;
2)         Screen   shots   and   brief   explanations   of   simulation   results   for   all   potential   cases   of   data hazard and control hazard.
3)       RTL   schematic   of   your   Verilog   model   generated   with   Xilinx   Vivado   software;
• Peer Evaluation – Each   team   member   is   required   to   provide   a   peer   evaluation   for   the   team
effort in this lab. The marks of   the peer evaluation should be   integers   ranging between   0   to   10,   inclusively, with   10 indicating the biggest contribution. A mark should be given to each   team member   including   yourself   according   the   team   member’s   contribution   based   on   your observation. A   brief   description   of   contribution   of   each   team   member   should   also   be   provided,   as shown in the   following   table.
Name 
Level of contribution 
(0 ~ 10) 
Description of contribution 
(yourself) 


(your lab partner 1 ) 


(your lab partner 2) 


• Source Files – All   your Verilog   source   files   and   any   other   supporting   files   should be   submitted   as appendix to the lab   report.
This is a   1-week lab. The full   score   for this   lab   is   500 points.
All required documents should be submitted on Canvas   before 22:00pm, July 13, 2024.
Grading 
•            Lab   report: 40%
•            Demonstration: 40%
-                Working Verilog model   (simulation):   30%
-                  Individual oral exam:   10%
•            Source files and peer evaluation: 20%

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
