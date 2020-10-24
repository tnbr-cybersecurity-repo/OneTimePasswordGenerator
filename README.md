# Cybersecurity Foundations

## Project 1 - Python Scripting
This was a learning challenge
1) Learn Python within 2 weeks
2) Develop the 2 programs

### Program 1: Pasword Guessing Tool
Write a Python script that prompts the user to enter a guessed password value and responds back by confirming if the provided password matches the one in the system or not.  

Use **crypt.crypt(word, salt)** to perform this validation.

### Program 2: One-Time Password Generator
Impellent a One-Time Password generator using the following algorithm.  

Hash Feedback One-Time Password Algorithm described in the following chart.   

Secret key is used as the initialization vector. The first OTP is generated by hashing this vector.  

The second OTP is generated by hashing the hash generated by the first the 1st OTP, and so on.  

The OTP is calculated by truncating the hash into a six digit hexadecimal value.  

The most significant hex digits will be extracted as the OTP.

Use the following hexadecimal value for the **Key: 810770FF00FF07012**.  

Use **hashlib.sha256(input_message).hexdigest()** to calculate the hash digest.  

Write a Python script that will generate a display on the screen the first 100 OTPs generated by the above algorithm.
<hr>
With God's guidance and determination to succeed, I completed the challenge on time.
