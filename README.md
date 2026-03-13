Algoritmo "JOGO DE ADIVINHAÇÃO"

Var
   numero_secreto, chute: inteiro
   sim: caracter

Inicio
   numero_secreto <- 7
   
   escreval("Tente advinhar o número de 1 a 10")
   leia(chute)
   
   se chute = numero_secreto entao
   escreval("Parabéns! Você acertou!")
   
   senao
   escreval("Errou! O número era: ", numero_secreto)
   
   fimse
   
Fimalgoritmo
