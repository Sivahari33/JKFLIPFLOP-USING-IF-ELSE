NAME: K.Sivaharibalan
DEPT:IT
REG NO: 212224220103
# JKFLIPFLOP USING VERILOG

**AIM:** 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**JK Flip-Flop**

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

![300541519-a649c30b-232b-4558-b188-fd6c09845180](https://github.com/user-attachments/assets/f2644875-011f-4c79-bfce-9933c194f0aa)



This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![300541618-c4360742-e8a8-4937-b089-c46c0433f9a3](https://github.com/user-attachments/assets/c521970d-6a1d-424c-bd99-d5197a8e49a7)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State

![300541696-6c275261-a6d5-4c37-a3a7-1e88ca11c4cd](https://github.com/user-attachments/assets/fac81cc3-c133-4fbe-91ee-f0bde3caf7f8)



By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
![300541801-5174f41b-0ce0-4329-a372-6d1943ea6673](https://github.com/user-attachments/assets/0f6a5dee-3f77-45d3-a057-fe0885cdabeb)


The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q
t)Q(t+1)=JQ(t)′+K′Q(t)


**PROCEDURE**

1. Type the program in Quartus software.

2.Compile and run the program.

3. Generate the RTL schematic and save the logic diagram.

4. Create nodes for inputs and outputs to generate the timing diagram.

5. For different input combinations generate the timing diagram.


**PROGRAM**

![434133173-fa644c4f-11e2-40a4-b95a-83d9cfd728c1](https://github.com/user-attachments/assets/8e63d295-124a-449e-88db-64100d6c8501)

**TRUTH TABLE**

![434133879-fdab606d-854f-4092-b725-bcc6abbcf50d](https://github.com/user-attachments/assets/69aa8c37-1997-4659-885a-d8e3ca621e2b)




**RTL**

![434133995-da4b4f1f-e7ec-4553-8d4b-9fdc8eedd459](https://github.com/user-attachments/assets/d798803e-f222-4fe9-9c7c-c29ced9a04be)


**WAVEFORM**

![434134157-a59ef99b-66cb-4d01-8a3d-d837afbd13cf](https://github.com/user-attachments/assets/c8960479-6b33-4a9f-a59e-02cbf7c0a8d3)




**RESULTS**

Thus the given JK flipflops are implemented using and their operations are verified using Verilog programming.

