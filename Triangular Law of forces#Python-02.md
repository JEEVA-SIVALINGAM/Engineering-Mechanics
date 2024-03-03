If Two Forces 20 kN and 15 kN act on a point. The angle between the forces is 600.Find the magnitude and the direction of the resultant.
import math
# Given values
F1 = 20  # N
F2 = 15  # N
theta = 110  # degrees
# Calculate R using the triangle law formula
R_squared = F1**2 + F2**2 - 2 * F1 * F2 * math.cos(math.radians(theta))
R = math.sqrt(R_squared)
# Apply sine rule formula
alpha = math.degrees(math.asin((F2 * math.sin(math.radians(theta))) / R))
# Display results
print(f'R value: {R:.4f}')
print(f'Alpha value: {alpha:.4f} degrees')
