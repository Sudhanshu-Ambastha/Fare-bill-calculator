# Python Program to Calculate Fare for a Given Distance

# Accept the distance covered in kilometers
distance = int(input("Enter the distance (in kilometers): "))

# Initialize the fare variable
fare = 0

# Calculate the fare according to the criteria
if distance >= 1 and distance <= 10:
    fare = distance * 11
elif distance > 10 and distance <= 19:
    fare = 10 * 11 + (distance - 10) * 10
elif distance >= 20:
    fare = 10 * 11 + 9 * 10 + (distance - 19) * 9
else:
    print("Invalid distance")

# Display the total fare if it's not zero
if fare > 0:
    print("The total fare for", distance, "km is Rs.", fare)
