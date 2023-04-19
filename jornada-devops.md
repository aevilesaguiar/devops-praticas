# Resumo da Jornada Devops

Devops surgiu da comunidade em 2018 e 2018 - desenvovimento e operações. Devops é uma jornada, descoberta da comunidade.

Devops trás o conceito de colaboração, não existe devops sem colaboração.

![image](https://user-images.githubusercontent.com/52088444/233214751-9fffc79a-d60a-4afa-8227-ab3558d2c567.png)

A devops tem a questão de ferramentas, mas deve ter a cultura colaborativa, facilitação, transparencia, confiança isso é o que faz a diferença. 

Essa cultura devops vem do lean, do scrum do xp, dos métodos ágeis em geral. Para implantar Devops é necessário ter uma empresa colaborativa

Quando se fala em Devops se foca muito em equipes de desenvolvimento e operações, elas possuem conflitos de interesses, e o devops veio com o intuito de unificar essas equipes, e para isso funcionar é necessário mobilizar as equipes a colaboração.

A base do devops é a integração contínua, entrega contínua e implantação contínua.

- A integração contíinua é importante por que cada vez mais temos equipes descentralizadas, ou seja um sistema não é feito/mantido/codificado apenas por uma pessoa/equipe , mais por muitas pessoas/equipes, a ideia da integração continua é fazer o merge do código com  5 10 pessoas diariamente, por que quanto mais tempo demorar para fazer integração mais chance de falha haverá na implantação. 

- Entrega contínua: a questão da entrega continua é fazer a integração de maneira contínua automatizada não só no ambiente de desenvolvimento, mas em todos os ambientes, é você deixar o código pronto para ser implantado em produção bastanto apertar um botão.

- Implantação continua: desde o desenvolvimento. Tá bom, funcionou,o pipeline segue até a implantação em produção.

Para ter devops é preciso investir em integração continua no mínimo.
![image](https://user-images.githubusercontent.com/52088444/233221546-39de72cb-2ee2-4b53-96cf-be626ae42177.png)

- Infraestrutura que está ligado com desenvolvimento, mas por exemplo, aqui a questão de microserviço que também é um assunto antigo mas, ultimamente as empresas têm investido bastante, porque com microserviço você viabiliza a implantação diária vários implantações diárias. Então a ideia do microserviço é que ao vez de ter um sistema totalmente monolítico, em que uma implantação você tem que parar o sistema todo, e pode impactar o sistema todo. Na questão de microsserviço você pode usar muito container, nuvem, você pode quebrar o seu sistema em 100 transações e camadas de serviços que são independentes um do outro

Então com isso você tem 100 microsserviços numa aplicação mais completa, ou seja o serviço numero 100, não impacta os 99, você implanta você consegue ter implantações de baixo e de baixo risco. releases de baixo risco, E a questão de API que você consegue reaproveitar serviços que também é importante para devops

Esse conceito já existe a muito tempo, é que devops converge uma série de tecnologias, iniciativas e outras técnicas para você conseguir fazer uma implantação de uma maneira mais rápida, com mais disponibilidade e segurança.
Outra coisa importante é a estrutura como código, e ela começou praticamente com devops, é você ter condições de usar as mesmas técnicas de programação de desenvolvimento  para infraestrutura, para minimizar ações manuais. A nuvem como temos hoje para utilizar, a questão de container, microsserviço na prática.
Ou seja ao invés de você criar servidores na mão, você coloca no controle de versão também a criação de servidores, então ao invés de ficar consertando servidor, você mata e recria do zero, minimiza também a questão do desenvolvedor ficar pedindo para a infraestrutura criar máquinas, vai ter um script que vai criar máquina de maneira automática, que o próprio desenvovledor inicia, não precisa pedir para a infra para criar na mão, chance de erro é menor e otimiza o fluxo de valor de ponta a ponta.

- Injeção de falhas: existe um case de mercado do netflix que eles chamam de macacos do caos, ele criou software , scripts, serviços que injetam falhas nos próprios serviços da netflix par testar a sua resiliência. As empresas mais maduras injetam falhas em seus próprios sistemas, para se recuperar mais rápido, se aumentar a resiliência das empresas. Para isso acontecer a empresa precisa ter uma cultura de aprendizado, a ideia é aprender com as falhas.

- pipeline de implantação automatizado:ou seja que você tenha desde o desenvolvimento, homologação antes o teste, produção ou pré produção, esses ambientes que você tenha de ponta a ponta uma visão clara que tragam feedback de imediato para quem está colocando o código. Exemplo: estão desenvolvendo meu código eu faço o teste unitário e já estou vendo na hora se já deu certo.Ou seja eu vejo os erros no ambiente de teste, não preciso ver em produção. é muito importante para o devops a questão Pipeline e automação de testes.E aí essa questão do TDD que é o desenvolvimento baseado em teste ou o Desenvolvimento Guiado por testes, Ou seja eu já criei o teste antes de criar o código.Então o meu código vai ser feito para passar no teste. A ideia do teste para devops e para o lean é que seja descoberta na hora e não lá na frente, ou seja que eu tenha qualidade na fonte.

- Revisão do Código se associa a questão do teste, a revisão do código pode ser com programação em par ou pode ser pedindo ao colega para fazer uma revisão 























