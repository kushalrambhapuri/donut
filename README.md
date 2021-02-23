# donut
This is a virtual donut which moves naturally in a screen.
I have done it by using Pycharm which is an python code editor.
For the code I have used a pip (python installation package) which is **pip install vpython**
In the code I have imported the package vpython but before that in the terminal I have installed the vpython package
And then I have told to change the background color of the screen to purple
Then for the layer of the donut I have made a variable called donut in that variable I have put the shape of it as ring and the radius of it is 0.5, thickness is 0.25, and color=vector(400, 100, 1)
And then created another variable named chocolate and in that I have put it in a shape of ring which will be outer of the donutthe radius is 0.55, thickness is 0.25, and color is vector (0.4, 0.2, 0)
There is another variable called rad which I have put the value to 0
Then I have created a if condition which is while true:
and under this if condition I have put the rate(10) and the donut position = vector(3*cos(rad), sin(rad), 0) and the chocolate position = vector(3*cos(rad), sin(rad), 0) and then I have made rad = rad + 0.03
And when we run the program we will go to another tab in Google Chrome or which you use and the donut starts to move naturally in the provided screen.
