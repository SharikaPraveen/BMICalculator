# BMICalculator
Bmi calculator using function and returns the value in Python
def bmi_calculator(bmi):
   return (bmi)
w = float(input("Enter your weight in kg"))
h = float(input("Enter your height in meter"))
bmi = ((w)/(h*2))
print("Your BMI is",bmi)
if bmi < 18:
  print("You are Underweight")
elif bmi >= 18  and  bmi < 25:
  print("You are Normal")
elif bmi >= 25 and bmi < 30:
  print("You are Overweight")
else:
  print("You are Obese")

