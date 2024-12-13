Data: 2024-10-29  
Status: #fim
Tags: [[Matemática]], [[Computação]], [[Aprendizado de Máquina]], [[Redes Neurais]], [[Medium]], [[Cálculo]], [[Álgebra Linear]],[[Sergios Theodoridis, Konstantinos Koutroumbas - Pattern Recognition, Fourth Edition-Academic Press (2008).pdf]]



Após escrever meu [artigo na medium sobre o Perceptron](https://medium.com/@joaopedrobrasil/pattern-recognition-part-1-perceptron-7d332c0a4bdc) percebi que não possuía profundo entendimento de como a atualização de pesos funciona, essa nota serve para deixar registrado o meu entendimento de como isso funciona.
O problema a ser solucionado em questão é que precisamos de uma maneira de reduzir uma função de custo, que calcula o erro das previsões do nosso classificador linear(Basicamente um vetor). Portanto uma solução viável é verificar como nossa função de custo varia de acordo com uma variação no nosso vetor ou seja  $$ 
\frac{J(w)}{w}
$$
Onde J é nossa função de custo e w é o nosso vetor, para realizarmos essa divisão precisaríamos escolher um intervalo e teríamos como retorno um número que se positivo indicaria que a função de custo está aumentando naquele intervalo de w e se positivo estaria diminuindo.
Quando aplicamos a derivada parcial
$$
\frac{\partial J(w)}{\partial w}
$$
o que estamos fazendo é verificar em para um ponto especifico como uma pequena variação em w afeta J, portanto para finalizar precisamos atualizar nossos pesos a cada iteração de forma que eles reduzam a função de custo de forma que, se a derivada parcial for positiva precisamos diminuir o valor de w e se for negativa precisamos aumentar o valor de w, logo:
$$
w_{novo}=w_{antigo} - \alpha \times \frac{\partial J(w)}{\partial w}
$$
Adicionamos um parâmetro alpha com o intuito de controlar o quanto iremos aumentar ou diminuir nossos pesos e com isso 




### Referências
[[Sergios Theodoridis, Konstantinos Koutroumbas - Pattern Recognition, Fourth Edition-Academic Press (2008).pdf]]
https://medium.com/@joaopedrobrasil/pattern-recognition-part-1-perceptron-7d332c0a4bdc

