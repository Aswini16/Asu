# Python code for gcd of two numbers


def hcf(a, b):
	if(b == 0):
		return a
	else:
		return hcf(b, a % b)

a = 60
b = 48

print("The gcd of 60 and 48 is : ", end="")
print(hcf(60, 48))
