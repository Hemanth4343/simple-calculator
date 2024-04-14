# simple-calculator
while True:
  print("Select Operation \n 1. Addition \n 2. Substraction \n 3. Multiplication \n 4. Division \n 5. Exponentiation")
  choice = int(input("Enter Your Choice:"))
  num1 = float(input("Enter The Number:"))
  num2 = float(input("Enter The Number:"))
  if choice == 1:
    print("Result :", num1 + num2)
  elif choice == 2:
    print("Result :", num1 - num2)
  elif choice == 3:
    print("Result :", num1 * num2)
  elif choice == 4 and num2 != 0:
    print("Result :", num1 / num2)
  elif choice == 5:
    print("Result:", num1**num2)
  elif choice == 6:
    print("Exiting the calculator.")
    break
  else:
    print("Invalid Input")
