import math

def solve_right_triangle(opposite, adjacent, use_degrees = False):
    hypotenuse = ((opposite ** 2) + (adjacent ** 2)) ** (1/2)
    angle = math.atan(opposite/adjacent)
    if use_degrees == True:
        angle = math.degrees(angle)
    return (hypotenuse, angle)


print("Hypotenuse and angle: ", solve_right_triangle(3.0, 4.0))
print("Hypotenuse and angle: ", solve_right_triangle(3.0, 4.0, use_degrees = True))


