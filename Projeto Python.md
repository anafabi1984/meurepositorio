Este projeto foi desenvolvido como atividade acadêmica utilizando a linguagem Python.
O programa recebe as medidas dos três lados de um triângulo e realiza:

🔧 Funcionalidades
Validação dos lados informados (não podem ser nulos ou negativos).

Verificação se os lados formam um triângulo válido.

Classificação do triângulo em:

Equilátero
Isósceles
Escaleno

Código do programa

print("Digite qual a medida 1 do lado do triângulo:")
lado1 = float(input())
print("Digite qual a medida 2 do lado do triângulo:")
lado2 = float(input())
print("Digite qual a medida 3 do lado do triângulo:")
lado3 = float(input())
if lado1 <= 0 or lado2 <= 0 or lado3 <= 0:
    print("Não é um triângulo (lado inválido)")
elif lado1 + lado2 <= lado3 or lado1 + lado3 <= lado2 or lado2 + lado3 <= lado1:
    print("Não é um triângulo.")
elif lado1 == lado2 == lado3:
    print("Triângulo Equilátero")
elif lado1 == lado2 or lado1 == lado3 or lado2 == lado3:
    print("Triângulo Isósceles")
else:
    print("Triângulo Escaleno")

Telas de execução

Caso 1
<img width="766" height="211" alt="image" src="https://github.com/user-attachments/assets/eb704940-a269-4c07-81fb-3176a111a32f" />

Caso 2
<img width="784" height="225" alt="image" src="https://github.com/user-attachments/assets/6839a73b-5024-4411-9b88-ecab76b352d6" />

Caso 3
<img width="705" height="220" alt="image" src="https://github.com/user-attachments/assets/819b42ec-12ac-446a-903e-f55c01cb7e38" />

Caso 4
<img width="831" height="228" alt="image" src="https://github.com/user-attachments/assets/1fb6deb1-3ab6-4a89-a998-5dd575638f9f" />

Caso 5
<img width="702" height="230" alt="image" src="https://github.com/user-attachments/assets/451b8cab-8543-4e31-8df1-b3d536099dd4" />

Caso 6
<img width="877" height="220" alt="image" src="https://github.com/user-attachments/assets/5687a244-3a1a-478a-9bb2-876c5d218bf5" />

Caso 7
<img width="863" height="227" alt="image" src="https://github.com/user-attachments/assets/cf3d77f1-1f5c-4e5b-a8ce-e1cbe3ff60ca" />

Caso 8
<img width="759" height="231" alt="image" src="https://github.com/user-attachments/assets/f003c624-630d-484b-8f71-fc008c88486a" />







