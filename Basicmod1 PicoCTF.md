---
tags:
  - study
  - PicoCTF2022
  - Cryptography
url: 
share: "true"
---

# Question 
![[Pasted image 20240116170102.png|Pasted image 20240116170102.png]]

# Answer 
![[Pasted image 20240202182857.png|Pasted image 20240202182857.png]]
# Problems
1. the questions stated that, it wants the 0 - 25 results have to be the alphabet in uppercase, this requirements makes me question, from which alphabet i need to start with and when i should i stop. than the i realized that in the 18th line in the script, the code uses chr() function to convert it, and uses the ASCII table as the chr() function use ASCII table to convert the integer into a unicode and turns the unicode according to char in ASCII table. it's added with 65 because in the ASCII table the alphabet starts in the 65th table. 
2. the questions also asks to include the 26-35 results have to be a decimal digits, again, i was confused, and then i realized that decimal digits starts from 0 to 9, and then i just have to reduce, the t in the loop to make t starts counting from 0 as the number of decimal digits start from 9. 

# What i learned 
Decimal numbers start from 0 - N 
Real Numbers are everything except like pi etc 
ASCII table comes pretty useful to converts integer/number into a character or a symbol using decimal and hexadecimal 

Denary/Decimal is a base 10 Number System
which are 0,1,2,3,4,5,6,7,8,9,…
Binary is a base 2 number system 
which are 0 and 1 
Hexadecimal is a base 16 Number system 
which are 0,1,2,3,4,5,6,7,8,9,A,B,C,D,E,F
Octal is a base 8 Number system
which are 0,1,2,3,4,5,6,7