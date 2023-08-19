# desconto-salario-liquido
import math
salario=float(input("salario a receber: "))
valevale=float(input("voce recebe vale transporte?"))
if salario < 1320:
    print ("desconto do salario", (salario-valevale))
elif salario < 2872:
    print ("desconto do salario",(salario-valevale))
elif salario > 3870:
    print ("desconto do salario",(salario-valevale))
else:
  valevale= "s" or "S"
  inss= (salario-inss*valevale)
print ("desconto do salario liquido",(salario-valevale))
