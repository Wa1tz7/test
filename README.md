# test
# this is just a test
#bmi caculator
weight=float(input("enter your weight (kg):"))
height=float(input("enter your height (m):"))

if height <=0 or weight <= 0:
    print("weight and height must be greater than 0")
else:    
    result= weight / height ** 2
    print(round(result, 2))
if 0 < result <= 12:
    print("critical underweight")
elif result < 18.5:
    print("underweight")
elif 18.5 <= result <= 24.9:
    print("normal")
elif 25 <= result <=29.9:
    print("overweight")
elif 30 <= result <40:
    print("obese")
elif result >= 40:
    print("severely obese")
else:
    print("invalid input")
