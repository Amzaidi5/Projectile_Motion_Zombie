# Projectile_Motion_Zombie


# Creating value for gravitational field strength
g = 9.81

# Generate a random angle
import random
theta = random.random()*45

# Converting angle to radians
import math
theta_rads = theta*(math.pi/180)

# Asking for distance to zombie
d1 = input("Please enter the distance to our target zombie: ")
d = float(d1)

# Equation fot projectile
v = ((g*d)/(math.sin(2*theta_rads)))**(1/2)

# Output and statement
print("""
Ready for launch!
Set angle to""", theta, """degrees
Set velocity to """, v, """m/s""")
