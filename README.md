# NOIRLab colors
---
NOIRLab official color palette. Source: https://noirlab.edu/public/media/archives/techdocs/pdf/techdoc001.pdf

(R,G,B) | HEX | Name | Link
--------|-----|------|-----
``(097,102,114)``|``#616672``|Very dark grayish blue|https://www.colorhexa.com/616672
``(000,118,182)``|``#0076B6``|Strong blue|https://www.colorhexa.com/0076B6
``(190,091,146)``|``#BE5B92``|Moderate pink|https://www.colorhexa.com/BE5B92
``(255,183,027)``|``#FFB71B``|Gemini gold|https://www.colorhexa.com/FFB71B
``(241,093,093)``|``#F15D5D``|Soft red|https://www.colorhexa.com/F15D5D
``(005,138,139)``|``#058B8C``|Dark cyan|https://www.colorhexa.com/058B8C

---
## Copy/paste options for different plotting programs

### [gnuplot](http://gnuplot.info/) line style definition

    set style line 1 pt 7 ps 1.00 lt -1 lw 1.00 lc rgb "#00616672"
    set style line 2 pt 7 ps 1.00 lt -1 lw 1.00 lc rgb "#000076B6"
    set style line 3 pt 7 ps 1.00 lt -1 lw 1.00 lc rgb "#00BE5B92"
    set style line 4 pt 7 ps 1.00 lt -1 lw 1.00 lc rgb "#00FFB71B"
    set style line 5 pt 7 ps 1.00 lt -1 lw 1.00 lc rgb "#00F15D5D"
    set style line 6 pt 7 ps 1.00 lt -1 lw 1.00 lc rgb "#00058B8C"

### python (in progress...)

> contributions are welcome!

    nl01 = Color('#616672') # Very dark grayish blue
    nl02 = Color('#0076B6') # Strong blue
    nl03 = Color('#BE5B92') # Moderate pink
    nl04 = Color('#FFB71B') # Gemini gold
    nl05 = Color('#F15D5D') # Soft red
    nl06 = Color('#058B8C') # Dark cyan

---
## Example of lines and points (also with 50% transparency)

![example](https://raw.githubusercontent.com/vmplacco/noirlab_colors/main/noirlab_colors.png)
