# password generator
import random
upper = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ'
lower = 'abcdefghijklmnopqrstuvwxyz'
number = '0123456789'
symbol = '!@#$^_()[]{}/'
all = lower_case + upper_case + symbol + number
length = int(input('enter a number : '))
password= "".join(random.sample(all,length))
print('The Generated Password is',password)
