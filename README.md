# backend-test

## será avaliado

1. legibilidade
2. manutenção
3. testabilidade

## requisitos

* desenvolva a solução em uma linguagem da sua escolha: **C#** ou **Java**;
* crie testes;
* não é necessário utilizar nenhum framework, procure utilizar os recursos da linguagem;
* a solução deve ter um script que possa compilar e testar a partir da linha de comando;
* coloque a solução em um repositório GitHub;
* se precisar adicionar qualquer comentário/observação que achar importante, crie um arquivo `leiame.txt`;
* quando terminar, envie o link do projeto por e-mail;
* seja criativo!

## orientações

dado o seguinte log de movimentações de uma conta:

```text
Data              Descricao                   Valor               Categoria
17-Feb            TAM SITE                    -430,49             viagem
21-Mar		  INGRESSO.COM                -159,53             diversao
21-Mar		  NESPRESSO                   -55,9               alimentacao
22-Mar		  IBIS PARQUE OLIMPICO	      -143,15             hospedagem
27-Mar		  PONTO FRIOCOM               -213,26	
26-Apr		  LOJAS RENNER FL             -59,95              Vestuario
21-May		  Antonio Coutinho            120,00	
21-May		  Camila Souza                35,00	
24-May		  Evino	                      -62,43              alimentacao
24-May		  Uber Do Brasil Tecnolog     -6,66               transporte
25-May		  UATT                        -79,9               alimentacao
25-May		  Uber Do Brasil Tecnolog     -8,65               transporte
25-May		  COMETA TIETE                -28,28              transporte
25-May		  Droga Raia                  -14,09              higiene
26-May		  SONDA SUPERMERCADO          -41,89              alimentacao
26-May		  Uber Do Brasil Tecnolog     -9,39               transporte
27-May		  EBANX AIRBNB                -1.430,44           hospedagem
27-May		  Droga Raia                  -13,98              higiene
27-May		  ITUNES.COM/BILL             -74,9               diversao
29-May		  Hirota                      -13                 alimentacao
30-May		  HARU LANCHONETE             -75,9               alimentacao
01-Jun		  Uber Do Brasil Tecnolog     -7,04               TRANSPORTE
02-Jun		  Jose Mota                   35	
02-Jun		  Uber Do Brasil Tecnolog     -6,09               transporte
02-Jun		  RECARGAPAY BILH UNICO       -10                 transporte
03-Jun		  ITUNES.COM/BILL             -16,9               diversao
05-Jun		  Uber Do Brasil Tecnolog     -7,03               TRANSPORTE
12-Jun		  ITUNES.COM/BILL             -10,9               diversao
20-Jun		  EBANX AIRBNB                -338,6              hospedagem
20-Jun            EBANX AIRBNB 		      338,75              hospedagem
```

a partir do input de um arquivo de log no formato acima, montar um resultado com as seguintes informações:

* informar qual categoria cliente gastou mais;
* informar qual foi o mês que cliente mais gastou;
* quanto de dinheiro o cliente gastou;
* quanto de dinheiro o cliente recebeu;
* saldo total de movimentações do cliente.
