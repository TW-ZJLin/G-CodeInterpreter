# G-CodeInterpreter
G-Code Interpreter and 3D visualization for CNC code.
## Introduction
This program can reads NC files(.txt, .nc, etc.) and converts them into arrays.<br>
And implement 3D visualization with plotly.<br>

## input output format
Input: NC files with G-code(.txt, .nc, etc.) as shown below.<br>
![]("https://github.com/TW-ZJLin/G-CodeInterpreter/blob/main/Figures/NCfile.jpg")<br>

Output: Numpy array with X, Y, Z, R, F for each columns as shown below.<br>
![]("https://github.com/TW-ZJLin/G-CodeInterpreter/blob/main/Figures/DataArray.jpg")<br>

## Case 1 <br>
![](https://github.com/TW-ZJLin/G-CodeInterpreter/blob/main/Figures/Case1.png)<br>

## Case 2 <br>
![](https://github.com/TW-ZJLin/G-CodeInterpreter/blob/main/Figures/Case2-1.png)<br>
![](https://github.com/TW-ZJLin/G-CodeInterpreter/blob/main/Figures/Case2-2.png)<br>

## Case 3 <br>
![](https://github.com/TW-ZJLin/G-CodeInterpreter/blob/main/Figures/Case3.png)<br>
