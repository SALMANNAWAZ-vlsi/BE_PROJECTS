# BE_PROJECTS
I'm Mohammed Salman Nawaz, created this repository on 05/11/2021. Curious to face new challenges and keen to learn in vast domain vlsi. In this repository you will find authentic information explained in  lucid manner regarding "Opensource Digital Frontend EDA Tools". This repository contains the following:
1. OPENSOURCE VERILOG SIMULATOR-"Icarus" also known as "iverilog"
2. OPENSOURCE WAVEFORM VIEWER-"gtkwave"
3. OPENSOURCE GRAPH VISUALIZATION SOFTWARE-"Graphviz"
4. OPENSOURCE VERILOG SYNTHESIS TOOL-"yosys"
5. VSCODE as IDE

DOWNLOAD LINK:https://drive.google.com/drive/folders/1WgWNOLdMSXDQtqfFmxVxLkStSSGlS3Rs
after installing icarus iverilog,gtkwave and graphviz
Download vscode:https://code.visualstudio.com/download (also extentions i.Verilog-HDL/SystemVerilog/Bluespec SystemVerilog and ii.Graphviz Preview).

Let's Get Started
STEP 1
Open VS studio and open folder, create master folder in any drive select folder and ok as shown below:
![image](https://user-images.githubusercontent.com/93606618/140569277-d1179002-9f86-4e27-9346-99a6169fa936.png)
<img width="495" alt="2" src="https://user-images.githubusercontent.com/93606618/140569391-e9e78b16-e2bc-4eaa-be1c-15aed39c7cbb.png">
Now click on master folder and create folders you wish to implement verilog module
![image](https://user-images.githubusercontent.com/93606618/140570509-907a631c-ae39-4076-85a4-643c60fd8462.png)
Now create fa.v and tb.v file  and write corresponding verilog code and test bench for fulladder
![image](https://user-images.githubusercontent.com/93606618/140571992-0ef75b71-1167-4ff8-a977-cb93d8bb4ed6.png)
![image](https://user-images.githubusercontent.com/93606618/140572300-eec9d019-6b04-401c-964a-1923732fbafb.png)
click on terminal, new terminal you will be in master folder. To check folders in master folder use command ls
![image](https://user-images.githubusercontent.com/93606618/140572964-8b4b9059-41f6-4673-b53a-93d1bec91a59.png)
to goto fa folder cd fa+ tab key on keyboard now u will be in fa folder to check files in fa click ls
Now we need to ensure code is functionally correct using "iverilog fa.v tb.v" new file a.out will be created
![image](https://user-images.githubusercontent.com/93606618/140573908-084293eb-787f-419b-a5ca-7721531af5ef.png)
we run a.out file by command 'vvp a.out' this provides dumb file fa.vcd 
![image](https://user-images.githubusercontent.com/93606618/140574280-6e54edaa-da0e-43c9-bbf7-87fc2b88a6cb.png)
use command gtkwave fa.vcd to get waveform 
![image](https://user-images.githubusercontent.com/93606618/140574624-311e1509-b271-4e89-8ae3-651d9ad82df8.png)
invoke yosys command for synthesis. copy and paste 'sky130_lib_verilogmodels' fa folder given above.
![image](https://user-images.githubusercontent.com/93606618/140575844-18958f94-c68e-4008-942e-dc72ff2db3a4.png)
