---
excalidraw-plugin: parsed
tags:
  - excalidraw
indices:
---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠== You can decompress Drawing data with the command palette: 'Decompress current Excalidraw file'. For more info check in plugin settings under 'Saving'

indices: [[Aprendizado de Máquina]],[[Options,Futures and Other Derivatives - Jonh C. Hull.pdf]].[[Matemática]],[[Finanças]]
# Excalidraw Data
## Text Elements
Contratos a Termo (Foward Contract) ^AFCscqhw

*Entre 2 partes ^T0pQT4OR

Posição Longa -> Compra o ativo negociado
em uma data especificada no futuro a um preço
especificado  ^aemkftdG

Posição Curta -> Vende o ativo na data e preços
especificados ^AukjNk7I

*Podem ser usar como hedge para mitigar riscos de câmbio ^KQW5DTUF

Investimento para reduzir o potencial de perda de outro investimento por se mover na direção contrária ^qIScwARK

> ([[Options,Futures and Other Derivatives - Jonh C. Hull.pdf#page=29&annotation=6297R|Options,Futures and Other Derivatives - Jonh C. Hull, p.29]]) ^1CdgFCgM

Pagamento ^VwmHkMEs

Pagamento ^eAbdXWDm

Preço de mercado na Data acordada (Preço Futuro) ^cBkdKP3c

Preço Acordado (Preço Immediato) ^SO4MBUoz

*Preço Futuro e Preço Imediato:
    Suponha que você tenha um ativo que vale 100R$. Você pode pedir ou emprestar dinheiro por 1 ano a 5%. Qual deve ser o preço futuro de 1 ano da ação?
         ^Z5y4VxXw

Devc ser 105 R$, pois caso seja mais do que isso seria possível pegar emprestado 100R$ comprar o ativo vender e o resultado da operação pagaria
o empréstimo e geraria lcuro ^YLdAlL9C

* Feito em mercados Over the Counter(OTC) -> Não necessitam de uma bolsa organizada como intermediador  ^OKVRhXSm

Contratos Futuros (Future Contracts) ^O2KSWXRE

*Similares a Contratos a Termo, mas com uma bolsa (exchange) intermediando e especificando características do contrato  ^p4MiP0ib

*Suponhamos que em Setembro o preço futuro do ouro para entrega em Dezembro é cotado a 6000 R$
    Se muitos traders querem ir long ao invés de short o preço sobe
    Se muitos traders querem ir short ao invés de long o preço desce ^6BtZwqmI

Options ^jsXbUL5y

1.Call Option -> Da o direito de comprar o ativo a uma certa data a um certo preço
2.Put Option -> Da o direito de vender um ativo a uma certa data a um certo preço ^DpqpBUGD

*Preço no contrato -> Preço de Exercício
*Data no contrato -> Data de Expiração ou Maturidade
*A opção da o direito ao holder a executar uma ação mas não obrigada diferentemente dos contratos
*Há custos para entrar em opções, diferente dos contratos que possuem apenas (margin requirements)
*Nos EUA um contrato de opções é um contrato de comprar ou vender 100 ações
Exemplo:
    Trader comprar uma opção com preço de 20$ por ação -> 2000R$ 100 ações para um preço de exercício de 300R$ a ação
    Isso significa que caso chegue na data estipulada e a ação não passe de 300R$ o trader perde 2000$, caso ela vá bem
    por exemplo, chegue a 400R$ ele consegue comprar as 100 ações ao preço de exercício e vende-las ao preço do mercado, 
    lucrando nessa operação ^PrhvqNBf

>[[Options,Futures and Other Derivatives - Jonh C. Hull.pdf#page=32&selection=9,57,11,22&color=important|Options,Futures and Other Derivatives - Jonh C. Hull, p.32]] ^84QEkGLg

> > The price of a call option decreases as the strike price increases, while the price of a put option increases as the strike price increases ^9Tq4b4Lw

Hedging ^nS6RWvLE

O Objetivo do hedging é reduzir seus riscos
Usando futuros:
    Suponha que estamos em Maio uma empresa brasileira que irá realizar uma compra no valor de 100U$ em Agosto comprando de um fornecedor estrangeiro.
    Esta empresa pode comprar U$ no mercado futuro de 3 meses a 5.70R$ isso faria com que a aempresa brasileira fixasse a sua compr a um preço de 570R$.
Usando opções:
     Considere um investidor que tem 100 ações de 10R$ e está preocupado com a queda dela nos próximos dois meses.
     Ele pode comprar1 put option com preço de exercício de 9.80R$ e o preço da opção é 0.5R$ o que lhe leva a um custo  de 100 * 0.5 -> 50R$, contudo 
    lhe garante que consiguirá vender a opção a 9.80R$ e caso o preço se mantenha acima disso ela expira.
 ^ywOYOSsv

Especulação ^doIdLSEJ

O objetivo da especulação é o lucro. 
Na seguinte situação:
    Cada contrato futuro é para a compra de 62500EU$, com preço de 1.2223 dolares por euro e a troca por U$ agora está em 1.2220 dolares por euro.
    Neste cenário temos duas opções:
    1. Comprar euros (Por exemplo 250000EU$ -> 4 contratos futuros) e caso eles valorizem vende-los e lucrar na transação
    2. Comprar 4 contratos futuros (Margin = 20000U$).
    No caso do preço do euro em relação ao dolar ao final do contrato seja 1.3:
    1 -> Lucra (1.3 - 1.2220) * 250 mil = 19500U$
    2 -> Lucra (1.3-1.2223) * 250 mil = 19450U$
Apesar de a situação nos dois cenários parecer pior para a opção com futuros, temos que lembrar que o investimento inicial de 1 foi de 250 mil * 1.2220 -> 
305500 U$ enquanto de 2 foi de 20 mil U$.
Isso demonstra a capacidade dos contratos futuros de alavancagem
    
     ^bagalzfL

No caso do preço do euro em relação ao dolar ao final do contrato seja 1.2:
1-> Perde (1.2-1.2220)*250 mil = - 5500U$
2-> Perde (1.2-1.2223)*250 mil = - 5575U$ ^W5hH30AC

>[[Options,Futures and Other Derivatives - Jonh C. Hull.pdf#page=40&selection=13,52,16,19&color=important|Options,Futures and Other Derivatives - Jonh C. Hull, p.40]] ^kWomLKZV

> > The key lesson from the financial crisis is that financial institutions should always be dispassionately asking “What can go wrong?”, and they should follow that up with the question “If it does go wrong, how much will we lose?” ^1SWhkLsC

Taxas de Juros ^otskG2TU

Um importante fator que influência a taxa de juros é o risco de crédtio
Risco de Credito  -> Risco do pagador não cumprir suas obrigações, Quanto mais alto  mais alto a taxa de juros 
A quantidade adicionada a uma taxa de juros sem risco para permitir risco de crédito é conhecido como spread de crédito

 ^PShPk78h

Taxas de Referência ^EhDrYuNq

LIBOR -> Históricamente importante
Novas taxas de referência buscam basear-se nas taxas overnight
 ^Plpv4N8R

Taxas Overnight ^mlDLJTyk

Bancos precisam atender a requisitos de reservas obrigatórias estabelecidos
pelo Banco Cnetral. Caso tenha um excesso de reeservas eles podem exmpretar
para um banco em déficit ^j96Rvp8A

## Embedded Files
0b2c4c00be5cd4396b20aa8be1f3d654fee2fc9a: $$S_t - K$$

b9dd2f0a09f973be53e1b482f9307ef7e064e020: $$K-S_t$$

%%
## Drawing
```compressed-json
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
```
%%