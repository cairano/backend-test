# backend-test

## será avaliado

1. legibilidade
2. manutenção
3. testabilidade

## requisitos

* desenvolva a solução em **C#** ou **Java**;
* não é necessário utilizar nenhum framework, procure utilizar os recursos da linguagem;
* a solução deve ter um script que possa compilar e testar a partir da linha de comando;
* crie testes;
* para as chamadas de API utilize a URL [my-json-server.typicode.com/cairano/backend-test](https://my-json-server.typicode.com/cairano/backend-test/);
* coloque a solução em um repositório GitHub;
* utilize o arquivo `README.md` para descrever seu raciocínio, lógica e detalhes da solução;
* quando terminar, envie o link do projeto por e-mail;
* seja criativo!

## orientações

dado o log de movimentações de uma conta:

```text
Data              Descricao                   Valor               Categoria
21-Mar		  INGRESSO.COM                -159,53             diversao
17-Feb            TAM SITE                    -430,49             viagem
01-Jun		  Uber Do Brasil Tecnolog     -7,04               TRANSPORTE
22-Mar		  IBIS PARQUE OLIMPICO	      -143,15             hospedagem
27-Mar		  PONTO FRIOCOM               -213,26	
29-May		  Hirota                      -13                 alimentacao
24-May		  Evino	                      -62,43              alimentacão
21-May		  Camila Souza                35,00	
24-May		  Uber Do Brasil Tecnolog     -6,66               transporte
26-May		  SONDA SUPERMERCADO          -41,89              alimentacao
26-Apr		  LOJAS RENNER FL             -59,95              Vestuario
25-May		  COMETA TIETE                -28,28              transporte
26-May		  Uber Do Brasil Tecnolog     -9,39               transporte
03-Jun		  ITUNES.COM/BILL             -16,9               diversao
27-May		  EBANX AIRBNB                -1.430,44           hospedagem
25-May		  Droga Raia                  -14,09              higiene
27-May		  Droga Raia                  -13,98              higiene
30-May		  HARU LANCHONETE             -75,9               alimentacao
02-Jun		  Uber Do Brasil Tecnolog     -6,09               transporte
21-Mar		  NESPRESSO                   -55,9               alimentaçao
02-Jun		  Jose Mota                   35	
20-Jun		  EBANX AIRBNB                -338,6              hospedagem
02-Jun		  RECARGAPAY BILH UNICO       -10                 transporte
27-May		  ITUNES.COM/BILL             -74,9               diversao
05-Jun		  Uber Do Brasil Tecnolog     -7,03               TRANSPORTE
12-Jun		  ITUNES.COM/BILL             -10,9               diversao
25-May		  Uber Do Brasil Tecnolog     -8,65               transporte
20-Jun            EBANX AIRBNB 		      338,75              hospedagem
21-May		  Antonio Coutinho            120,00	
25-May		  UATT                        -79,9               alimentacao
```

* fazer o input dos dados acima, usando um arquivo no formato de log; 
* chamar os recursos de API e combinar os dados para processamento.

montar um resultado com as seguintes informações:

* exibir o log de movimentações de forma ordenada;
* informar o total de gastos por categoria;
* informar qual categoria cliente gastou mais;
* informar qual foi o mês que cliente mais gastou;
* quanto de dinheiro o cliente gastou;
* quanto de dinheiro o cliente recebeu;
* saldo total de movimentações do cliente.
