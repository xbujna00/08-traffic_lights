# Lab 08-traffic_lights 

### Preparation tasks
### Completed state table


| **Input P** | `0` | `0` | `1` | `1` | `0` | `1` | `0` | `1` | `1` | `1` | `1` | `0` | `0` | `1` | `1` | `1` |
| :-- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| **Clock** | ![rising](sipka.png) | ![rising](sipka.png) | ![rising](sipka.png) | ![rising](sipka.png) | ![rising](sipka.png) | ![rising](sipka.png) | ![rising](sipka.png) | ![rising](sipka.png) | ![rising](sipka.png) | ![rising](sipka.png) | ![rising](sipka.png) | ![rising](sipka.png) | ![rising](sipka.png) | ![rising](sipka.png) | ![rising](sipka.png) | ![rising](sipka.png) |
| **State** | A | A | B | C | C | D | A | B | C | D | B | B | B | C | D | B |
| **Output R** | `0` | `0` | `0` | `0` | `0` | `1` | `0` | `0` | `0` | `1` | `0` | `0` | `0` | `0` | `1` | `0` |

### Figure with connection of RGB LEDs on Nexys A7 Board
![LEDS](rgb.png)
