def caesar_cipher_encrypt(text, shift):  
    encrypted_text = ""  
    for char in text:  
        if char.isalpha():  # Check if character is a letter  
            shift_base = ord('A') if char.isupper() else ord('a')  
            encrypted_text += chr((ord(char) - shift_base + shift) % 26 + shift_base)  
        else:  
            encrypted_text += char  # Non-alphabetic characters are unchanged  
    return encrypted_text  

def caesar_cipher_decrypt(text, shift):  
    return caesar_cipher_encrypt(text, -shift)  # Decrypting is just encrypting with negative shift  

def main():  
    while True:  
        action = input("Choose an action (encrypt/decrypt/exit): ").strip().lower()  
        if action == 'exit':  
            print("Exiting the program.")  
            break  
        if action not in ['encrypt', 'decrypt']:  
            print("Invalid choice! Please choose 'encrypt', 'decrypt', or 'exit'.")  
            continue  
        
        message = input("Enter your message: ")  
        shift = int(input("Enter shift value (positive or negative): "))  
        
        if action == 'encrypt':  
            encrypted_message = caesar_cipher_encrypt(message, shift)  
            print(f"Encrypted message: {encrypted_message}")  
        elif action == 'decrypt':  
            decrypted_message = caesar_cipher_decrypt(message, shift)  
            print(f"Decrypted message: {decrypted_message}")  

if __name__ == "__main__":  
    main()
