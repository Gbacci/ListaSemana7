# ListaSemana7

1) B
2) B
3) D
4) D
5) B
6) B

7) 
```javascript
function Vote(idade) {
  if (idade < 16) {
    return "Não pode Votar!";
  } else if (idade >= 16 && idade < 18) {
    return "Voto facultativo!";
  } else {
    return "Voto obrigatório!";
  }
  }
```

8)
Class retangulo extends FormaGeométrica :
    Attributes:
        - Largura
        - Algura

    Constructor ( cor, largura, altura ):
        super.Constructor ( cor )
        Define o valor do atributo largura com o valor passado como parâmetro.
Define o valor do atributo altura com o valor passado como parâmetro.

    Method CalculateArea():
        Return largura * altura

Class Circle extends FormaGeométrica:
    Attributes:
        - raio
        
    Constructor ( cor, raio):
        super.Constructor ( cor )
        Define o valor do atributo raio com o valor passado como parâmetro.

    Method CalculateArea():
        Return 3.14 * raio * raio

        9)
        Function SimularCorrida ( Distância, VelocidadeInicial, Aceleração, VelocidadeMáxima, TempoMáximo ):
      time = 0
      currentSpeed = initialSpeed
      distanceCovered = 0

    While DistanceCovered < Distância e tempo <= TempoMáximo:
        DistanceCovered = DistanceCovered + CurrentSpeed
        time = time + 1

        If CurrentSpeed + acceleration <= VelocidadeMáxima:
            CurrentSpeed = CurrentSpeed + Acceleration
        Else:
            currentSpeed = maxSpeed

    If distanceCovered >= distance:
        Return: "O carro completou a corrida em + time +  minutes."
    Else:
        Return: "O carro não conseguiu completar a corrida no tempo máximo."

        10)
        Function MultiplicaçãodeMatriz ( MatrizA, MatrizB):
    # Checa se o número de colunas da matrizA é igual ao número de linhas da matrizB
    If size( MatrizA[0]) ≠ size(MatrizB) then:
        Return: "As matrizes não podem ser multiplicadas. O número de colunas da primeira matriz deve ser igual ao número de linhas da segunda matriz."
    Else:
        LinhasA <- size (matrizA)
        ColunasA <- size (matrizA[0])
        ColunasB <- size (matrizB[0])
        resultMatrix <- newMatrix (linhasA, colunasB)


        # Loop para calcular cada elemento da matriz resultado
        For i from 0 to linhasA-1 do:
            For j from 0 to colunasB-1 do:
                sum <- 0
                For k from 0 to colunasA-1 do:
                    sum <- sum + matrizA[i][k]  * matrizB[k][j]
                resultMatrix[i][j] <- sum

        Return resultMatrix





