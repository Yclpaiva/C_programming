# C_programming

1. Faça um programa que leia um numero inteiro e o imprima.
	
    	#include <stdio.h>
    	
    	int main(){
    	
        int num;
        scanf("%d", &num);
        printf("%d", num);
        return 0;
        
        }

2. Faça  um programa que leia um numero real e o imprima.  
	
		#include <stdio.h>
		
		int main(){
		
	    float num;
	    scanf("%f", &num);
	    printf("%f", num);
	    return 0;
	    
		}
		
3. Peça ao usuario para digitar três valores inteiros e imprima a soma deles. 

    	#include <stdio.h>
    
	    int main(){
	        int a;
	        int b;
	        int c;
	        scanf("%d", &a);
	        scanf("%d", &b);
	        scanf("%d", &c);
	        printf("%d", a+b+c);
	        return 0;
	        
	    }

4. Leia um numero real e imprima o resultado do quadrado desse número.  

		#include <stdio.h>

		int main(){
		    int a;
		    scanf("%d", &a);
		    printf("%d", a*a);
		    return 0;
		    
		}
	
5. Leia um numero real e imprima a quinta parte deste número.

		#include <stdio.h>

		int main(){
		    float a;
		    scanf("%f", &a);
		    printf("%f", a/5);
		    return 0;
		    
		} 
6. Leia uma temperatura em graus Celsius e apresente-a convertida em graus Fahrenheit.
	A formula de conversão é: F = C∗(9.0/5.0)+32.0, sendo F a temperatura em Fahrenheit e C a temperatura em Celsius.

	    #include <stdio.h>
	    
	    int main(){
	        float celsius;
	        scanf("%f", &celsius);
	        printf("%f", (celsius * (9.0/5.0) + 32));
	        return 0;
	        
	    }

7. Leia uma temperatura em graus Fahrenheit e apresente-a convertida em graus Celsius.
A formula de conversão  é:  C = 5.0 ∗ (F − 32.0)/9.0, sendo C a temperatura em Celsius
e F a temperatura em Fahrenheit.

		#include <stdio.h>

		int main(){
		    float fahrenheit;
		    scanf("%f", &fahrenheit);
		    printf("%f", (fahrenheit - 32.0) * (5.0/9.0));
		    return 0;
		    
		}

8. Leia uma temperatura em graus Kelvin e apresente-a convertida em graus Celsius. A
formula de conversão é:́ C = K − 273.15, sendo C a temperatura em Celsius e K a
temperatura em Kelvin.

        #include <stdio.h>
        
        int main(){
        float kelvin;
        scanf("%f", &kelvin);
        printf("%f", kelvin - 273.15);
        return 0;
           
        }


9. Leia uma temperatura em graus Celsius e apresente-a convertida em graus Kelvin. A
formula de convers  ́ ao ̃ e: ́ K = C + 273.15, sendo C a temperatura em Celsius e K a
temperatura em Kelvin.

        #include <stdio.h>
        
        int main(){
        float celsius;
        scanf("%f", &celsius);
        printf("%f", celsius + 273.15);
        return 0;
           
        }
        
10. Leia uma velocidade em km/h (quilometros por hora) e apresente-a convertida em m/s ˆ
(metros por segundo). A formula de conversão é: M = K/3.6, sendo K a velocidade em
km/h e M em m/s.

        #include <stdio.h>
        
        int main() {
        float kmphora;
        printf("Digite a velocidade em km/h: ");
        scanf("%f", &kmphora);
        printf("%f km/h\n", kmphora);
        printf("%f m/s\n", (kmphora/3.6));
        
        return 0;
        }

11. Leia uma velocidade em m/s (metros por segundo) e apresente-a convertida em km/h
(quilometros por hora). A fórmula de conversão é: K = M ∗ 3.6, sendo K a velocidade
em km/h e M em m/s.

        #include <stdio.h>
        
        int main() {
        float mpsec;
        printf("Digite a velocidade em m/s: ");
        scanf("%f", &mpsec);
        printf("%f m/s\n", mpsec);
        printf("%f km/h\n", (mpsec * 3.6));
        
        return 0;
        }


12. Leia uma distancia em milhas e apresente-a convertida em quilometros. A fórmula de conversão é: K = 1, 61 ∗ M, sendo K a distancia em quilometros e M em milhas.

        #include <stdio.h>
        
        int main() {
        float milhas;
        printf("Digite a distância em Milhas: ");
        scanf("%f", &milhas);
        printf("%f mi/h\n", milhas);
        printf("%f km/h\n", (milhas * 1.61));
        
        return 0;
        }
        
13. Leia uma distancia em quilômetros e apresente-a convertida em milhas. A fórmula de conversão é: M = K / 1,61 , sendo K a distancia em quilometros e M em milhas.

        #include <stdio.h>
        
        int main() {
        float km;
        printf("Digite a distância em quilometros: ");
        scanf("%f", &km);
        printf("%f km/h\n", km);
        printf("%f mi/h\n", (km / 1.61));
        
        return 0;
        }


14. Leia um angulo em graus e apresente-o convertido em radianos. A fórmula de conversão é: R = G ∗ π/180, sendo G o angulo em graus e R em radianos é π = 3.14.

        #include <stdio.h>
        
        int main() {
        float graus;
        printf("Digite o angulo em graus: ");
        scanf("%f", &graus);
        printf("%f rad\n", (graus * (3.14/180)));
        
        return 0;
        }

15. Leia um angulo em radianos e apresente-o convertido em graus. A fórmula de conversão
é:  G = R ∗ 180/π, sendo G o angulo em graus e R em radianos e π = 3.14.

        #include <stdio.h>
        
        int main() {
        float rad;
        printf("Digite o angulo em rad: ");
        scanf("%f", &rad);
        printf("%f rad\n", (rad * (180/3.14)));
        
        return 0;
        }

16. Leia um valor de comprimento em polegadas e apresente-o convertido em centimetros.
A formula de converssão é: C = P ∗ 2, 54, sendo C o comprimento em centımetros e P o
comprimento em polegadas.

        #include <stdio.h>
        
        int main() {
        float pol;
        printf("Digite o valor em polegadas: ");
        scanf("%f", &pol);
        printf("%f centimetros\n", (pol * 2.54));
        
        return 0;
        }


17. Leia um valor de comprimento em centimetros e apresente-o convertido em polegadas.
A formula de conversão é:  P = C/2.54, sendo C o comprimento em cent ́ımetros e P  ocomprimento em polegadas.

        #include <stdio.h>
        
        int main() {
        float centimetros;
        printf("Digite o valor em centimetros: ");
        scanf("%f", &centimetros);
        printf("%f polegadas\n", (centimetros/2.54));
        
        return 0;
        }

18. Leia um valor de volume em metros cubicos m3 e apresente-o convertido em litros. A
formula de conversão é: L = 1000 ∗ M, sendo L o volume em litros e M o volume em
metros cubicos. 

        #include <stdio.h>
        
        int main() {
        float metroscub;
        printf("Digite o valor em metros cúbicos: ");
        scanf("%f", &metroscub);
        printf("%f Litros\n", (metroscub*1000));
        
        return 0;
        }

19. Leia um valor de volume em litros e apresente-o convertido em metros cubicos m3
. A formula de conversão é: M = L / 1000 , sendo L o volume em litros e M o volume em metros
cubicos.

        #include <stdio.h>
        
        int main() {
        float litros;
        printf("Digite o valor em litros: ");
        scanf("%f", &litros);
        printf("%f Metros Cúbicos\n", (litros/1000));
        
        return 0;
        }


20. Leia um valor de massa em quilogramas e apresente-o convertido em libras. A fórmula de conversão é: \( L = K * 2.205 \), sendo \( K \) a massa em quilogramas e \( L \) a massa em libras.

        #include <stdio.h>
        
        int main() {
        float quilos;
        printf("Digite o valor em quilos: ");
        scanf("%f", &quilos);
        printf("%f Libras\n", (quilos*2.205));
        
        return 0;
        }

21. Leia um valor de massa em libras e apresente-o convertido em quilogramas. A fórmula de conversão é: \( K = L * 0,45 \), sendo \( K \) a massa em quilogramas e \( L \) a massa em libras.

        #include <stdio.h>
        
        int main() {
        float libras;
        printf("Digite o valor em libras: ");
        scanf("%f", &libras);
        printf("%f Libras\n", (libras*0.45));
        
        return 0;
        }


22. Leia um valor de comprimento em jardas e apresente-o convertido em metros. A fórmula de conversão é: \( M = 0,91 * J \), sendo \( J \) o comprimento em jardas e \( M \) o comprimento em metros.

        #include <stdio.h>
        
        int main() {
        float jardas;
        printf("Digite o valor em jardas: ");
        scanf("%f", &jardas);
        printf("%f Metros\n", (jardas*0.91));
        
        return 0;
        }


23. Leia um valor de comprimento em metros e apresente-o convertido em jardas. A fórmula de conversão é: \( J = M/0,91 \), sendo \( J \) o comprimento em jardas e \( M \) o comprimento em metros.

        #include <stdio.h>
        
        int main() {
        float metros;
        printf("Digite o valor em metros: ");
        scanf("%f", &metros);
        printf("%f jardas\n", (metros/0.91));
        
        return 0;
        }


24. Leia um valor de área em metros quadrados \(m^2\) e apresente-o convertido em acres. A fórmula de conversão é: \(A = M * 0,000247\), sendo \(M\) a área em metros quadrados e \(A\) a área em acres.

        #include <stdio.h>
        
        int main() {
        float metrosquad;
        printf("Digite o valor em metrosquad: ");
        scanf("%f", &metrosquad);
        printf("%f acres\n", (metrosquad*0,000247));
        
        return 0;
        }


25. Leia um valor de área em acres e apresente-o convertido em metros quadrados \(m^2\). A fórmula de conversão é: \(M = A * 4048,58\), sendo \(M\) a área em metros quadrados e \(A\) a área em acres.

        #include <stdio.h>
        
        int main() {
        float acres;
        printf("Digite o valor em acres: ");
        scanf("%f", &acres);
        printf("%f metros quadrados\n", (acres*4048,58));
        
        return 0;
        }


26. Leia um valor de área em metros quadrados \(m^2\) e apresente-o convertido em hectares. A fórmula de conversão é: \(H = M * 0,0001\), sendo \(M\) a área em metros quadrados e \(H\) a área em hectares.

        #include <stdio.h>
        
        int main() {
        float metrosquad;
        printf("Digite o valor em metros quadrados: ");
        scanf("%f", &metrosquad);
        printf("%f hectares\n", (metrosquad*0,0001));
        
        return 0;
        }

27. Leia um valor de área em hectares e apresente-o convertido em metros quadrados \(m^2\). A fórmula de conversão é: \(M = H * 10000\), sendo \(M\) a área em metros quadrados e \(H\) a área em hectares.

        #include <stdio.h>
        
        int main() {
        float hec;
        printf("Digite o valor em hectares: ");
        scanf("%f", &hec);
        printf("%f metros quadrados\n", (hec*10000));
        
        return 0;
        }
        
28. Faça a leitura de três valores e apresente como resultado a soma dos quadrados dos três valores lidos.

        #include <stdio.h>
        
        int main() {
        float a;
        float b;
        float c;
        
        scanf("%f", &a);
        scanf("%f", &b);
        scanf("%f", &c);
        printf("Total somado: %f\n", (a+b+c));
        
        return 0;
        }

29. Leia quatro notas, calcule a média aritmética e imprima o resultado.

        #include <stdio.h>
        
        int main() {
        float a;
        float b;
        float c;
        float d;
        
        printf("digite a nota 1:");
        scanf("%f", &a);
        printf("digite a nota 2:");
        scanf("%f", &b);
        printf("digite a nota 3:");
        scanf("%f", &c);
        printf("digite a nota 4:");
        scanf("%f", &d);
        printf("média: %f\n", ((a+b+c+d)/4));
        
        return 0;
        }

30. Leia um valor em real e a cotação do dólar. Em seguida, imprima o valor correspondente em dólares.

        #include <stdio.h>
        
        int main() {
        float valorreal;
        float valordolar;
        
        printf("digite o valor do real: ");
        scanf("%f", &valorreal);
        printf("digite a cotação do dolar: ");
        scanf("%f", &valordolar);
        
        printf("Valor em dolares: %f\n", valorreal/valordolar);
        
        return 0;
        }

31. Leia um número inteiro e imprima o seu antecessor e o seu sucessor.

        #include <stdio.h>
        
        int main() {
        int num;
        
        printf("digite o valor: ");
        scanf("%d", &num);
        printf("Valor do antecessor: %d, Valor do sucessor:%d\n", num-1,num+1);
        
        return 0;
        }

32. Leia um número inteiro e imprima a soma do sucessor de seu triplo com o antecessor de seu dobro.

        #include <stdio.h>
        
        int main() {
        int num;
        
        printf("digite o valor: ");
        scanf("%d", &num);
        
        int sucessortriplo = ((num*3)+1) ;
        int antecessordobro = ((num*2)-1);
        printf("Valor do sucessor do triplo: %d\n", sucessortriplo);
        printf("Valor do antecessor do dobro: %d\n", antecessordobro);
        printf("Soma dos dois: %d\n",sucessortriplo+antecessordobro);
        return 0;
        }

33. Leia o tamanho do lado de um quadrado e imprima como resultado a sua área, \(A = lado^2\).

        #include <stdio.h>
        
        int main() {
        int num;
        
        printf("digite o valor: ");
        scanf("%d", &num);
        
        int sucessortriplo = ((num*3)+1) ;
        int antecessordobro = ((num*2)-1);
        printf("Valor do sucessor do triplo: %d\n", sucessortriplo);
        printf("Valor do antecessor do dobro: %d\n", antecessordobro);
        printf("Soma dos dois: %d\n",sucessortriplo+antecessordobro);
        return 0;
        }
        
34. Leia o valor do raio de um círculo e calcule e imprima a área do círculo correspondente. A área do círculo é dada por \(A = π * raio^2\), considerando \(pi = 3.141592\).

        #include <stdio.h>
        
        int main() {
        float num;
        
        printf("digite o raio do circulo: ");
        scanf("%f", &num);
        
        printf("A área do circulo é: %f", 3.141592*(num*num));
        return 0;
        }

35. Sejam \(a\) e \(b\) os catetos de um triângulo, onde a hipotenusa é obtida pela equação: hipotenusa = √(a^2 + b^2). Faça um programa que receba os valores de \(a\) e \(b\) e calcule o valor da hipotenusa através da equação. Imprima o resultado dessa operação.

        #include <stdio.h>
        #include <math.h>
        
        int main() {
        float valora;
        float valorb;
        
        printf("digite o valor a: ");
        scanf("%f", &valora);
        printf("digite o valor b: ");
        scanf("%f", &valorb);
        
        printf("O valor da hipotenusa é: %f", sqrt((valora*valora)+(valorb*valorb)));
        return 0;
        }

36. Leia a altura e o raio de um cilindro circular e imprima o volume do cilindro. O volume de um cilindro circular é calculado pela fórmula \(V = π * raio^2 * altura\), onde \(pi = 3.141592\).

        #include <stdio.h>
        
        int main() {
        float altura;
        float raio;
        
        printf("digite a altura: ");
        scanf("%f", &altura);
        printf("digite o raio: ");
        scanf("%f", &raio);
        
        printf("O volume do cilindro é: %f", (3.141592*((raio*raio)*altura)));
        return 0;
        }

37. Faça um programa que leia o valor de um produto e imprima o valor com desconto, considerando que o desconto foi de 12%.

        #include <stdio.h>
        
        int main() {
        float valor;
        
        
        printf("digite o valor: ");
        scanf("%f", &valor);
        
        
        printf("O valor com desconto é: %f", valor-(valor*0.12));
        return 0;
        }

38. Leia o salário de um funcionário. Calcule e imprima o valor do novo salário, sabendo que ele recebeu um aumento de 25%.

        #include <stdio.h>
        
        int main() {
        float valor;
        
        
        printf("digite o valor do salário: ");
        scanf("%f", &valor);
        
        
        printf("O valor com aumento é: %f", valor+(valor*0.25));
        return 0;
        }


39. A importância de R$ 780.000,00 será dividida entre três ganhadores de um concurso, sendo que:
  - O primeiro ganhador receberá 46%;
  - O segundo receberá 32%;
  - O terceiro receberá o restante. Calcule e imprima a quantia ganha por cada um dos ganhadores.

        #include <stdio.h>
        
        int main() {
        float valor = 780000;
        
        printf("O valor do primeiro ganhador: R$%f\n",valor*0.46);
        printf("O valor do segundo ganhador: R$%f\n",valor*0.32);
        printf("O valor do terceiro ganhador: R$%f\n", valor*(1-(0.46+0.32)));
        return 0;
        }

40. Uma empresa contrata um encanador a R$ 30,00 por dia. Faça um programa que solicite o número de dias trabalhados pelo encanador e imprima a quantia líquida que deverá ser paga, sabendo que são descontados 8% para imposto de renda.

        #include <stdio.h>
        
        int main() {
        int dias;
        
        printf("Dias trabalhados:");
        scanf("%d",&dias);
        
        printf("Valor a ser recebido: R$%d", dias*30);
        return 0;
        }


41. Faça um programa que leia o valor da hora de trabalho (em reais) e o número de horas trabalhadas no mês. Imprima o valor a ser pago ao funcionário, adicionando 10% sobre o valor calculado.

        #include <stdio.h>
        
        int main() {
        float qnthoras;
        float valorhora;
        
        printf("Horas trabalhadas no mês:");
        scanf("%f",&qnthoras);
        printf("Valor da hora:");
        scanf("%f",&valorhora);
        
        printf("Valor a ser recebido: R$%f",(qnthoras*valorhora)*1.1);
        return 0;
        }

42. Receba o salário-base de um funcionário. Calcule e imprima o salário a receber, sabendo que esse funcionário tem uma gratificação de 5% sobre o salário-base. Além disso, ele paga 7% de imposto sobre o salário-base.

        #include <stdio.h>
        
        int main() {
        float salariobase;
        
        printf("Salário base:");
        scanf("%f",&salariobase);
        
        printf("Valor a ser recebido: R$%f",(salariobase*1.05)-(salariobase*0.07));
        return 0;
        }


43. Escreva um programa de ajuda para vendedores. A partir de um valor total lido, mostre:
   - o total a pagar com desconto de 10%;
   - o valor de cada parcela, no parcelamento de 3× sem juros;
   - a comissão do vendedor, no caso da venda ser à vista (5% sobre o valor com desconto);
   - a comissão do vendedor, no caso da venda ser parcelada (5% sobre o valor total).


    #include <stdio.h>
    
    int main() {
    float valortotal;
     
    printf("Digite o valor total:");
    scanf("%f",&valortotal);
      
    printf("Total a pagar com desconto de 10 porcento: %f\n",valortotal*0.9);
    printf("Valor de cada parcela, no parcelamento de 3x sem juros: %f\n",valortotal/3);
    printf("a comissão do vendedor, no caso da venda ser à vista: %f\n",(valortotal*0.9)*0.05);
    printf("a comissão do vendedor, no caso da venda ser parcelada: %f\n", valortotal*0.05);
    return 0;
    }

44. Receba a altura do degrau de uma escada e a altura que o usuário deseja alcançar subindo a escada. Calcule e mostre quantos degraus o usuário deverá subir para atingir seu objetivo.

        #include <stdio.h>
        
        int main() {
        int degrau;
        int degraualcancar;
        
        printf("Digite o degrau atual:");
        scanf("%d",&degrau);
        printf("Digite o degrau para alcançar:");
        scanf("%d",&degraualcancar);
        
        
        printf("Degrais para subir: %d", degraualcancar-degrau);
        return 0;
        }

45. Faça um programa para converter uma letra maiúscula em letra minúscula. Use a tabela ASCII para resolver o problema.

        #include <stdio.h>
        
        int main() {
        char maiuscula;
        printf("Digite a letra maiuscula:");
        scanf("%c",&maiuscula);
        
        
        printf("Letra minuscula: %c", maiuscula+32);
        return 0;
  