# BMI-project


name=input("Enter your name:")
height=float(input("Enter height:"))
weight=float(input("Enter weight:"))

bmi=weight / (height ** 2)

if bmi<18.5:
    Category = "Underweight"
    Advice = "Consider nutritious diet and consult a healthcare  provider."
elif bmi<25:
    category = "Normal weight"
    Advice = "Maintain a healthy lifestyle"
elif bmi<30:
    Category = "Overweight"
    Advice = "Do exercise"
else:
    Category = "Obese"
    Advice = "Health risks are higher"

print(f"\n{name},your bmi is:{bmi:.2f}")
print(f"category:{Category}")
print(f"health tip:{Advice}")
