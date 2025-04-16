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

![image](https://github.com/user-attachments/assets/d158ce89-316b-4dbf-98d1-4b5e19fb3588)


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![WhatsApp Image 2025-04-16 at 08 52 20_75ad7af3](https://github.com/user-attachments/assets/0b59b1ea-dc1d-4dc2-9fa5-724769359b84)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 
![WhatsApp Image 2025-04-16 at 08 52 21_a0ae534c](https://github.com/user-attachments/assets/0b663a44-0866-438c-be4e-d894b121984f)


By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
(![WhatsApp Image 2025-04-16 at 08 52 21_d20d2686](https://github.com/user-attachments/assets/b2fddd0f-ed4c-4460-aa5d-323702fc172f)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q
t)Q(t+1)=JQ(t)′+K′Q(t)



**PROGRAM**
![image](https://github.com/user-attachments/assets/9d310244-d181-4f91-a029-2b285e58feee)

**TIMING DIGRAMS FOR FLIP FLOPS**
![image](https://github.com/user-attachments/assets/d592caa4-54de-458f-b805-4cab1ea15ecd)

**RESULTS**
To implement  JK flipflop using verilog and validating their functionality using their functional tables has been executed successfully.
