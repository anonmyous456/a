
import string
import random

def NumberGenerator (s) :

	data = s[3:8]
	result = []

	while len(result) != 5000 :

		b = s.replace(data , str(random.randint(0 , int(string.digits))))
		
		if len(b) == 10 :

			if not b in result :

				result.append(b)

		else :

			pass

	with open("NumberGenerator.txt" , mode = "a") as file :

		for i in result :

			file.write(i)
			file.write("\n")

print(NumberGenerator("964XXXXX60"))
