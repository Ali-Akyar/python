import math
points = [(50, 40), (25, 30), (15, 10), (10, 7), (6, 4)]   # a sample list that contains coordinates of some points(x,y) in tuple format
distances = [] # an empty list 

def euclideanDistance():  #function definition
    for i in range(len(points)-1): # loop for calculating distance betw 1st and 2nd tuple, 2nd and 3rd tuple and goes like that 
        horizontalDiff = points[i][0]-points[i+1][0]  # x2-x1
        verticalDiff = points[i][1]-points[i+1][1]    # y2-y1
        distance = math.sqrt((horizontalDiff**2) + (verticalDiff**2))  # distance = ((x2-x1)^2+(y2-y1)^2)^0.5 
        print(horizontalDiff, verticalDiff) 
        print(distance)
        distances.append(distance)
        
euclideanDistance() #calling the function
print(distances) #printing all distances with a list
