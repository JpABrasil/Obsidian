Data: 2024-10-30  
Status:  #meio
Tags:[[Finanças]],[[Criptomoedas]],[[Computação]],[[Criptografia]],[[Datathon FGV 2024]]

### Registros e Assinaturas Digitais:

Inicialmente um registro público e editável por todos os usuários guarda as transações feitas, todos podem acessar e acrescentar novas transações. Isso gera um problema, pois alguém poderia adicionar transações que não aconteceram, para resolver isso precisamos criar assinaturas digitais que marcarão cada usuário e estas devem ser impossíveis de copiar.
Para tanto usamos um conceito de criptografia de **chave pública** e **chave secreta**, sendo cada uma delas uma sequência binária e a assinatura um número de 256 bits (Grande para dificultar a quebra da criptografia) muda de acordo com a mensagem que está se querendo assinar, logo podemos descrever uma função:
$$
f(Mensagem,Chave \space pública) = Assinatura
$$
Também precisamos de uma função para verificar se a assinatura é válida:
$$
f(Mensagem,Assin atura,Chave \space Privada) = V \space ou \space F
$$
Contudo ainda temos um problema, alguém poderia copiar várias vezes uma transação utilizando a mesma assinatura, para evitar isso associamos um id único a cada transação o que fará cada cópia precisar de uma nova assinatura.

### O Registro é a Moeda:
Mesmo conseguindo que cada transação registrada seja  válida, ainda precisamos contar que todos paguem o que devem a cada um ao final do determinado período. Considerando isso adotamos uma medida de cada um depositar uma determinada quantia e as transações que excedem essa quantia serão invalidadas, isso implica que para invalidar uma transação  precisamos de todo o histórico de todas as transações até aquele ponto
Nesse ponto se todas as pessoas usassem esse sistema não seria mais necessário converter o dinheiro colocado de volta para dinheiro físico já que todas as trocas poderiam ser registradas nele. **Portanto a moeda em si é o _REGISTRO_**.  

### Descentralização
Uma pergunta que fica é onde ficará esse esse registro? Para evitar a desconfiança em um órgão centralizado, cada um dos usuários mantém uma cópia do registro e quando alguém quiser fazer uma transação ela transmite esse sinal e cada um dos outros usuários guarda em seus respectivos registros.
Mas como vamos garantir que todos receberam, acreditaram nessa transação, e as gravaram na mesma ordem. Esse problema é abordado em [[bitcoin.pdf]] e em alto nível a solução descrita é confiar no registro com mais **_trabalho computacional_** utilizado, isso faz com que registros conflitantes e transações fraudulentas requeiram uma quantidade extraordinária de computação

### Funções de Criptografia Hash
Uma função hash é um algoritimo matemático que recebe um dado de tamanho arbitrário e o mapeia em um texto encriptado. ([[Cryptographic Hash Functions.pdf#page=2&annotation=357R|Cryptographic Hash Functions, p.2]])
$$
 H : D\to R,onde \space D = \{0,1\}^*\space e\space R= \{0,1\}^n, n \geq 1\newline 
$$Então h sendo o output da função e m sendo nossa mensagem, podemos dizer que h = H(m).



### Referências
https://www.youtube.com/watch?v=bBC-nXj3Ng4
https://www.youtube.com/watch?v=S9JGmA5_unY
[[bitcoin.pdf]]




