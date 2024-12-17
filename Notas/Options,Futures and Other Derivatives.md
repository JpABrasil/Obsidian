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

a5647d4644b1c5b91ea4a803c40354b8517d1fe0: [[Captura de tela 2024-12-16 113404.png]]

8c98bb4f6017448a9841754d3efe76b89e4fbc50: [[Pasted Image 20241217114058_906.png]]

%%
## Drawing
```compressed-json
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

QoDNRocNvfVZXRfgATVDN6p0DAAEdc+QIAA=
```
%%