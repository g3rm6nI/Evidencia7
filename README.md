# Evidencia7

#LISTAS
# Creación de listas
nombres_familia = ["Javier", "Mario", "Caetano", "Carolina", "Sara", "Carlos", "Elvira", "Juan", "Liliana"]
temperaturas_octubre_2021 = [22.5, 23.0, 24.2, 25.8, 26.5, 27.1, 27.6, 28.2, 27.8, 26.7, 24.9, 23.4, 22.7, 21.9, 22.3, 23.8, 25.5, 26.7, 28.0, 27.2, 25.9, 24.6, 23.2, 22.4, 22.0, 21.6, 22.2, 23.7, 25.4, 26.9, 27.5, 26.3]
ciudades_visitadas = [ "Rosario", "Mendoza", "Salta", "Resistencia", "Corrientes", "Posadas",  "Formosa"]
fechas_importantes = ["23 de junio de 1983", "15 de septiembre de 2006", "26 de abril de 1992", "15 de marzo de 1980",
    "16 de mayo de 1996", "11 de junio de 2013", "9 de agosto de 2015"]

# Definición de las tuplas de datos de países con ubicación geográfica en lugar de población
pais1 = ("Argentina", "América del Sur", "Latitud: -34.61, Longitud: -58.38")
pais2 = ("Francia", "Europa", "Latitud: 48.86, Longitud: 2.35")
pais3 = ("China", "Asia", "Latitud: 35.68, Longitud: 103.84")

#Ordenamiento de LISTA Flia
nombres_familia.sort()
print(nombres_familia) 

#Ordenamiento de LISTA Temp
temperaturas_octubre_2021.sort()
print(temperaturas_octubre_2021)

#Agregado de Temp
temperaturas_octubre_2021.append(28.5, 29.0, 30.2, 31.8, 32.5, 33.1, 33.6, 34.2, 33.8, 32.7, 30.9, 29.4, 28.7, 27.9, 28.3) 
print(temperaturas_octubre_2021)

#Eliminar nombres
nombres_familia.remove("Sara")
nombres_familia.remove("Carlos")
print(nombres_familia)

#Eliminar ciudad
ciudades_visitadas.remove("Rosario")

#Mostrar todas las listas
print(nombres_familia)
print(temperaturas_octubre_2021)
print(ciudades_visitadas)
print(fechas_importantes)

#TUPLAS
#Creación de la lista que contiene las tuplas de países
paises_lista = [pais1, pais2, pais3]

#Mostrar los datos de los países con ubicación geográfica
for pais in paises_lista:
    nombre, continente, ubicacion = pais
    print(f"País: {nombre} | Continente: {continente} | Ubicación: {ubicacion}")

#Diccionario Flia
diccionario_Flia = {
    "12345678": "Javier",
    "23456789": "Mario",
    "34567890": "Caetano",
    "45678901": "Carolina",
    "10789012": "Sara", 
    "11456789": "Carlos", 
    "20345678": "Elvira",
    "26456789": "Juan",
    "29567890": "Liliana",
}

#Datos Flia ampliada
['6345678'] =  "José"
['5456789'] =  "Pedro"
['6567890'] =  "Elba"
['4678901'] =  "Ana"
['6789012'] =  "Darío"
['6456789'] =  "Ricardo"
['5345678'] =  "Elisa"

#Dicc Nuevos Datos
nuevos_datos = {
"6345678": "José",
"5456789": "Pedro",
"6567890": "Elba",
"4678901": "Ana",
"6789012": "Darío",
"6456789": "Ricardo",
"5345678": "Elisa"
}

#Mostrar Dicc
diccionario_Flia.items()
nuevos_datos.items()



