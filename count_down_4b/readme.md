<!-- Please do not change this html logo with link -->

<a href="https://www.microchip.com" rel="nofollow"><img src="images/microchip.png" alt="MCHP" width="300"/></a>

# 4-Bit Binary Down Counter

The module has Reset and Enable inputs. 

| **reset** | **enable** | **output** |
|:---------:|:----------:|:----------:|
|     0     |      0     |  Disabled  |
|     0     |      1     |   Enabled  |
|     1     |      0     |    Reset   |
|     1     |      1     |    Reset   |

The schematic is shown in the below image.
<br><img src="images/binary_down_counter_4bit.png" width="600">

## Demo

The demo shows an example of using the counter.
<br><img src="images/binary_down_counter_4bit_demo.png" width="600">

 The waveforms obtained on each output pin are shown in the below image.
<br><img src="images/binary_down_counter_4bit_waveforms.png" width="600">