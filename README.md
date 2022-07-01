programa 
{
	funcao inicio() 
	{
	
	inteiro  numerodoQuarto = 1, quantidadeHospede = 2
	real valorDiaria = 0, soma = 0, valorTotal = 0 

	       escreva("número do quarto \n")
	       leia(numerodoQuarto)
	       escreva("quantidade de hospede, [ex:2]\n")   
	       leia(quantidadeHospede)
	       
	              enquanto(numerodoQuarto < quantidadeHospede){
	                  escreva("qual o número do quarto, [ex:1]\n")
	                  leia(numerodoQuarto)
	                  escreva("qual o valor da diária, [ex:1.000]\n")
	                  leia(valorDiaria)
	                  escreva("quarto",numerodoQuarto, ":R$ ",valorDiaria)
	                  quantidadeHospede = quantidadeHospede + 1
	                  soma = soma + valorDiaria}
	                  
	                  valorTotal = soma 
	                  
	                  escreva("no total de diária(s) é R$",valorTotal)
	              
	}
}
