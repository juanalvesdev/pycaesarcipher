Part 1

# TODO-1: Create a function called 'encrypt' that takes the 'text' and 'shift' as inputs.

def encrypt(plain_text, num):

    encrypted_word = []

    for letter in plain_text:
        shifted = alphabet.index(letter) + num
        chart = alphabet[shifted]
        encrypted_word.append(chart)
    print(''.join(encrypted_word))

encrypt(plain_text=text, num=shift)

# TODO-2: Inside the 'encrypt' function, shift each letter of the 'text' forwards in the alphabet by the shift amount and print the encrypted text.

# e.g.

# plain_text = "hello"

# shift = 5

# cipher_text = "mjqqt"

# print output: "The encoded text is mjqqt"

# HINT: How do you get the index of an item in a list:

# https://stackoverflow.com/questions/176918/finding-the-index-of-an-item-in-a-list

# 🐛Bug alert: What happens if you try to encode the word 'civilization'?🐛

# TODO-3: Call the encrypt function and pass in the user inputs. You should be able to test the code and encrypt a message.


Part 2
#TODO-1: Create a different function called 'decrypt' that takes the 'text' and 'shift' as inputs.

#TODO-2: Inside the 'decrypt' function, shift each letter of the 'text' _backwards_ in the alphabet by the shift amount and print the decrypted text.  
 #e.g.
#cipher_text = "mjqqt"
#shift = 5
#plain_text = "hello"
#print output: "The decoded text is hello"

#TODO-3: Check if the user wanted to encrypt or decrypt the message by checking the 'direction' variable. Then call the correct function based on that 'drection' variable. You should be able to test the code to encrypt _AND_ decrypt a message.
