# Traffic-Detection-using-openCV

## Summary 

Using a raspberry pi with a camera to detect the number of vehicles passing through a particular section of the road in a period of time. 

## Working

We can use a Raspberry PI which has a camera attached to it, as a Edge based device to predict the traffic on the road on a particular time of the day using various computer vision algorithms that are implemented in the OpenCV library. 
The algorithm works by defining a region inside the captured frame, and then constantly monitoring that region in order to find out when a particular car has passed that region. 

This can help data anaylysts build models for predicting the estimated traffic in various parts of a city, at any time of a day, and using those predictions to accurately predict how long would it take for a cab to arrive, instead of linearly scaling the time based on the distance. 

## Getting Started

```python 
python Car_Detection_Algorithm.py
```
