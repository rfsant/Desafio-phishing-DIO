# Desafio-phishing-DIO
Criação de um phishing para capturar a senha do Facebook, clonando o site usando o setoolkit. Desafio proposto pelo bootcamp DIO.

# Ferramentas
- Kali
- Setoolkit

# Realizando o  ataque
- No Kali abra o terminal;
- Acesse o modo root com o comando ``` sudo su ```;
- Dentro do root insira o comando ``` setoolkit ``` para iniciar a ferramenta;

![Alt text](./passo1.jpg "Optional title")

- Com a ferramenta aberta vai  ter o menu de ações, com os tipos de ataques da ferramenta e para esse ataque usaremos a opção 1 ``` Social-Engineering Attacks ```;

![Alt text](./passo2.png "Optional title")

- Após escolher o tipo de ataque será exibido um menu com os vetores de ataque, agora selecionamos a opção 2 para vetor de ataque o ``` Web Site Attack Vectors ```;

![Alt text](./passo3.png "Optional title")

- As próximas telas apresentam uma breve descrição das ações de cada ataque que faz parte do vetor de ataque e do método de ataque escolhidos, seguido pelo menu com esses tipos de ataques ataques.
- No primeiro menu com os métodos de ataque selecionamos a opção 3 ``` Credential Harvester Attack Method ```;

![Alt text](./passo4.png "Optional title")

- No segundo menu com os métodos de ataque selecionamos a opção 2 ``` Site Cloner ```;

![Alt text](./passo5.png "Optional title")

- Após concluir a última etapa aparecerá uma mensagem importante informando que é necessário utilizar um ip externo para que tenha a comunicação com o browser, então após informar o ip prossiga com enter;
- Em seguida será solicitada a url do site que desejamos clonar, nesse caso o facebook;

![Alt text](./passo6.png "Optional title")

- Para testar o site falso basta pesquisar o ip que foi usado para hospedar o site falso e para sofisticar o ataque basta definir um nome para esse ip para disfarçar a origem na hora de aplicar o ataque;
- Para conferir os dados obtidos basta observar essa parte do resultado;

![Alt text](./passo7.png "Optional title")
