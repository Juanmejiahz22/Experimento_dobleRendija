import numpy as np
#Definimos la matriz inicial con sus probabilidades
m = np.array([[0  ,0  ,0  ,0  ,0  ,0  ,0  ,0], 
               [1/2,0  ,0  ,0  ,0  ,0  ,0  ,0], 
               [1/2,0  ,0  ,0  ,0  ,0  ,0  ,0],
               [0  ,1/3,0  ,1  ,0  ,0  ,0  ,0], 
               [0  ,1/3,1  ,0  ,1  ,0  ,0  ,0], 
               [1  ,1/3,1/3,0  ,0  ,1  ,0  ,0],
               [0  ,0  ,1/3,0  ,0  ,0  ,1  ,0],
               [0  ,0  ,1/3,0  ,0  ,0  ,0  ,1]])
v1 = np.array([[1], [0], [0], [0], [0], [0], [0], [0]])
v2 = np.array([[0], [1/2], [1/2], [0], [0], [1], [0], [0]])
v3 = np.array([[0], [0], [0], [1/6], [1/6], [1/3], [1/6], [1/6]])

#Estado después de un click
state_after_one_click = np.dot(m, v1)

#Estado después de dos click
state_after_two_clicks = np.dot(m, v2)

#Estado después de tres click
state_after_three_clicks = np.dot(m, v3)


print("Result after one Click: \n", state_after_one_click)
print("Result after two Clicks: \n", state_after_two_clicks)
print("Result after three Clicks: \n", state_after_three_clicks)
