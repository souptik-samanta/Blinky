# Blinky Board

Made by Souptik!

I built this little project because I wanted a heart-shaped PCB that I could gift to someone. It's a simple LED chaser built around a 555 timer and a CD4017 decade counter. The LEDs light up one after another, creating a blinking animation around the heart.

Built using parts I already had on hand, and manufactured through JLC thanks stasis.
BUILD PHOTO
![image](https://stasis.hackclub-assets.com/images/1782295844268-m1t962.png)

and here is the bottom

![image](https://stasis.hackclub-assets.com/images/1782295856992-xktjgw.png)

worknig video 

https://youtube.com/shorts/QsSJmAaTk8Q?feature=share
## Photos

<img width="916" height="776" alt="Blinky Board PCB" src="https://github.com/user-attachments/assets/4fc4a516-117c-45df-8549-69bfe71bc61a" />

<img width="1115" height="885" alt="Blinky Board Schematic" src="https://github.com/user-attachments/assets/7c2f5adc-adb5-4f5b-891e-e6748ce709cc" />

<img width="1107" height="948" alt="Blinky Board PCB Layout" src="https://github.com/user-attachments/assets/e3d33c0f-9e49-4353-b67b-9877fb41bd05" />

<img width="696" height="568" alt="Blinky Board Render" src="https://github.com/user-attachments/assets/de7e12b2-0921-432a-934a-c57213c57599" />

## How It Works

A 555 timer is configured as an oscillator that generates clock pulses. These pulses are fed into a CD4017 decade counter, which turns on one output at a time. Each output drives an LED on the heart, creating a rotating blinking effect. The potentiometer can be adjusted to change the animation speed.

## Bill of Materials (BoM)

| Part | Purpose | Quantity |
|--------|---------|----------|
| PCB | Heart-shaped board that holds all the components | 1 |
| LED | Creates the chasing light effect around the heart | 10 |
| 1kΩ Resistor | Helps set the oscillator timing | 1 |
| 470Ω Resistor | Limits LED current | 1 |
| Potentiometer (RV) | Adjusts the animation speed | 1 |
| 1µF Capacitor | Works with the 555 timer to generate clock pulses | 1 |
| 1x01 Header | Test/debug connection point | 1 |
| 1x02 Header | Power input connector | 1 |
| CD4017 | Sequences the LEDs one after another | 1 |
| NE555P | Generates the clock signal | 1 |

## Cost

All components were sourced from my existing parts inventory, so the project itself cost me nothing to assemble.

| Item | Cost (USD) |
|--------|------------|
| Components | $0.00 |
| PCB | JLC sponser |
| **Total Out-of-Pocket Cost** | **$0.00** |

## Why I Made It

I wanted to make something small, simple, and fun that could be gifted to someone. Instead of a regular rectangular PCB, I designed it in the shape of a heart and added a classic 555 + 4017 LED chaser circuit to make it feel a bit more special.
