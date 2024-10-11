# Desafio Controle De Fluxo
## Descrição do Projeto
Este projeto implementa um sistema simples que recebe dois números inteiros via terminal e realiza uma contagem incremental com base nos valores recebidos. O objetivo é imprimir a quantidade de interações entre os dois números, respeitando a regra de que o segundo número deve ser maior que o primeiro. Caso essa regra não seja atendida, uma exceção customizada é lançada.

## Estrutura do Projeto
O projeto possui as seguintes classes:

__Contador:__ Contém a lógica principal do programa, que inclui a leitura dos parâmetros do usuário e o método de contagem.
__ParametrosInvalidosException:__ Exceção customizada que é lançada quando o segundo número não é maior que o primeiro.
## Tecnologias Utilizadas
Java 8+  
Biblioteca padrão java.util.Scanner para receber a entrada do usuário.
