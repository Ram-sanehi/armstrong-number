# armstrong-number
# Python program to check if the number is an Armstrong number or not

# take input from the user
<br>
num = int(input("Enter a number: "))
<br>
# initialize sum
<br>
sum = 0
<br>
# find the sum of the cube of each digit
<br>
temp = num
<br>
while temp > 0:
<br>
   digit = temp % 10
<br>   sum += digit ** 3
  <br> temp //= 10

<br># display the result
<br>if num == sum:
  <br> print(num,"is an Armstrong number")
<br>else:
   print(num,"is not an Armstrong number")
