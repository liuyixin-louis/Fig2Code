# Matplotlib with chatgpt
I am trying to use the chatgpt model from openAI for generating python plotting code based on textual or visual inputs. 

## Example#1

- Input

```
Using the python library, such as numpy and matplotlib, to implement the code that plots the following figure. The figure description is as follows:
1.  The x-axis title is "# of Tokens"
2. The y-axis title is "token-F1"
3. The range of the y-axis is from 0.00 to 0.25 and the main scale of the y-axis is 0.05.
4. The range of the y-axis is from 10 to 80 and the main scale of the y-axis is 10.
5. There are seven lines in the figure. And the colors of the lines are red, yellow, green, blue, purple, and pink respectively. The trend of these lines is gradually upwards. and they do not cross each other.
6. The figure needs to have legends and the labels for these lines are Ours, partial LRP, raw attention, GradCAM, LRP, rollout. The legend should be at the left upper position. 

The lowest line data is given as follows; please generate fake data in the code that ensure that other lines are above the given line. And ensure that all the lines are in the range of the y-axis. 

// X-Y data of the lowest line
11, 0.011
14, 0.015
17, 0.019
21, 0.024
24, 0.029
27, 0.033
30, 0.038
33, 0.043
36, 0.049
39, 0.054
42, 0.059
45, 0.063
48, 0.067
51, 0.072
54, 0.075
57, 0.079
61, 0.083
64, 0.088
67, 0.092
70, 0.096
73, 0.10
76, 0.10
79, 0.11
```

- output graph

![image-20221230171538736](https://s2.loli.net/2022/12/31/ha1CWgdU59Lu4le.png)
