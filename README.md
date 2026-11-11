## EXPERIMENT NO. 3 – STAIRCASE WIRING

| **Name:** | | **Reg. No.:** | |
|---|---|---|---|
| **Date:** | | **Batch / Section:** | |

---

## AIM

To control the status of the given lamp by using two-way switches.

## APPARATUS REQUIRED

| S. No. | Name of the apparatus | Range / Type | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Incandescent lamp | 60 W | 1 No. |
| 2 | Lamp holder | Pendant type | 1 No. |
| 3 | SPDT switch | 230 V, 5 A | 2 Nos. |
| 4 | Wires | 1/18" | As required |
| 5 | PVC pipe | 1/4" | As required |
| 6 | Wooden board | — | 1 No. |
| 7 | Round block | — | 1 No. |
| 8 | Simulation software | Proteus Design Suite | 1 |

## THEORY

- A two-way switch is installed near the first step of the stairs. The other two-way switch is installed at the upper part where the stairs end.
- The light point is provided between the first and last stair at an adequate location and height. If the light is switched on by the lower switch, it can be switched off by the switch at the top, or vice versa.
- The circuit can also be used in places like a bedroom, where the person need not walk back to the place from where the light was switched on in order to switch it off.
- Two numbers of two-way switches are used for this purpose. The supply is given to the switch at the short-circuited (common) terminal.
- The connection to the light point is taken from the similar short-circuited (common) terminal of the second switch. The other two independent terminals of each switch are connected through cables.

## PROCEDURE

1. Place the accessories on the wiring board as per the circuit diagram.
2. Place the PVC pipe and insert two wires into the PVC pipe.
3. Take one wire; connect one end to the phase side and the other end to the middle (common) point of SPDT switch 1.
4. The upper point of SPDT switch 1 is connected to the lower point of SPDT switch 2.
5. The lower point of SPDT switch 1 is connected to the upper point of SPDT switch 2.
6. Another wire is taken through the PVC pipe, and the middle (common) point of SPDT switch 2 is connected to one end of the lamp holder.
7. The other end of the lamp holder is connected to the neutral line.
8. Screw the accessories on the board and switch on the supply.
9. Test the circuit for all possible combinations of switch positions.

## A. DIRECT CONNECTION

### Circuit diagram

<img width="1080" height="608" alt="893330450_2202918357308193_6270441507613490445_n" src="https://github.com/user-attachments/assets/c89d3eb2-0329-461e-8bad-7fe86f5e6430" />
<img width="1080" height="608" alt="888557527_1646483450303866_4308767926023914006_n" src="https://github.com/user-attachments/assets/64fec39d-76bf-4589-ae34-730056816f4b" />


**Figure 1:** Staircase wiring – direct connection

### Tabulation 1: Truth table – direct connection

<img width="900" height="1600" alt="895307697_1680560103779181_9212860726611463137_n" src="https://github.com/user-attachments/assets/ecc5464c-162f-4624-86d4-67e7378f915f" />


| S. No. | Switch S1 position | Switch S2 position | Lamp status (ON / OFF) |
|:---:|:---:|:---:|:---:|
| 1 | | | |
| 2 | | | |
| 3 | | | |
| 4 | | | |

## B. CROSS CONNECTION

### Circuit diagram

<img width="1080" height="608" alt="896895948_1685679316254032_5430925499099813514_n" src="https://github.com/user-attachments/assets/5511ac6c-98c8-4e75-92ad-c34d20ccc0be" />
<img width="1080" height="608" alt="892843601_1453982986875287_5216622920185823523_n" src="https://github.com/user-attachments/assets/1223793c-df31-4440-8ba8-13f7d98ee699" />



**Figure 2:** Staircase wiring – cross connection

### Tabulation 2: Truth table – cross connection

<img width="900" height="1600" alt="898162954_2455781388158776_6528968482179882799_n" src="https://github.com/user-attachments/assets/3f42d4eb-5ef3-4522-b6dc-e899c7ce3a8b" />


| S. No. | Switch S1 position | Switch S2 position | Lamp status (ON / OFF) |
|:---:|:---:|:---:|:---:|
| 1 | | | |
| 2 | | | |
| 3 | | | |
| 4 | | | |

## SIMULATION USING PROTEUS

Build both the direct and cross connection circuits in Proteus using an AC source, two SPDT switches and a lamp. Run the simulation for each switch combination and paste screenshots showing the lamp ON and OFF states.

### A. Direct connection – simulation

<img width="1080" height="608" alt="893330450_2202918357308193_6270441507613490445_n" src="https://github.com/user-attachments/assets/c89d3eb2-0329-461e-8bad-7fe86f5e6430" />
<img width="1080" height="608" alt="888557527_1646483450303866_4308767926023914006_n" src="https://github.com/user-attachments/assets/64fec39d-76bf-4589-ae34-730056816f4b" />

**Figure 3:** Proteus simulation – direct connection

### B. Cross connection – simulation

<img width="1080" height="608" alt="896895948_1685679316254032_5430925499099813514_n" src="https://github.com/user-attachments/assets/5511ac6c-98c8-4e75-92ad-c34d20ccc0be" />
<img width="1080" height="608" alt="892843601_1453982986875287_5216622920185823523_n" src="https://github.com/user-attachments/assets/1223793c-df31-4440-8ba8-13f7d98ee699" />

**Figure 4:** Proteus simulation – cross connection

## RESULT

Thus, the staircase wiring was connected and tested for both direct and cross connections, and the lamp was controlled from two different places using two-way switches.
