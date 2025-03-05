# Calculador-de-tempo-para-percorrer-x-dist-ncia
Estúdio Portugol

    programa {
      funcao inicio() {
    
        real distanciaTotal, velocidadeMedia, horas, tempo

        escreva("Digite a distania total a ser percorrida (em km/h) ")
        leia(distanciaTotal)

        escreva("Digite a velocidade media esperada (km/h) ")
        leia(velocidadeMedia)

        tempo = distanciaTotal/velocidadeMedia
        horas = tempo
    
        escreva("O tempo estimado para a viagem em horas é ", horas," horas")
      }
    }
