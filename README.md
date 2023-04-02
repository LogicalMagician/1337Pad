Overview

1337Pad is a secure, client-side encrypted notepad application that ensures the privacy of your notes. It offers various features such as encryption, decryption, and the option to switch between day and night modes for ease of use.

Why is it safer than using a normal notepad?

1337Pad is safer than a normal notepad due to its encryption capabilities. When saving a note, the content is encrypted using the Advanced Encryption Standard (AES) with a random salt that uses random mouse movements to increase entropy and a password provided by the user. This ensures that even if someone gains access to the saved note file, they will not be able to read the content without the correct password. Furthermore, all encryption and decryption are done client-side, meaning your data never leaves your browser.

Why do I need to randomly move my mouse around the screen?

In 1337Pad, mouse movement is used to increase the entropy for the encryption process. Entropy, in this context, refers to the randomness and unpredictability of data used in the encryption process. The more entropy, the more secure the encryption. When the user moves their mouse randomly around the screen, the application collects mouse movement data, which consists of the x and y coordinates of the cursor. This data is then used as an additional source of randomness when generating a salt for the encryption process. The salt, combined with the user's password, strengthens the encryption by making it more resistant to attacks, such as brute-force or dictionary attacks. In other words, incorporating mouse movement data into the encryption process increases the overall security of the encrypted note, making it more difficult for an attacker to decipher the content without the correct password.

Features

Client-side encryption and decryption
Increased Entropy using Mouse Movements
Title input
Textarea for taking notes
Save, open, and day/night mode buttons
No internet connection required

How to use

Open 1337Pad in your web browser.
Enter a title for your note in the "Title" input field.
Write your note in the textarea provided.
Move your mouse randomly around the screen to increase the entropy for the encryption process. The progress bar will show the progress of entropy collection.
Enter a password in the "Password" input field. This password will be used to encrypt and decrypt your note, so make sure to remember it.
Click "Save" to save your note. The note will be saved as a ".1337" file, which contains the encrypted content.
To open a saved note, click "Open" and select the ".1337" file from your computer. Enter the correct password when prompted to decrypt and load the note.
Use the "Day/Night Mode" button to toggle between day and night modes for a more comfortable reading experience.
Enjoy using 1337Pad and keep your notes safe and secure!

Access 1337Pad via IPFS at ipfs://QmfVDUz1R94zpDnVgrSgLnX8hCD59cnpDjAi3ik52dvhUA or via the short link 1337Pad.com.
