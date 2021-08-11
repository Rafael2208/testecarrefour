# testecarrefour
/*************************************************************************************
*Detalhe
*Desenvolva um programa capaz de ler um valor inteiro N. N * 2 linhas de saída vão ser apresentadas na execução do programa, seguindo a lógica do exemplo mais abaixo. Para os valores com mais de seis dígitos, todos os dígitos devem ser apresentados.

*Entrada
*O arquivo de entrada contém um número inteiro positivo N (1 < N < 1000).

*Saída
*Imprima a saída conforme o exemplo fornecido.

 
*Exemplo de Entrada	Exemplo de Saída
*5

*1 1 1
*1 2 2
*2 4 8
*2 5 9
*3 9 27
*3 10 28
*4 16 64
*4 17 65
*5 25 125
*5 26 126

************************************************************************************/

 import java.util.*
 
 fun main(args: Array<String>) {
 
        val leitor = Scanner(System.`in`)
        val N: Int = leitor.nextInt()
        for (i in 1..N) {
            println(i.toString() + " " + i * i + " " + i * i * i)
            println(i.toString() + " " + (i * i + 1) + " " + (i * i * i + 1))
        }
    }
