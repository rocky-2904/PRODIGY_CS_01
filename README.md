# CAESAR CIPHER
The Caesar Cipher is a classic encryption technique where each letter in the plaintext is shifted a certain number of places down or up the alphabet.
It's named after Julius Caesar, who is historically known to have used it.

# ENCRYPTION
Encryption:

Choose a shift value, often denoted as k.
Each letter in the plaintext is shifted k positions down the alphabet.
For example, with a shift of 3 (k=3):
'A' becomes 'D'
'B' becomes 'E'
...
'X' becomes 'A'
'Y' becomes 'B'
'Z' becomes 'C'

# DECRYPTION
Decryption:

To decrypt, you simply shift each letter k positions up the alphabet (or in the opposite direction of the original shift).
For example, with a shift of 3 (k=3):
'D' becomes 'A'
'E' becomes 'B'
...
'A' becomes 'X'
'B' becomes 'Y'
'C' becomes 'Z'

# EXAMPLE

Plaintext: "HELLO"
Shift: 3 (k=3)
Encrypting "HELLO":

'H' -> 'K'
'E' -> 'H'
'L' -> 'O'
'L' -> 'O'
'O' -> 'R'
So, "HELLO" encrypts to "KHOOR".

Decrypting "KHOOR" with the same shift (3):

'K' -> 'H'
'H' -> 'E'
'O' -> 'L'
'O' -> 'L'
'R' -> 'O'
