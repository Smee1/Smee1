[Project requirements

This project is to write and show my understanding of code in relation to password security for a Queen’s medical centre using ASMIS appointment system. This line of code makes sure that the passwords are strong to prevent brute-force hacking. By making the password a min of six characters, with a symbol as well as at least one upper and lower case letter, makes the password stronger. Therefore harder to hack into. By adding a multi-factor authentication method another level of security is added.

The reason for code

Passwords must be strong. An average medical history is worth around $200 per person. Medical histories are being targeted by hackers due to the lack of cyber security from outdated software used by medical centres. This information can be sold to third parties which can thus be used for several illegal activities such as blackmailing a patient. Patients can be victims of phishing attacks, especially the elderly, which these attacks are often focused on. Therefore, the code has multi-factor authentication to reduce phishing attacks. The lines of code are in python which the ASMIS system must be coded in for this to be compatible. There is a legal requirement to protect personal data with strong penalties and reputational damage for failure.

Installing the code

The script is currently short and concise. More code could be added to increase its security of it. Currently, the code shows proof of understanding of the set criteria. The code prompts the user to create a password with certain criteria. The bcrypt authentication is a password hashing algorithm that adds a level of security by always hashing a password with a salt. Adding a process that adds hashing and salting improves the process of making the hash unidentifiable. bCrypt was based on the blowfish cipher and can hash over 200,000 passwords per second. bCrypt can be made slower which can hinder attackers. bCrypt benefits include large salt space, adaptable cost, and speed change. bCrypt requires a salt. A salt is an additional input that hashes data for a password to ensure it is secure. Essentially it adds random parts to the password before it is hashed. The code could be improved to add extra security but this currently shows the basic requirements and understanding of a code for a patient to create a strong password with extra security with multi-authentication.

Why use python 3

The code used is python 3. Python 3 code was selected as it is the most updated version of python and is one of the easier codes for beginners to learn. A comparison between python 2 and 3 is the syntax used/ For example python 2 would use print “nice to meet you” whereas python 3 would use print(“nice to meet you”). This does mean that the two languages cannot communicate with one another which has slowed the uptake on the newer updated version python 3.

Another huge advantage of python is that it is Unicode, and thus can be coded in many languages such as Greek, Arabic or even symbols. From 2020 python 2 is no longer being supported because python 3 has well surpassed its predecessor in the libraries that it has on offer. 



References

Arias, D. (2021). Hashing in Action: Understanding bcrypt. Available: https://auth0.com/blog/hashing-in-action-understanding-bcrypt/. Last accessed 4th June 2022.

Mishra, L. (2021). 10 benefits of using Python 3 over 2. Available: hhttps://www.pylenin.com/blogs/10-benefits-of-switching-to-python-3/. Last accessed 4th June 2022.

No author. (2021). Generate password in python. Available: https://stackoverflow.com/questions/3854692/generate-password-in-python. Last accessed 4th June 2022.

pypi. (2022). bcrypt 3.2.2. Available: https://pypi.org/project/bcrypt/. Last accessed 4th June 2022.

Stamenic, D. (2022). Hashing Passwords in Python with BCrypt. Available: https://stackabuse.com/hashing-passwords-in-python-with-bcrypt/. Last accessed 4th June 2022.
](https://github.com/Smee1/final-ema-uplaod-1)
