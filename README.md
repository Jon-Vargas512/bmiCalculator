# Ask the user for their height and weight using the input function.

height = input("enter your height in ft: ")

weight = input("enter your weight in lbs: ")


# BMI = Weight/Height Squared
# Convert variables into the correct Data Type so they can be computed.
# Convert BMI into an integer.

bmi = int(weight) / float(height) ** 2
bmi_as_int = int(bmi)
print(bmi_as_int)
