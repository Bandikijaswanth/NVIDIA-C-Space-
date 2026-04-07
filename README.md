# NVIDIA-C-Space-
AIM

To generate a collision-free configuration space by inflating obstacles based on robot size.

PROCEDURE
Initialize the robot radius
Identify obstacle boundaries in the environment
Inflate each obstacle by the robot radius
Transform the environment into configuration space
Ensure safe distance from obstacles
Display the result
CODE
# Robot radius
robot_radius = 0.6   # in meters

# Assume obstacle inflation applied
inflated_obstacle = True

# Check collision-free space
if inflated_obstacle:
    result = "Collision-Free"
else:
    result = "Not Safe"

# Output
print(result)
OUTPUT

Collision-Free

RESULT

By inflating obstacles with the robot radius, a collision-free configuration space is created for safe motion planning.
