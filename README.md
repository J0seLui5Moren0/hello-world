# Hola 
# Este programa te pide tus datos para ingresar a nustra pagina para que adoptes 

print("Bienvenido a ..... " )
print("""
 
  ###    #####     #####   ######   # #####           ##   ##  #######
 ## ##    ## ##   ### ###   ##  ##  ## ## ##          ### ###   ##   #
##   ##   ##  ##  ##   ##   ##  ##     ##             #######   ##
##   ##   ##  ##  ##   ##   #####      ##             ## # ##   ####
#######   ##  ##  ##   ##   ##         ##             ##   ##   ##
##   ##   ## ##   ### ###   ##         ##             ##   ##   ##   #
##   ##  #####     #####   ####       ####            ### ###  #######

 """)


# Solicitud de nombre 
nombre = input("Para empesar dime como te llamas.        ")
print()
print("Hola ", nombre, ", Bienvenido a Adopt me")
print()

# Socilitud de ciudad
ciudad = input("Para seguir dime en que ciudad naciste.       ")
print()
print("Hola ", ciudad, "Bienvenido a Adopt me")
print()

# Solicitar la edad al usuario
edad = int(input("Por favor, ingresa tu edad: "))

# Verificar si la edad es mayor o igual a 18
if edad >= 18:
    print("Eres mayor de 18 años. Puedes acceder.")
else:
    print("Lo siento, eres menor de 18 años. No puedes acceder.")
    
