import random
import string

def generate_random_string(length):
    characters = string.ascii_letters + string.digits
    random_string = ''.join(random.choice(characters) for i in range(length))
    return random_string

# Exemplo de uso
random_length = 10
random_string = generate_random_string(random_length)
print(f"String aleatória de {random_length} caracteres: {random_string}")
