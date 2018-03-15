#include  <stdio.h>
#include  <stdlib.h>						
#include <locale.h>

/*Autor : Mateus Gomes Costa Barbosa
  Data de criação: 25/02/2018 
  Data de atualização 14/03/2018 - ATUALIZAÇÃO V3.0 (Inclusão de exercícios da lista 3)
  Lista de exercícios */




int main ()
{	int exer;
	setlocale(LC_ALL, "Portuguese");
 	printf ("\n Autor : Mateus Gomes Costa Barbosa\n Data de criação: 25/02/2018 \n Data de atualização 14/03/2018 ATUALIZAÇÃO V3.0 \n (Inclusão de exercícios da lista 3) \n Lista de exercícios \n");
	printf("\n Lista de Exercícios 1: de 1 à 8 ");
	printf("\n Lista de Exercícios 2: de 9 à 16 ");
	printf("\n Lista de Exercícios 3: de 16 à 20 ");
	printf ("\n ESCOLHA OS EXERCÍCIOS DIGITANDO DE 1 a 20 \n");
	 printf ("\n Digite o número do exercÍcio: ");
 		scanf ("%d",&exer);

 switch (exer)
{
 	case 1:
 		exercicio_1();
	 break;
	  	case 2:
 			exercicio_2();
	 break;  
	  	case 3:
	  		exercicio_3();
	break;
		case 4:
			exercicio_4();
	break;
		case 5:
			exercicio_5();
	break;
	
	    	case 6:
			exercicio_6();
	break;
	
		case 7:
			exercicio_7();
	break;
	
		case 8:
			exercicio_8();
	break;
	
		case 9:
			exercicio_9();
	break;
		case 10:
			exercicio_10();
	break;
	
		case 11:
			exercicio_11();
	break;
		
		case 12:
			exercicio_12();
	break;
	
		case 13:
			exercicio_13();
	break;
		
		case 14:
			exercicio_14();
	break;
			
		case 15:
			exercicio_15();
	break;
				
		case 16:
			exercicio_16();
	break;
	
		case 17:
			exercicio_17();
	break;
	
		case 18:
			exercicio_18();
	break;
    	case 19:
			exercicio_19();
	break;
	
	  	case 20:
			exercicio_20();
	break;

	default :
     printf ("\nÉ SÓ DE 1 À 20 SEU ANIMAL !!\nSaindo do programa...");
     printf ("\n");
     system ("pause");
}}

exercicio_1()
{	int quadrado;
		printf ("\n Exercicio 1: Dado um número inteiro não-nulo, imprima o seu quadrado");
		printf ("\n");
		printf ("\n Insira o número : ");
		scanf("%d", &quadrado);
			quadrado = quadrado*quadrado;
    			printf ("\n o quadrado do número é : %d", quadrado);
    			printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			system ("pause");
    			system ("cls");
    return main ();
}	

exercicio_2()

{
	float a, b ,c;
	printf ("\n Exercicio 2: Faça um programa que leia as 3 notas de um aluno e calcule a média aritmética deste aluno.");
	printf ("\n");
	printf ("\n Insira a primeira nota : ");
		scanf("%f", &a);
	printf ("\n Insira a segunda nota : ");
		scanf("%f", &b);
	printf ("\n Insira a terceira nota : ");
		scanf("%f", &c);
	printf ("\n A média é : %3.1f ", ((a+b+c)/3));
	    		printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			system ("pause");
    			system ("cls");
		 return main ();
	
}

exercicio_3()
{
	float a, b ,c;
	printf ("\n Exercicio 3: Faça um programa que leia as 3 notas de um aluno \n e calcule a média final deste aluno. Considerar que a média é ponderada e que o peso das notas é: 2, 3 e 5, respectivamente.");
	printf ("\n");
	printf ("\n Insira a primeira nota : ");
		scanf("%f", &a);
	printf ("\n Insira a segunda nota : ");
		scanf("%f", &b);
	printf ("\n Insira a terceira nota : ");
		scanf("%f", &c);
	printf ("\n A média ponderada é : %3.1f ",((a*2)+(b*3)+(c*5))/10);
			    printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			system ("pause");
    			system ("cls");
		 return main ();
}

exercicio_4()
{
	float produto;
			printf ("\n Exercicio 4  Em épocas de pouco dinheiro, os comerciantes estão procurando aumentar suas vendas oferecendo desconto. \n Faça um programa que possa receber um valor de um produto e que escreva o novo valor tendo em vista \n que o desconto foi de 9%% .");
		printf ("\n");
	printf("\n Insira o valor do Xbox: ");
		scanf("%f",&produto);
	printf("\n Valor do Xbox: %3.2f", produto);
		printf("\n Valor do Xbox com desconto: %6.2f", produto*0.91);
			    printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			system ("pause");
    			system ("cls");
			 return main ();
}

exercicio_5()
{
	float trumpos,temers;
			printf ("\n Exercicio 5: Faça o programa que calcule o valor em Reais, correspondente aos dólares \n que um turista possui no cofre do hotel. \n Solicitar os dados: Quantidade de dólares guardados no cofre e cotação do dólar naquele dia.");
		printf ("\n");
	printf("\n Insira o valor da cotação do dólar: ");
		scanf("%f",&trumpos);
	printf("\n Quanto Trumps eu tenho : ");
		scanf("%f",&temers);
	printf("\n Isso da em temers: %3.2f",temers*trumpos);
			    printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			system ("pause");
    			system ("cls");
		 return main ();
		/*printf("\BAFORA TEMER !")*/
}

exercicio_6()
{		printf ("\n Exercicio 6: A Loja Mamão com Açúcar está vendendo seus produtos em 5 (cinco) prestações sem juros. \n Faça um programa que receba um valor de uma compra e mostre o valor das prestações ");
		printf ("\n");
	float produto_xxx;
	printf("\n Insira o valor do Xiaomi: ");
		scanf("%f",&produto_xxx);
	printf("\n Valor do Xiaomi com as prestações: %3.2f", produto_xxx/5);
				printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			system ("pause");
    			system ("cls");
		 return main ();
}

exercicio_7()

{		printf ("\n Exercicio 7: Faça um programa que receba o preço de custo de um produto e mostre o valor de venda. \n Sabe-se que será acrescido um percentual informado pelo usuário sobre o preço de custo. ");
		printf ("\n");
	
	float custo_propriedade;
    int   porcentagem;
	printf("\n Custo da propiredade: ");
		scanf("%f",&custo_propriedade);
	printf ("\n porcentagem: ");
		scanf("%d",&porcentagem);
	printf ("\n Valor Final: %3.3f ", custo_propriedade+((custo_propriedade*porcentagem)/100));
				printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			system ("pause");
    			system ("cls");
		 return main ();
}

exercicio_8()
{ 			printf ("\n Exercicio 8: O custo ao consumidor, de um carro novo, é a soma do custo de fábrica com a percentagem do distribuidor \n e dos impostos (aplicados ao custo de fábrica). Supondo que a percentagem do distribuidor seja de 28%% e os \n impostos de 45%%, escrever um programa para ler o custo de fábrica de um carro e escrever o custo ao consumidor.");
		printf ("\n");
 	float valor_carro;
 		printf ("\n Valor do Carro: ");
 			scanf("%f",&valor_carro);
 		printf ("\n Valor cobrado fábrica: %3.3f", (valor_carro*0.28));
 		printf ("\n Valor cobrado imposto: %3.3f", (valor_carro*0.45));
 		printf ("\n Valor final: %3.3f", (valor_carro*0.73));
 				printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			system ("pause");
    			system ("cls");
 			 return main ();
 		
}

exercicio_9()

{ 
		printf ("\n Exercicio 9: Escreva um algoritmo que leia três números inteiros (A, B, C) e calcule a seguinte expressão: \n D = R+S/2 \n Onde: R = (A+B)² e S = (B+C)²");
		printf ("\n");
    int a,b,c,d,r,s;
    	printf ("\n Valor A: ");
        scanf("%d",&a);
            	printf ("\n Valor B: ");
        scanf("%d",&b);
           	printf ("\n Valor C: ");
        scanf("%d",&c);
            printf ("\n Valor de R: %d", r=(a+b)*2);
            printf ("\n Valor de S: %d", s=(b+c)*2);
            printf ("\n Valor de D: %d", d=(r+s)/2);
	    		printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			system ("pause");
    			system ("cls");
		 return main ();
}




exercicio_10()

{ 
    	printf ("\n Exercicio 10: O coração humano bate em média uma vez por segundo. Desenvolva um algoritmo para \n calcular e escrever quantas vezes o coração de uma pessoa baterá se viver X anos. \n Dado de entrada: idade da pessoa (inteiro em anos). \n Considerações: 1 ano = 365,25 dias, 1 dia = 24horas, 1 hora = 60 minutos e 1 minuto = 60 segundos.");
		printf ("\n");
		int idade;
		int batimentos;
		
            printf ("\n Insira a idade : ");
            scanf ("%d",&idade);
            
        printf  ("\n A média de batidas de coração por ano é : %d",  batimentos = idade*365.25*24*60*60);
	    		printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			system ("pause");
    			system ("cls");
		 return main ();
}



exercicio_11 ()

{	 	
	printf ("\n Exercicio 11:  Fazer um algoritmo ler uma temperatura dada em graus Celsius e imprimir o equivalente em Farenheit. \n Onde: Farenheit = 1,8*Celsius+32." );
		printf ("\n");
    float celsius;
        printf("\n insira a temperatura em celsius : " );
            scanf ("%f", &celsius);
        printf("\n Temperatura equivalente em farenheit é : %2.1f", (1.8*celsius)+32);
	    		printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			system ("pause");
    			system ("cls");
	return main ();
            
}

exercicio_12 ()

{ 		printf ("\n Exercicio 12:  Fazer um algoritmo ler uma quantidade de chuva dada em polegadas e imprimir o equivalente \n em milímetros (1 polegada = 25,4 mm)." );
		printf ("\n");

    float polegadas,milimetros;
    polegadas = 25,4;
        printf("\n Insira o nível de chuva em milímetros : " );
            scanf ("%f", &milimetros);
        printf("\n Chuva equivalente em polegadas é : %2.1f", (polegadas*milimetros));
	    		printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			system ("pause");
    			system ("cls");
	return main ();
            
}

exercicio_13 ()

{ 		printf ("\n Exercicio 13:  Dada a base e a altura de uma pirâmide, fazer um algoritmo que calcule e escreva: \n Volume = 0,33*Base*Altura." );
		printf ("\n");
    float base,altura;
            printf("\n Insira o valor da base : " );
                scanf ("%f", &base);
            printf("\n Insira o valor da altura : " );
                scanf ("%f", &altura);
            printf("\n O volume da pirâmide é : %2.1f", 0.3*(base*altura));
	    		printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			printf ("\n");
    	     	system ("pause");
    			system ("cls");
	return main ();
	
     }
     

exercicio_14 ()

{ 	 	printf ("\n Exercicio 14:  Escrever um algoritmo que leia: \n • a percentagem do IPI a ser acrescido no valor das pecas; \n • o código da peca 1, valor unitário da peca 1, quantidade de pecas 1;  \n • o código da peca 2, valor unitário da peca 2, quantidade de pecas 2; \n • O algoritmo deve calcular o valor total a ser pago e apresentar o resultado: \n Valor Total = (Valor da 1ª peça*Quantidade da 1ª peça + Valor da 2ª peça*Quantidade da 2ª peça)*(IPI/100)+1." );
		printf ("\n"); 
	int cod_pec_1 ,cod_pec_2;
		cod_pec_1 = 156576723;
		cod_pec_2 = 324245561;
		int quant_pec_1,quant_pec_2;
    	float valor_total,valor_pec_1,valor_pec_2,IPI,IPI_APLICADO;
    	
    		IPI_APLICADO = IPI=valor_pec_1+valor_pec_2;
			valor_total = (valor_pec_1*quant_pec_1)+(valor_pec_2*quant_pec_2)*(IPI_APLICADO/100)+1;
				
				
				printf ("\n Porcentagem do IPI a ser acrescido no valor das peças : ");
					scanf("%f",&IPI);
						printf ("\n");			
			
				printf ("\n Peça 1: %d",cod_pec_1);    					
					printf ("\n Insira o valor da peça do produto 1: ");
    				scanf("%f",&valor_pec_1);
    						printf ("\n Insira o a quantidades de peças disponivel do produto 1: ");
    						scanf("%d",&quant_pec_1);
    						
    				printf ("\n Peça 2: %d",cod_pec_2);
    				printf ("\n Insira o valor da peça do produto 2: ");
    					scanf("%f",&valor_pec_2);
    				    	printf ("\n Insira o a quantidades de peças disponivel do produto 2: ");
    						scanf("%d",&quant_pec_2);    						
    						printf ("\n Valor total das peças : %3.1f ", valor_total=(valor_pec_1*quant_pec_1)+(valor_pec_2*quant_pec_2)*(IPI_APLICADO/100+1));
    			printf ("\n");
    			printf ("\n");
	    		printf ("\n");
    			printf ("\n");
    			system ("pause");
    			system ("cls");
	return main ();
}


exercicio_15 ()

{
     	 	printf ("\n Exercicio 15:  Escrever um algoritmo que leia o nome de um funcionário, seu numero de horas \n trabalhadas, o valor que recebe por hora, o número de filhos com idade menor que 14 anos e \n o valor do salário família (pago por filho com menos de 14 anos), e que calcule o salário total \n deste funcionário. Ao final escreva o seu nome e o seu salário total." );
		printf ("\n");
		char nome_colaborador [100];
		float horas_trabalhadas,salario_hora, salario_familia;
		int num_filhos;
		
		   printf("\n Insira o nome do colaborador : " );
                scanf ("%s",&nome_colaborador);
            printf("\n Insira as horas trabalhadas do colaborador : " );
                scanf ("%f",&horas_trabalhadas);
            printf("\n Insira o salário por hora do colaborador  : " );
                scanf ("%f",&salario_hora);
           printf("\n Número de filhos menores de 14 anos do colaborador : " );
                scanf ("%d",&num_filhos);   
            printf("\n Insira o valor do salário_familia : ");
                scanf ("%d", &salario_familia);       
            printf("\n O salário total do colaborador %s à receber é : %3.2f", nome_colaborador, (horas_trabalhadas*salario_hora)+(num_filhos*salario_familia));
            printf ("\n");
    			printf ("\n");
	    		printf ("\n");
    			printf ("\n");
    			system ("pause");
    			system ("cls");
	return main ();
            
            
    
}


exercicio_16 ()

{ 
	printf ("\n Escrever um algoritmo que leia o valor de uma compra em dólares, a cotação do dólar no dia da compra, \n o percentual de ICMS e o percentual de lucro da empresa. Calcule e escreva o valor a ser pago em reais, sabendo-se que \n o percentual de lucro e o percentual de ICMS incidem sobre o valor em reais.");
	float VD,COTACAO,PICMS,PLUCRO,ICMS,LUCRO,VR;

	printf("\n Valor de uma compra em dólares : ");
			scanf("%f",&VD);
    printf("\n Cotação do dolar: ");
			scanf("%f",&COTACAO);
	printf("\n Percentual de ICMS: ");
			scanf("%f",&PICMS);
	printf("\n Percentual de lucro: ");
		scanf("%f",&PLUCRO);
	VR = VD*COTACAO;
	ICMS = VR*PICMS/100;
	LUCRO = VR*PLUCRO/100;
	VR = VR+ICMS+LUCRO;
	printf("\n Valor a ser pago em reais: %8.2f",VR);
				printf ("\n");
    			printf ("\n");
	    		printf ("\n");
    			printf ("\n");
    			system ("pause");
    			system ("cls");
	return main ();
}


exercicio_17 ()
    
{ printf ("\n Uma empresa resolveu conceder descontos de 10%% nas vendas superiores a 1000 \n reais. Faça um programa que leia o valor da venda\n e informe o valor a ser pago.");
    float valor, desconto,valor_desconto;
    printf ("\n Inrsira o valor: ");
        scanf ("%f",&valor);
        desconto = 0.1;
        valor_desconto = valor-desconto;
        if (valor>1000)
    printf ("\n O valor a pagar será: %3.2f",valor_desconto );
         if (valor<1000)
    printf ("\n O valor a pagar será: %3.2f",valor);
       			printf ("\n");
    			printf ("\n");
	    		printf ("\n");
    			printf ("\n");
    			system ("pause");
    			system ("cls");
    return main ();
        
            
    
}

exercicio_18()

{
	float a, b ,c, media;
	printf ("\n Exercicio 18: . Entrar com 3 notas de um aluno e informar a sua situação \n (APROVADO caso média aritmética >=7 e REPROVADO caso contrário");
	printf ("\n");
	printf ("\n Insira a primeira nota : ");
		scanf("%f", &a);
	printf ("\n Insira a segunda nota : ");
		scanf("%f", &b);
	printf ("\n Insira a terceira nota : ");
		scanf("%f", &c);
	media = (a+b+c)/3;
	printf ("\n A média é : %3.1f ", media);
	if (media >=7)
	   printf ("\n O aluno está Aprovado");
	else
	    printf ("\n O aluno está Reprovado");
	    		printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			system ("pause");
    			system ("cls");
		 return main ();
	
}


exercicio_19()
{
    printf ("\n Exercicio 19: Solicitar um número inteiro e informar se é positivo, negativo ou nulo."); 

 int numero;
 
  printf ("\n Qual é o número ?: ");
    scanf ("%d",&numero);

    if (numero==0)
    printf ("\n Número é N U L O !");
        if (numero>0)
    printf ("\n Número é P O S I T I V O !");  
            if (numero<0)
    printf ("\n Número é N E G A T I V O !");  
        	    printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			system ("pause");
    			system ("cls");
		 return main ();
        
}

exercicio_20()
{
    
 float saldo_medio, credito;
    printf ("\n Insira o saldo médio: ");
        scanf ("%f",&saldo_medio);
        
    if (saldo_medio >=0 && saldo_medio <=200)
      credito == 0;
    
    
    if (saldo_medio >=200.01 && saldo_medio <=400)
        credito = saldo_medio*0.20;
       
    
    if (saldo_medio >600.01)
        credito = saldo_medio*0.40;
    printf ("\n O seu saldo médio é de: %3.2f", saldo_medio);
    printf ("\n O Valor de crédito disponivel é de: %3.2f", credito);
        	    printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			printf ("\n");
    			system ("pause");
    			system ("cls");
		 return main ();
    
}


