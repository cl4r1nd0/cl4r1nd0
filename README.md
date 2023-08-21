algoritmo "calculadias de vida"
// Função :  calcula os dias de vida de uma pessoa
// Autor :    cl4r1nd0
// Data : 21/08/2023
// Seção de Declarações 
var

dianascimento, mesnascimento, anonascimento, calculaano, calculames, calculadias, ano: inteiro
nome: caractere

inicio
// Seção de Comandos 
      escreval ("******* CALCULADORA DE DIAS DE VIDA DE UMA PESSOA ********")
      escreval
      escreval
      
      escreval ("Digite o nome da pessoa")
      leia (nome)
      escreval ("Em que ano estamos? (quatro dígitos)")
      leia (ano)
      
      escreval ("Digite o dia em que ",nome," nasceu: (1 a 30)")
      leia (dianascimento)
      
      escreval ("Digite o mês em que ",nome," nasceu: (1 a 12)")
      leia (mesnascimento)
      
      escreval ("Digite o ano em que ",nome," nasceu: (quatro dígitos)")
      leia (anonascimento)
      
      escreval ("***********************************************************")
      escreval ("**********************RESULTADO****************************")
      escreval ("***********************************************************")
      
      calculaano <- (ano - anonascimento) *365
      calculames <- (mesnascimento * 30) - (30-dianascimento)
      calculadias <- (calculaano + calculames)
      escreval
      escreval
      
      escreval (nome," possui: ",calculadias, " dias de vida")
      
      escreval
      escreval


      escreval ("***********************************************************")
      escreval ("************************FIM********************************")
      escreval ("***********************************************************")
      
      
      

fimalgoritmo
