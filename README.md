vainilla=0
chocolate=0
fresa=0

print("Registro de heladeria")

for i in range(1,6):
    print(f"Pedido{i}")
    voto = input("Elige un sabor(vainilla,chocolate,fresa):").lower().strip()

    if voto == "vainilla":
        vainilla += 1
    elif voto =="chocolate":
        chocolate += 1 
    elif voto =="fresa":
         fresa  += 1 
    else:
        print("Error:Sabor no reconocido.")

print ("\n"+"-"*30)
print ("Resumen de ventas:")
print (f"vainilla: {vainilla}")
print (f"chocolate: {chocolate}")               
print (f"fresa: {fresa}")
print ("-"*30)
