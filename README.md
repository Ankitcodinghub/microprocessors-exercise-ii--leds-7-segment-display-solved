# microprocessors-exercise-ii--leds-7-segment-display-solved
**TO GET THIS SOLUTION VISIT:** [Microprocessors Exercise II -LEDs & 7-Segment Display Solved](https://www.ankitcodinghub.com/product/microprocessors-exercise-problems-i-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;126121&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Microprocessors  Exercise II -LEDs \u0026amp; 7-Segment Display Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
LEDs &amp; 7-Segment Display

Design the hardware interface and write an 8086-assembly program for the following projects. The addresses of ports A, B and C of the 8255A PIA are 01 H, 05 H, 09 H and 0D H respectively odd addresses. Assume that the forward voltage of a LED (VD) is 3V, and the required LED current (ID) is 8 mA.

1. The assembly program controls 16 LEDs according to the status of two switches (SW1 and SW2) connected to PORT C (PC0 and PC1). The LEDs are connected to PORT A and PORT B. The program controls the LEDs as follows: o If only SW1 is pressed, the program flashes the 8 LEDs connected to PORT A (5 times).

o If only SW2 is pressed, the program flashes the 8 LEDs connected to PORT B (5 times).

o If both SW1 and SW2 are pressed, the program flashes all the 16 LEDs connected to PORT A and PORT B (5 times).

o If both SW1 and SW2 are released, the program turns all the 16 LEDs OFF.

2. The assembly program monitors the status of a switch connected to PC7, and displays the number of switch presses on a seven-segment connected to PORT A. If the number exceeds 9, the program displays the letter F on the sevensegment.

3. The program controls 8 LEDs connected to PORT A as follows:

o First, turn ON the LED connected to PA7 (alone).

o Second, turn ON the LED connected to PA6, while keeping the PA7-LED ON. o Repeat the previous steps, by turning ON the LED that follows them, and so on until all the LEDs are turned ON.

o Do the same as the previous steps, but in reverse so that the LEDs are turned off sequentially, and continue until we return to the status of the LEDs that described in the first step. o Repeat all the previous steps.

4. The assembly program monitors the status of a switch connected to PC4.

o If the switch is pressed, the program rotates 8 LEDs connected to PORTA in a clockwise manner.

o If the switch is released, the rotation will occur in the opposite direction.

5. The program monitors the status of a switch connected to PORTC, and controls a seven-segment display connected to PORT A as follows:

o If the switch is pressed, the program displays the EVEN numbers on the sevensegment (in ascending order from 0 to 8 and repeat). o If the switch is released, the program displays the ODD numbers on the sevensegment (in descending order from 9 to 1 and repeats).

6. The program displays numbers from 0 to 9 on a seven-segment display connected to PORT B, and repeats. Each number displayed on the sevensegment is blinked twice before the next number is displayed.

7. The program monitors the status of a switch connected to PORTC, and controls a seven-segment display connected to PORT A as follows:

o If the switch is pressed, the program rotates only one segment of the 7segment in a clockwise direction (and repeats).

o If the switch is released, the program rotates only one segment of the 7segment in an anticlockwise direction (and repeats).

8. The program monitors the status of 8 switches, and displays the status of these switches on 8 LEDs connected to PORT C. The switches are connected to PORT A (PA0 to PA3) and PORT B (PB0 to PB3). The program displays the status of the 8 switches at the same time on the LEDs that are connected to PORTC.

9. Design the hardware interface and write an 8086-assembly language program for the following project:

▪ Two 8255A interfacing chips (Chip 1 &amp; Chip 2) are connected to the 8086 microprocessor.

▪ The required port addresses are as follows:

Chip 1 addresses: PB1 02 H , PControl1 06 H

Chip 2 addresses: PB2 0A H , PControl2 0E H .

▪ The assembly program first flashes 8 LEDs connected to PB1 (10 times), then it displays even numbers (from 0 to 9) on a seven segment connected to PB2, then the program stops.

▪ Use two current limiting resistors and find their values, assuming that the LED forward voltage VD = 2.5 V, and the required LED current ID = 8 mA.

▪ Use one second delay intervals.

10. For the project described above, it is required to connect one of the 8255A interfacing chips to the high byte of the data bus [AD15 . . AD8]. Assume that the required port addresses are as follows:

Chip 1 addresses: PB1 02 H , PControl1 06 H

Chip 2 addresses: PB2 09 H , PControl2 0F H .

11. Design the hardware interface and write an 8086-assembly program for a common anode 7-segment display connected to PORT B. The program displays the letters A , E , F , H , L , and P (and repeat) if a switch connected to BIT0 of PORT A is pressed. If the switch is released, the program displays dash “ – ” on the 7-segment. Use two seconds delay intervals between each two characters.
