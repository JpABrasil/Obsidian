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

Estratégias de Hedging com Futuros ^oXX5E1gj

> [!PDF|187, 97, 229] [[Options,Futures and Other Derivatives - Jonh C. Hull.pdf#page=70&annotation=6309R|Options,Futures and Other Derivatives - Jonh C. Hull, p.70]] ^Mw8uXYXm

> > When an individual or company chooses to use futures markets to hedge a risk, the objective is often to take a position that neutralizes the risk as far as possible ^uxpzcxe5

Short Hedge: 
    Apropriado quando já se tem o asset e se espera vender em um tempo futuro ou quando sabe-se que irá compra-lo e vende-lo no futuro
    Ex: Ganharei 5U$ em 3 meses, se o dólar valorizar em relação ao real eu terei lucro e no inverso prejuizo, para anular isso faço um short
         hedge no qual entro vendido e caso o doólar suba eu perco, mas caso desça eu ganho. Assim diminuindo o risco. ^m63QjJHS

Long Hedge:
    Quando sabe-se que irá comprar um asset no futuro e quer fixa-lo à um preço8 ^K6kflM8T

> ([[Options,Futures and Other Derivatives - Jonh C. Hull.pdf#page=73&annotation=6312R|Options,Futures and Other Derivatives - Jonh C. Hull, p.73]]) ^GgAEVcrI

> A company that does not hedge can expect its profit margins to be roughly constant. However, a company that does hedge can expect its profit margins to fluctuate! ^Y6cFERzd

Empresas de manufatura que não fazem hedge tem seus lucros constantes já que sobem e descem seus preços de venda
de acordo com o preço da matéira-prima, enquanto empresas que fazem hedging podem ter seus lucros aumen-
tados ou diminuídos. ^8mwP3np2

> ([[Options,Futures and Other Derivatives - Jonh C. Hull.pdf#page=74&annotation=6315R|Options,Futures and Other Derivatives - Jonh C. Hull, p.74]]) ^hhShmrm6

> President: This is terrible. We’ve lost $10 million in the futures market in the space of three months. How could it happen? I want a full explanation. Treasurer: The purpose of the futures contracts was to hedge our exposure to the price of oil, not to make a profit. Don’t forget we made $10 million from the favorable effect of the oil price increases on our business. President: What’s that got to do with it? That’s like saying that we do not need to worry when our sales are down in California because they are up in New York. Treasurer: If the price of oil had gone down . . . President: I don’t care what would have happened if the price of oil had gone down. The fact is that it went up. I really do not know what you were doing playing the futures markets like this. Our shareholders will expect us to have done particularly well this quarter. I’m going to have to explain to them that your actions reduced profits by $10 million. I’m afraid this is going to mean no bonus for you this year ^d44Wimx9

Risco Base:
    Causas:
        1.Assets não serem exatamente iguais 
        2.Incerteza na data da venda
        3.O contrato poderia ter de ser fechado 
            antes do mês de delivery
Base-> Spot Price do asset - Preço no contrato futuro ^2B6emxZH

Considerando um posição short no tempo 1 é o spot price no tempo 2 + o lucro dos futuros ^DMQ8hW6C

Base ^zjtssN1Z

Spot Price ^IOWZhbRs

Preço Futuro ^a2k6G0eY

O risco do hedging é a incerteza associada a b no tempo 2
também chamado de risco base ^CWcoPzRz

> ([[Options,Futures and Other Derivatives - Jonh C. Hull.pdf#page=77&annotation=6318R|Options,Futures and Other Derivatives - Jonh C. Hull, p.77]]) ^D4vOA0Tz

> Note that basis changes can lead to an improvement or a worsening of a hedger’s position ^AYBbofVf

Escolhas de Contrato: ^nS6jnSai

> If the asset being hedged exactly matches an asset underlying a futures contract, the first choice is generally fairly easy. In other circumstances, it is necessary to carry out a careful analysis to determine which of the available futures contracts has futures prices that are most closely correlated with the price of the asset being hedged. ^Cv8QdRnA

> ([[Options,Futures and Other Derivatives - Jonh C. Hull.pdf#page=78&annotation=6324R|Options,Futures and Other Derivatives - Jonh C. Hull, p.78]]) ^CMWQnFUN

Sobre o asset: ^hxmVtOfM

Sobre o mês de entrega: ^afkzdOsc

> ([[Options,Futures and Other Derivatives - Jonh C. Hull.pdf#page=78&annotation=6327R|Options,Futures and Other Derivatives - Jonh C. Hull, p.78]]) ^K2LoEu7D

> A good rule of thumb is therefore to choose a delivery month that is as close as possible to, but later than, the expiration of the hedge ^OsW8VTyA

Cross-Hedging: ^WPv6xbT3

Definição -> Ativo de Hedging diferente do Ativo do contrato futuro
Hedge Ratio ^a2IdDbf4

> ([[Options,Futures and Other Derivatives - Jonh C. Hull.pdf#page=79&annotation=6330R|Options,Futures and Other Derivatives - Jonh C. Hull, p.79]]) ^XyxjRcKA

> The  hedge ratio  is the ratio of the size of the position taken in futures contracts to the size of the exposure ^eVqSCpfM

Quando utilizando Cross-Hedging queremos escolher o 
hedge ratio que minimiza a variância do valor da posição
a qual foi feita o hedge ^Ez3Ugg4M

Desconsiderando ajuste diário e considerando a a relação entre a variação no spot price e o future price aproximadamente linear temos: ^PssHKVAl

Variação no preço Futuro ^M2s8IOfM

Variação no spot price ^HztGXjxB

Termo de Erro ^6H2l9ZB6

Definindo o Hedge Ratio com h, temos que a variação da posição por unidade de exposição é: ^fHbjO88E

> ([[Options,Futures and Other Derivatives - Jonh C. Hull.pdf#page=80&annotation=6336R|Options,Futures and Other Derivatives - Jonh C. Hull, p.80]]) ^P8TmzJ7j

Nosso objetivo agora é minimizar                               podemos derivar a posição e igualar a 0 para encontrar h* que minimiza a variância, já que a curva posição x h é sempre côncava para cima, pois para h > b ou h < b temos valores maiores que para h =b (Zera o 2° termo da eq. acima) ^mWf56pRR

Covariância: ^cPgERm60

*Covariância mede o grau de associação linear entre duas  váriaveis aleatórias: ^S2j6FzgW

Esperança: ^4U9gylpF

Equivalente proobabilístico da média e indica o valor médio  ou esperado de uma váriavel após muitas observações ^mRoeGWLt

Valores Discretos ^BOUD6x22

Função Densidade de Probabilidade de X ^uyseAMC1

Valores Contínuos ^Qoebx19M

Variância: ^laYT8xiU

*Caso específico de Covariância que entre a váriavel e si mesma ^R9OQb3Xs

> ([[Dennis D. Wackerly, William Mendenhall, Richard L. Scheaffer - Mathematical statistics with applications    -Thomson Brooks_Cole (2008).pdf#page=290&annotation=14772R|Dennis D. Wackerly, William Mendenhall, Richard L. Scheaffer - Mathematical statistics with applications    -Thomson Brooks_Cole (2008), p.265]]) ^MOWRKmIE

E(X) ^5yBEjnEn

E(Y) ^ToUPB9Hn

> ([[Dennis D. Wackerly, William Mendenhall, Richard L. Scheaffer - Mathematical statistics with applications    -Thomson Brooks_Cole (2008).pdf#page=116&annotation=14775R|Dennis D. Wackerly, William Mendenhall, Richard L. Scheaffer - Mathematical statistics with applications    -Thomson Brooks_Cole (2008), p.91]]) ^GnWCcFys

Correlação: ^sBgIPBOi

> ([[Dennis D. Wackerly, William Mendenhall, Richard L. Scheaffer - Mathematical statistics with applications    -Thomson Brooks_Cole (2008).pdf#page=290&annotation=14778R|Dennis D. Wackerly, William Mendenhall, Richard L. Scheaffer - Mathematical statistics with applications    -Thomson Brooks_Cole (2008), p.265]]) ^ZEuoKRaQ

*Coeficiente para normalizar a covariância ^1iBEGRiV

Variância de Soma/Subtração: ^NhPwcUFA

Igualando a 0 para achar h*: ^P8b6w3OI

> ([[Options,Futures and Other Derivatives - Jonh C. Hull.pdf#page=81&annotation=6342R|Options,Futures and Other Derivatives - Jonh C. Hull, p.81]]) ^yRanfqVC

The implicit assumption is that the future will in some sense be like the past. ^0Bj2WUHn

Número Ótimo de Contratos ^tu33lcKx

Tamanho da Posição hedgeada ^Hw9miSYk

Tamanho de 1 contrato futuro ^ZeW8SCwu

Impacto de Daily Settlement no Cross-Hedging: ^FV1wl3uy

Considerando a propriedade dos contratos futuros de diariamente afetar o balanço da conta de margem do trader
podemos adaptar a fórmula encontrada para um hedging de 1 dia ^TOlo0Xbz

*Entender melhor por que do termo adicional futuramente ^rsbJfHll

Indices de Ações: ^5myfvETl

Representam mudanças em um portfólio hipotético de ações ^nRH9hQuE

> ([[Options,Futures and Other Derivatives - Jonh C. Hull.pdf#page=85&annotation=6348R|Options,Futures and Other Derivatives - Jonh C. Hull, p.85]]) ^zEiT2ng5

> For example, contracts on the S&P 500 are closed out at the opening price of the S&P 500 index on the third Friday of the delivery month. ^ooi3hg4H

Em casos que o portfólio represente bem podemos aplicar diretamente o número
de contratos ótimo com h* = 1.0
Quando não aplicamos um modelo precificador de capital de ativos (CAPM) ^oPqSKHok

CAPM: ^Y6me3WT9

Modelo utilizado para relacionar o retorno esperado de um ativo e o risco do retorno
O risco no retorno de um ativo é divido em 2 riscos: Sistematico que está relacionado
do retorno do mercado como um todo e não pode ser diversificado; Não sistemático
que se refere ao ativo exclusivamente e pode ser diversificado. ^on4cncxo

> ([[(Wiley Finance Series)  - Risk Management and Financial Institutions-John Wiley & Sons, Inc. (2023).pdf#page=30&annotation=12124R|(Wiley Finance Series)  - Risk Management and Financial Institutions-John Wiley & Sons, Inc. (2023), p.2]]) ^QG2SCNU1

> Expected return is therefore a weighted average of the possible returns, where the weight applied to a particular return equals the probability of that return occurring. ^rOo3XrIf

Oportunidades de investimento ^SQROMaVt

Para comparar oportunidades de investimento podemos comparar o Retorno Esperado com o Risco relacionado a este Retorno ^ORz3MIUQ

Uma forma de mensurar risco 
é com o desvio padrão  ^Anu1UAcT

Retorno Esperado x Risco para diferentes ativos ^2jkggrRh

É natural pensar o que acontece com o retorno e o risco se combinarmos 
diferentes ativos formando assim um portfólio. Inicialmente para simplici-
dade analiseramos apenas 2 ativos ^mEG7xmKs

Alocação Percentual do ativo no Portfólio ^1h3r79l1

Retorno esperado do Ativo  ^uHyoB7j2

Risco como desvio padrão 
do retorno do portfolio ^KQEM0gmx

Retorno Esperado do Portfolio x Risco
Para diferentes possíveis alocações ^6hYeX85i

Fronteira de Eficiência ^Dho9izqa

Se quisermos adicionar mais e mais investimentos ao portfólio e testar diferentes combinações de alocação na busca de encontrar melhores pontos de 
Retorno Esperado x Risco, encontraremos a fronteira de eficiência onde o Retorno Esperado é Máximo para um determinado risco. Mas como é essa 
fronteira e como ela se comporta ao adicionarmos investimentos sem risco.
 ^8mUjMSyy

No gráfico à esquerda observamos
a fronteira de eficiência. Podemos
adicionar um ponto F que represen-
ta o investimento sem risco e a 
partir dele traçar uma reta que tan-
ge a fronteira de eficiência.
Agora temos uma nova fronteira
de eficiência que permite a adição
de investimento sem risco no port-
fólio, no qual     representa a alo-
cação no portfólio de risco (M) no 
ponto I. ^Mudrs4Wa

Nesse novo cenário fazemos a combinação dos retornos para termos o retorno no novo portfólio: ^n3X5JCso

E como temos risco apenas no portfólio de risco (M), o Risco do novo portfólio:  ^nL19skjC

Todos os pontos na linha FM são obtidos a partir das combinações de alocações entre o portfólio de risco e o investimento sem risco.
Esses pontos tem melhor risco-retorno o que leva FM a fazer parte da nova fronteira de eficiência.
 ^CTK3LWOW

Assumindo que conseguimos pegar emprestado na taxa sem risco, assim como investir nessa taxa, podemos criar investimentos que continuam a linha FM

 ^57KvJC1Z

> ([[(Wiley Finance Series)  - Risk Management and Financial Institutions-John Wiley & Sons, Inc. (2023).pdf#page=36&annotation=12127R|Risk Management and Financial Institutions (2023), p.8]]) ^Rnexfb0K

> It is a short step from here to argue that the portfolio of risky investments represented by  M  must be the portfolio of all risky investments. Suppose a particular investment is not in the portfolio. No investors would hold it and its price would have to go down so that its expected return increased and it became part of portfolio  M. In fact, we can go further than this. To ensure a balance between the supply and demand for each investment, the price of each risky investment must adjust so that the amount of that investment in portfolio  M  is proportional to the amount of that investment available in the economy. The investment represented by point  M  is therefore usually referred to as the  market portfolio ^lebM7LC4

O Modelo em Si: ^SVHsAjcO

Como decidir qual o retorno esperado para um investimento individual. Para tanto usaremos o conceito de portfólio de mercado e o que assumido sobre ele
Um procedimento comum é utilizar uma análise de rgressão para encontrar a melhor correção linear entre o retorno de um investimento e o retorno do port
fólio de mercado ^AguPrSiW

Erro não relacionado ao portfólio de mercado
Não Sistemático ^8T9hk2Qz

Erro relacionado ao  retorno do portfólio de
mercado, Sistemático ^KoD864pD

Taxa de investimento
livre de risco ^D7xoqWRr

Pois será o retorno caso
tudo seja investido no livre
de risco (B = 0) ^Kc4pvgy5

Exemplo de Aplicação: ^YDEupCQl

Suppose that the risk-free rate is 5% and the return on the market portfolio is 10%. An investment with a beta of 0 should have an expected return of 5%. This is because all of the risk in the investment can be diversified away. An investment with a beta of 0.5 should have an expected return of? ^y2QjDm7O

Suposições do Modelo ^1mNheIU0

> [!PDF|187, 97, 229] [[(Wiley Finance Series)  - Risk Management and Financial Institutions-John Wiley & Sons, Inc. (2023).pdf#page=38&annotation=12130R|(Wiley Finance Series)  - Risk Management and Financial Institutions-John Wiley & Sons, Inc. (2023), p.10]] ^qQvJTCHh

> > The idealized analysis we have presented leads to the surprising conclusion that all investors want to hold the same portfolios of assets (the portfolio represented by  M  in Figure 1.4). This is clearly not true. Indeed, if it were true, markets would not function at all well because investors would not want to trade with each other! ^grm8urDu

A Causa das análises não corresponderem a realidade do mercado são as suposições implicitamente feitas
que são:
1. Investidores se importam apenas com retorno e desvio padrão, se os retornos fossem normalmente distribuidos
   isso seria suficiente, contudo como não são, também sãoo levados em consideração assimetria e kurtosis da 
   distribuição.
2.Assumimos que epsilon para diferentes investimentos são independentes e que os retornos dos investimentos
   são correlacionados apenas por causa da sua correlação com o protfólio de mercado.
3.Assumimos retornos em cima de apenas 1 período e mesmo tamanho de período para todos investidores
4.Assumimos que podemos pegar emprestado e emprestar à mesma taxa livre de risco. O que é verossimil em mercados
  normais para grandes instituições, mas não para o pequeno investidor
5.Desconsideramos taxações, que podem afetar diferentemente, diferentes tipos de investimentos
6.Assumimos que todos os investidor fazem as mesmas estimativas de retorno esperado, desvio padrão e correlação
  entre os retornos dos possíveis investimentos. Isso significa que esperamos expectativas homogêneas.
Apesar das falhas o CAPM é uma ferramenta útil para encontrar Beta e para criação de benchmarks da performance do portfólio ^3E58cRXe

Criando um benchmark com CAPM: ^A0IuhLwi

Podemos traçar o retorno esperado do portfólio para diferentes  retornos de mercado, encontrando a correlação entre o reotrono 
esperado do portfólio e o retorno de mercado ^D8Q3Kk9B

Se o retorno real do portfóllio for maior que o retorno esperado do portfólio,
o manager de portfólio criou um retorno superior par a a quantidade de risco
sistemático tomado. Esse surplus é comumente chamado de alfa do portfólio.
Dentro das formar de produzir um alfa positivo estão:
1.Selecionar ações que dão outperform no mercado.
2.Tentando antecipar movimentações do mercado ^SfMEpZCk

> [!PDF|187, 97, 229] [[(Wiley Finance Series)  - Risk Management and Financial Institutions-John Wiley & Sons, Inc. (2023).pdf#page=41&annotation=12133R|(Wiley Finance Series)  - Risk Management and Financial Institutions-John Wiley & Sons, Inc. (2023), p.13]] ^ih97M8wK

> > Chapter 4 explains other strategies used by hedge funds to try to create positive alpha. ^7EJTw4sM

> ([[(Wiley Finance Series)  - Risk Management and Financial Institutions-John Wiley & Sons, Inc. (2023).pdf#page=41&annotation=12136R|(Wiley Finance Series)  - Risk Management and Financial Institutions-John Wiley & Sons, Inc. (2023), p.13]]) ^cegKQEks

> An investor can make a positive alpha only at the expense of other investors who are making a negative alpha. The weighted average alpha of all investors must be zero. ^1bRMxqf2

Juros Continuos ^doyeaIXV

Juros podem ser compostos com diferentes períodos de composição, a definição
de juros contínuos é quando período de composição tende ao infinito ^8ZjG2plb

Rever o passo a passo 
dessa eq. ^iDUTvjhz

Juros compostos (m = períodos de composição, n= anos,
                        R= taxa de juros, A = Valor aportado) ^6ty7N1KJ

Zero coupons se refere ao juros ganho quando não há pagamentos intermediários dentro de um investimento
sujeitos a juros contínuos em um determinado período de tempo
A maioria dos títulos financeiros não atuam como zero coupons já que distribuem coupons periodicamente. ^CXJwk3Bv

Precificação de titulos ^srpr2W5O

O preço teórico do titulo pode ser calculado com todas as entradas que o dono do titulo ira receber, cada uma com seu zero coupon rate.  ^2Iw1GFEe

Capítulo 4 -> Titulos (Ignorando por enquanto) ^MLEcmIJz

Short Selling ^rzuKgJyd

Vender um ativo que não se possui ^1fPb5ns4

> ([[Options,Futures and Other Derivatives - Jonh C. Hull.pdf#page=125&annotation=6372R|Options,Futures and Other Derivatives - Jonh C. Hull, p.125]]) ^Bvxw5Fga

> Suppose an investor instructs a broker to short 500 shares of company X. The broker will carry out the instructions by borrowing the shares from someone who owns them and selling them in the market in the usual way. At some later stage, the investor will close out the position by purchasing 500 shares of company X in the market. These shares are then used to replace the borrowed shares so that the short position is closed out. The investor takes a profit if the stock price has declined and a loss if it has risen. ^IE3Ijdrd

## Embedded Files
0b2c4c00be5cd4396b20aa8be1f3d654fee2fc9a: $$S_t - K$$

b9dd2f0a09f973be53e1b482f9307ef7e064e020: $$K-S_t$$

a63201a92c8c64342a366ff72782800c2a0c2b24: $$b_1 = S_1 - F_1 \space b_2 = S_2 - F_2
$$

0e24c215c443a9f580a9fe2059c3c0d2828e58b0: $$S_2 + F_1 - F_2 -> F_1 + b_2$$

a711bcc3ecd79633655e0fd4f5a313a6a6f4ae4f: $$\triangle S = a + b \triangle F + \epsilon$$

06aff03ef33c369ebac023f3886a661b2b91145d: $$\triangle S - h \triangle F = a + b \triangle F - h \triangle F + \epsilon \newline

$$

3410ce839015e3c250eecbd65e1f3231e8e6fd45: $$\triangle S - h \triangle F = a + (b- h) \triangle F + \epsilon$$

b5f7b157a2649f47dcf14dd8e704d4a25f90b630: $$E[ X] \ =\ \sum _{i} x_{i} \ P( X=x_{i})$$

119a0391e27da59efce3f3cd158ab533fd47c960: $$E[ X] \ =\ \int _{-\infty }^{+\infty } x\ f_{X}( x) dx
$$

9d16bc1cb40fbe65a23db31cd625b68585d5447d: $$E[(X-u_1)(Y-u_2)]$$

99a2f32339ecfdcfcc83b23c6ade5e52cab7e89c: $$Cov(X,Y) =$$

47c003aa33a4566c327475bd86f5ba3c4b70ffc0: $$Var(X) = E[(X-u)^2]$$

fdeaf2dd6d7f13b08b7f489b5e5ea1affc4c7974: $$p = \frac{Cov(X,Y)}{\sigma_1 \sigma_2}$$

d3dddc9d30f84feaccb77f844c0410b5a656d7a6: $$Var(\triangle S - h \triangle F)$$

e6c74c15734a4b179e52e26a239b27e944a8de83: $$Var(X) = E[(X-E[X])^2]$$

2e2c0c5209800c7a39e7e174207f0099aa420ccb: $$Var(Z) = E[(X+Y - E[X+Y])^2]$$

d98e98b437ec3d44d2b9d71114cba6e8bc52995e: $$E[(X+Y - (E[X] + E[Y))^2]$$

d608b0b1aa52b8208ebb2dec885ad21836ef5fde: $$E[((X-E[X]) + (Y-E[Y]))^2]$$

dd215461eed874df01f22d474b0539768700fc83: $$E[(X-E[X])^2 - 2*(X-E[X])*(Y-E[Y]) + (Y-E[Y])^2]$$

d90e335266d53cfd5cdf38348a1cd1a6788f6a98: $$E[(X-E[X])^2] - E[2*(X-E[X])*(Y-E[Y])]+ E[(Y-E[Y])^2]$$

ae18cae01f40335c2fc3d9ced2001e202c3d695a: $$Var(X) + Var(Y) - 2*Cov(X,Y)$$

152aaf002ee4a1b55b7236b267b423e2df6dd60d: $$\sigma _X ^2 + \sigma _Y ^2 - 2 * \sigma _X  * \sigma _Y * p$$

a3cddf28a70e1a8cb5d1bbcaaebd73330dc36581: $$Var(\triangle S - h \triangle F)$$

9cb5b625d5095f21a16c3b41aadef36d7795628c: $$= \sigma _S ^2 + h^2 * \sigma _F ^2 - 2 * \sigma _S * \sigma _F$$

d262c6f4d7d440e611ead602261009c7c374e1e8: $$\frac{\partial Var(\triangle S - h \triangle F)}{\partial h}$$

8928e3b2fbdc96f71e6d3978ac3b32d6afcabde9: $$h$$

ea650dbf734bb84076113cd078f431560e954ea3: $$* p$$

5e652946d7f5f3d050ac41e8e08aba23666053b3: $$= 2 * h * \sigma _F ^2 - 2 * \sigma _S * \sigma _F * p$$

2151f240356cd8c6341176f3638735a06929e420: $$h^* = \frac{2 * \sigma _S * \sigma _F * p}{2 *  \sigma _F ^2}$$

ef222dbd3cd0a66631fc904a8108252180463a0f: $$= p * \frac{\sigma _S}{\sigma _F}$$

f95e2efcbed13eaf1794b92b8ecec4e806d8fc49: $$\frac{\partial Var(\triangle S - h \triangle F)}{\partial h}$$

87d2b810dbdf3555acdc9e6f0a19d6ac213b210d: $$ = 0$$

a337044189dbd3c47c52c94da5537c02c49bb94e: $$N^* = \frac{h^* Q_A}{Q_F}$$

b87fec451587ece5e8a4b83c4a74abb27c730edd: $$= p * \frac{\sigma _S}{\sigma _F}$$

24eb9734413496c673d598cbf7fede5f4894d3b0: $$* \frac{S}{F}$$

5cd8291a3e8af0c0618a225c261138b4645e04d3: $$E[Retorno]$$

e6a5bf6d603a0280987e05c228cb85b34c2878df: $$Retorno \space Portfolio = w_1 u_1 + w_2 u_2$$

08d96391ffd65a5d43360d3a2ebfb848690ede35: $$Risco = \sqrt{w_1 ^2 \sigma_1 ^2 + w_2 ^2 \sigma_2 ^2 + 2*p*w_1*w_2*\sigma_1 *\sigma_2}$$

3ee84884aeec7e913067da6bb788dca19dfc878b: $$\beta _I$$

3379ebb70fe5c1e8cc6374f66fc3ac7998a2e850: $$E(R_I) = (1 - \beta _I)R _F + \beta _I E(R_M)$$

a0db1d147e9cfd84da4ba2fc2ba2d18ecb12c48d: $$\beta _I \sigma _M$$

61e568aadcede8328f21c67c44b8973d90ad0664: $$R = \alpha + \beta R_M + \epsilon$$

606e88ef0b16b822c99046b6a5bb312d9a972f7b: $$R = (\beta - 1)R_F + \beta R_M$$

8282dda39ce210ff12ce2daf571085ecfdd419a5: $$E[R] = R_F + \beta [E[R_M] - R _F]$$

efdf73573128bbed82cf013edfcc72cef5a971a3: $$R_F = 0.05, \space R_M = 0.10$$

3216a36bfb871ec1b9dbe5ad6f9b66bb9cdf8b3b: $$E[R] = 0.05 + 0.5 * (0.1 - 0.05) = 0.075$$

7b300b0b6bdcda3326351f2df3acbce5ca194d90: $$, \space \beta = 0.5$$

4ab84eed3e2b95f9c88f376ea0e7d15ac9402e7a: $$lim_{m->\infty}A(1+\frac{R}{m})^{mn}$$

453087ed2f24308af5ad108e58b580da354c3582: $$A*lim_{m -> \infty} (1 + \frac{R}{m})^{mn}$$

972428f24e3b3b38df5a5630fd4dd0933dc10c36: $$Resultado =$$

5776012e1796d2fdecb982b1d8ba7f0b7d1aa8ef: $$A*e^{nR}$$

a5647d4644b1c5b91ea4a803c40354b8517d1fe0: [[Captura de tela 2024-12-16 113404.png]]

8c98bb4f6017448a9841754d3efe76b89e4fbc50: [[Pasted Image 20241217114058_906.png]]

520127f0485087dd666e363e8b50dd84ca8c2252: [[Pasted Image 20241217231201_747.png]]

67adda087e6b9eb1eb692a5115e4f2158fa922fc: [[Pasted Image 20241217232133_572.png]]

d6f30b28031296bfa10acc3b737e9127eb504e9c: [[Pasted Image 20241217233938_960.png]]

73f4e79395abe2eeba4f22e07bd17498fd40df0b: [[Pasted Image 20241217234707_210.png]]

bb371d28b9d981decc09b70d3210a4fd51bd452e: [[Pasted Image 20241218090458_925.png]]

1eed2f430dbd056e5c292feae550a5c465633c1d: [[Pasted Image 20241218095303_455.png]]

%%
## Drawing
```compressed-json
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
```
%%