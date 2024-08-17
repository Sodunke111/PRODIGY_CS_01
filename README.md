THIS IS A CAESAR CIPHER ALGORITHM

A Python program that can encrypt and decrypt text using the Caesar Cipher algorithm. Allow users to input a message and a shift value to perform encryption and decryption.

HOW TO USE IT:

Open a Terminal or Command Prompt:

On Windows, you can open Command Prompt by searching for "cmd" in the Start menu.
On macOS or Linux, open the Terminal application.
Navigate to the Directory:
Use the cd command to navigate to the directory where you saved your Python file. For example:

cd path/to/your/directory  
Run the Program:
Execute the program by typing the following command:

python caesar_cipher.py  
If your system requires Python 3 specifically, you may need to use:

python3 caesar_cipher.py  
Interact with the Program:
Once the program is running, you will see prompts asking you to choose an action.

Choose an Action:
Type encrypt to encrypt a message or decrypt to decrypt a message.

Input the Message:
You will be prompted to enter the message you wish to encrypt or decrypt.

Input the Shift Value:
The next prompt will ask for the shift value (an integer). For example, entering 3 will shift letters three places forward in the alphabet, while -3 would shift them three places backward.

View the Result:
The program will display the resulting encrypted or decrypted message.

Repeat or Exit:
You can repeat the process for additional messages or type exit to terminate the program.

Example Session
Here’s how a session might look:

Start program:

Choose an action (encrypt/decrypt/exit):  
User chooses to encrypt:

Choose an action (encrypt/decrypt/exit): encrypt  
Input a message:

Enter your message: Hello, World!  
Input a shift value:

Enter shift value (positive or negative): 3  
Output encrypted message:

Encrypted message: Khoor, Zruog!  
User chooses to decrypt:

Choose an action (encrypt/decrypt/exit): decrypt  
Input the encrypted message:

Enter your message: Khoor, Zruog!  
Input the same shift value:

Enter shift value (positive or negative): 3  
Output decrypted message:

Decrypted message: Hello, World!  
Exit the program:

Choose an action (encrypt/decrypt/exit): exit  
Exiting the program.  
Tips

. Remember that the shift value can be positive or negative.
. Non-alphabetic characters (like spaces, punctuation) are not altered by the cipher.
. Feel free to experiment with different messages and shift values!
. If you encounter any issues or have more questions, feel free to ask!
