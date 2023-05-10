import random
import string

# Define the length of the password
password_length = 8

# Define the characters that can be used in the password
password_characters = string.ascii_letters + string.digits + string.punctuation

# Generate a random password
password = ''.join(random.choice(password_characters) for i in range(password_length))

# Print the randomly generated password
print("Your random password is:", password)
