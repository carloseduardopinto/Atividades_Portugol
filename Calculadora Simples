programa {
  logico reiniciar = verdadeiro

  funcao calcular() {

   caracter opcao 
   real fator1 
   real fator2 
   real result

   escreva("Calculadora básica\n")
   escreva("\nEscolha a operação:\n")
   escreva("1 - Adição\n")
   escreva("2 - Subtração\n")
   escreva("3 - Multiplicação\n")
   escreva("4 - Divisão\n")
   escreva("\nresposta:\t")
   leia(opcao)

    se (opcao == 1) {
      escreva("\nAdição:\n")
      escreva("\nDigite o primeiro fator:\t\n")
      escreva("resposta:\t")
      leia(fator1)
      escreva("\nDigite o segundo fator:\n")
      escreva("resposta:\t")
      leia(fator2)
      result = fator1 + fator2
      escreva("\nO resultado é:\t", result, "\n")
    }

    se (opcao == 2) {
      escreva("\nSubtração:\n")
      escreva("\nDigite o primeiro fator:\t\n")
      escreva("resposta:\t")
      leia(fator1)
      escreva("\nDigite o segundo fator:\n")
      escreva("resposta:\t")
      leia(fator2)
      result = fator1 - fator2
      escreva("\nO resultado é:\t", result, "\n")
    }
  
    se (opcao == 3) {
      escreva("\n Multiplicação:\n")
      escreva("\nDigite o primeiro fator:\t\n")
      escreva("resposta:\t")
      leia(fator1)
      escreva("\nDigite o segundo fator:\n")
      escreva("resposta:\t")
      leia(fator2)
      result = fator1 * fator2
      escreva("\nO resultado é:\t", result, "\n")
    }
  
    se (opcao == 4) {
      escreva("\nDivisão:\n")
      escreva("\nDigite o primeiro fator:\t\n")
      escreva("resposta:\t")
      leia(fator1)
      escreva("\nDigite o segundo fator:\t\n")
      escreva("resposta:\t")
      leia(fator2)
      result = fator1 / fator2
      escreva("\nO resultado é:\t", result, "\n")
    }
  }
  funcao inicio() {
    enquanto (reiniciar) {
      calcular()
      escreva("\nDeseja calcular novamente? digite 'verdadeiro' para sim e 'falso' para não:\n")
      escreva("Resposta:\t")
      leia(reiniciar)
      limpa() 
    }
  }
}
