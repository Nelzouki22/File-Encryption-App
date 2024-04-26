# File Encryption App
If you’re interested in the field of data security systems, this project is a great primer in C++, as it’s fascinating to see how you can protect file systems with basic encryption techniques.

As a beginner’s project, we’ll stick to a simple Caesar cipher using a character shift. I like this approach, as it’s easy to understand and implement for newcomers to C++.

We’re also extending our skills in file I/O, making it a nice step up from our previous To-Do List app.

Just think, if you’ve made it this far, you're not just coding – you're safeguarding data and delving into the principles that underpin secure communication in our digital world.
Code Explanation:

I really love this C++ project because it’s a great way to get some simple exposure to the powerful and potentially very complicated subject of encryption.

That said, let’s break down the main parts of our C++ program:

The program uses file streams to read from an input file and write to an output file, similar to our previous projects.
The encryptFile and decryptFile functions perform simple encryption and decryption by shifting characters by a given key. The key is an integer value determining how many places each character is shifted.
In the encryption function, each character from the input file is shifted forward by the key value, while in the decryption function, the characters are shifted backward.
The main function asks the user to choose between encrypting and decrypting a file. They’re then prompted to specify the key for the cipher and to provide the file paths.
When you run this program, you’re greeted with a really simple user interface that asks you to choose between encryption or decryption.

It’s then a matter of choosing the encryption key value and providing file names for the input and output.

Here’s a question: have you tried using the wrong encryption key? What happens?

Also, here’s a challenge for you! How might you add more complexity to your encryption technique? If you’re not sure where to start, I’ll provide some ideas.

Why not try a substitution cipher? Or perhaps a randomly generated key? Perhaps you can look at some form of login with a username and a password?
