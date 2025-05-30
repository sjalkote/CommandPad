# CommandPad

This is supposed to be a keyboard macro pad that lets you set keys to custom keybinds, using mx switches, a rotary knob, and LEDs.

My attempt at a start-to-finish hardware project from scratch, including creating PCB designs, 3d print designs, and coding firmware.

### Bill of Parts

| Reference            | Qty | Value                | DNP | Exclude from BOM | Exclude from Board | Footprint                                                     | Datasheet                                                                  |
| -------------------- | --- | -------------------- | --- | ---------------- | ------------------ | ------------------------------------------------------------- | -------------------------------------------------------------------------- |
| D1,D2,D3,D4,D5,D6,D7 | 7   | Diode                |     |                  |                    | ScottoKeebs_Components:Diode_DO-35                            |                                                                            |
| DLED1,DLED2          | 2   | SK6812MINI           |     |                  |                    | LED_SMD:LED_SK6812MINI_PLCC4_3.5x3.5mm_P1.75mm                | https://cdn-shop.adafruit.com/product-files/2686/SK6812MINI_REV.01-1-2.pdf |
| J1                   | 1   | OLED_128x32          |     |                  |                    | 0.91 OLED Display:SSD1306-0.91-OLED-4pin-128x32               |                                                                            |
| S1,S2,S3,S4,S5,S6    | 6   | Keyswitch            |     |                  |                    | Button_Switch_Keyboard:SW_Cherry_MX_1.00u_PCB                 | ~                                                                          |
| SW1                  | 1   | RotaryEncoder_Switch |     |                  |                    | Rotary_Encoder:RotaryEncoder_Alps_EC11E-Switch_Vertical_H20mm | ~                                                                          |
| U1                   | 1   | XIAO-RP2040-DIP      |     |                  |                    | Seeed Studio XIAO Series Library:XIAO-RP2040-DIP              |                                                                            |

## Results

![schematic](assets/schematic.png)

![pcb](assets/pcb.png)

![render](assets/3d_render.png)

![case](assets/fusion_case.png)
