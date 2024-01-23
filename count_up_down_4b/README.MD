<!-- Please do not change this html logo with link -->

<a href="https://www.microchip.com" rel="nofollow"><img src="images/microchip.png" alt="MCHP" width="300"/></a>

# 4-Bit Up/Down Counter

The module has Reset and Enable inputs. The direction of the counter can be changed by using the Down input.

| **reset** | **enable** |    **down**   |   **output**  |
|:---------:|:----------:|:-------------:|:-------------:|
|     0     |      0     |       0       |    Disabled   |
|     0     |      0     |       1       |    Disabled   |
|     0     |      1     |       0       |  Up Counting  |
|     0     |      1     |       1       | Down Counting |
|     1     |      x     |       x       |     Reset     |

The schematic is shown in the below image.
<br><img src="images/up_down_counter_4bit.png" width="600">

## Demo

The demo shows an example of using the counter. The direction is changed by using a CLB Software Input Register (CLBSWIN).
<br><img src="images/up_down_counter_4bit_demo.png" width="600">

 The waveforms obtained on each output pin are shown in the below image.
<br><img src="images/up_down_counter_4bit_waveforms.png" width="600">