This is an EXTREMELY basic password hashing program that I've written. Allows you to enter any string into the command line where it is then hashed and salted, added to a list, and finally added to a text document called "Hashed Passwords" by default. 

Entries are hashed via SHA256 and are NOT recommended for practical, real-world use for password hashing. There are much more secure ways to store passwords, but of course, the most secure way to store passwords is to... well, NOT store them :)

I am posting this mainly for educational purposes. Hypothetically, you could use this for personal use, however, you must keep in mind that you cannot "un-hash" the results and get the original plain text entry. And again, it's not going to protect you in a breach (more than likely).
