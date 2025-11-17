# EXP-1
EXPT NO: 1	VERIFICATION OF KIRCHHOFF’S LAWS
AIM
a.   To verify Kirchhoff’s Voltage Law (KVL) for the given circuit. 
b.   To verify Kirchhoff’s Current Law (KCL) for the given circuits.

APPARATUS REQUIRED:
S.No.	Components	Range	Quantity
1	Resistor	1kΩ	3
2	Voltmeter (DC)	0-30V	3
3	Ammeter (DC)	(0-200)mA	3
4	Bread Board		1
5	Regulated Power Supply	(0-30)V	1
6	Connecting wires		As required

THEORY:
KVL: Kirchhoff's voltage law states that the sum of the voltage differences around any closed loop in a circuit must be zero. A loop in a circuit is any path that ends at the same point at which it starts.
KCL:
Kirchhoff's Current Law (KCL) Kirchhoff's Current Law states that the algebraic sum of the currents entering and leaving a node is equal to zero. By convention, currents entering the node are positive, and those leaving a node are negative


PROCEDURE:
a.   KVL:
1.   Connect as per the circuit diagram.
2.   Check if the RPS voltage is set to zero voltage.
3.   Check all the meters for null position.
4.   Switch on the RPS.
5.   Set the input voltage to a value between 0V to 30V.
6.   Record the voltage values shown in the voltmeter connected across each resistor.
7.   Take readings for different values of input voltage and tabulate them.


b.  KCL:
1.   Connect as per the circuit diagram.
2.   Check if the RPS voltage is set to zero voltage.
3.   Check all the meters for null position.
4.   Switch on the RPS.
5.   Set the input voltage to a value between 0V to 30V.
6.   Record the voltage values shown in the ammeter connected to each resistor.
7.   Take readings for different values of input voltage and tabulate them. 
CIRCUIT DIAGRAM:


CIRCUIT DIAGRAM:

a.   KVL:

<img width="1570" height="840" alt="Screenshot 2025-11-12 092646" src="https://github.com/user-attachments/assets/19e9d996-8bc0-4a0d-8980-360331b06352" />
b.  KCL:
 
<img width="1570" height="840" alt="Screenshot 2025-11-12 092646" src="https://github.com/user-attachments/assets/ac16dafd-cf20-4970-acad-c78df408e70e" />


Calculation:

a.   KVL:
 
$$ V=V_{1}+V_{2}+V_{3} $$

$$ 100=IR_{1}+IR_{2}+IR_{3} $$

$$ R_{eq}=R_{1}+R_{2}+R_{3} $$

$$ R_{eq}=180\Omega $$

$$ I=V/R_{eq}=100/180=0.556V $$

$$ V_{1}=V_{30\Omega}=IR_{1}=0.556 \ast 30=166.68V $$

$$ V_{2}=V_{50\Omega}=IR_{2}= O.556\ast 50=27.8V $$

$$ V_{3}=V_{100\Omega}=IR_{3}= O.556\ast 100=55.6V $$

b.  KCL:
$$ i_{30\Omega}=I_{50\Omega}+I_{100\Omega} $$

$$ i_{30\Omega}=\frac{100-V}{30} $$

$$ I_{50\Omega}=\frac{V}{50} $$
$$I_{100\Omega}=\frac{V}{50} $$
$$ frac{100-V}{30}=\frac{V}{50} +\frac{V}{100} $$
$$ \frac{100-V}{30}=\frac{2V}{100} +\frac{V}{100} $$
$$ \frac{100-V}{30}=\frac{2V +V}{100} $$
$$ \frac{100-V}{3}=\frac{3V}{10} $$
$$ \frac{100-V}{3}=\frac{3V}{10} $$




Tabulation:

a.   KVL:
 
|KVL|Source(V)|$$V_{30\Omega}$$|$$V_{50\Omega}$$|$$V_{100\Omega}$$|$$V_{30\Omega}+V_{50\Omega}+V_{100\Omega}$$|
 |:-----:|:-----:|:------------:|:--------------:|:---------------:|:-----------------------------------------:|
 |Theoretical|100|16.68V|27.8V|55.6V|100.05V|
 |partical|100|16.7V|27.8V|55.6V|100.1V|

b.  KCL:

|KCL|$$I_{30\Omega}$$|$$I_{50\Omega}$$|$$I_{100\Omega}$$|$$V_{A}$$|
 |:-----:|:------------:|:--------------:|:---------------:|:-----------------------------------------:|
 |Theoretical|1.58A|1.05A|0.53A|52.63V|
 |partical|1.58A|1.05A|0.53A|52.6V|

RESULT:

Thus, for the given circuit, Kirchhoff’s Laws, (a) KVL and (b) KCL are proved.
