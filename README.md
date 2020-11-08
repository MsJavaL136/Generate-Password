# Generate-Password
import string
import random 

# define the password by using "string letters+digits'', assign size for it/instead of asking how long user wants for pw
def pass_word(size = 6, chars = string.ascii_letters + string.digits):
    return ''.join(random.choice(chars) for _ in range(size))

pass_word()
