Password generator, strength checker, and manager written in python3.

Password generator asks user for desired length and character types. User can choose text, numbers, alphanumeric or alphanumeric with special characters. Password is then generated.

Password strength checker grades passwords on a scale of 0-7. The score is based on length, character types - upper and lowercase text, numbers, special characters - and whether or not it is found in a common password list.

Password manager allows user to add or view usernames and passwords on a local .txt file. Passwords are readable within terminal when using the view function, but are encrypted within the .txt file. Encryption / decryption is done using Fernet.
