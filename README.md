# LonCapaHW-1
steps = [1,2,3,4,5] 
t = 0 
dt = 0.1 
x = 0
velocity = 2
for step in steps:
  x = x + velocity*dt
  t = t + dt
print("x = ", x)
print("Time = ", t)
