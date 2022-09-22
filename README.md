# -embedded.ai

# Um Resumo sobre o  artigo TinyMLOps: Operational Challenges for Widespread Edge AI Adoption 

O artigo TinyMLOps: Operational Challenges for Widespread Edge AI Adoption tem como intuito mostrar os desafios que o profissional que pretende desenvolver aplicações para embarcados terá que enfrentar. Além de mostrar essas dificuldades, também é falado sobre algumas das  suas vantagens e as diferenças existentes entre aplicações que são desenvolvidas para embarcados e aquelas que são desenvolvidas utilizando uma infraestrutura de nuvem. O artigo é dividido em algumas partes, inicialmente é mostrado de forma mais superficial as vantagens e os desafios que se tem quando trabalhamos com TinyML e posterior a isso é feito uma divisão em tópicos importantes para um modelo e é debatido alguns pontos sobre eles.
  
Iniciando com a parte que dá uma  visão mais superficial, é relatado que se comparado com os modelos que utilizam uma infraestrutura de nuvem, os modelos de embarcados tem como vantagem a diminuição da latência, escalabilidade e um aumento na privacidade.  No entanto, além dessas vantagens acabam surgindo alguns obstáculos, como por exemplo, a limitação do processamento e o consumo de energia, uma vez em que, parte desses dispositivos utilizam bateria. 

	Já na parte que relata o desafio do TinyMLOps, o primeiro assunto abordado é referente ao gerenciamento de versões do modelo. Para um modelo que utiliza uma infraestrutura de nuvem é relativamente simples realizar isso, uma vez em que, um único modelo será distribuído para todos os usuários. Já para um modelo embarcado, não é tão simples, pois o modelo será distribuído para diversos aparelhos com performances diferentes e em situações diferentes, com isso, terá que ser distribuído modelos menores ou modelos mais completos dependendo de cada situação.

	O Segundo desafio relatado fala a respeito da observabilidade dos modelos, ou seja, realizar o monitoramento de um determinado modelo para saber se os resultados obtidos e seu desempenho estão conforme foi planejado. Para o caso onde é utilizado uma infraestrutura em nuvem é relativamente simples pois todos os dados são centralizados. Já no caso de modelos embarcados é um pouco mais complicado pois é uma estrutura descentralizada e parte dos dispositivos funcionam sem a utilização de internet. Além disso, enviar dados desses dispositivos irá  infligir  um dos pontos positivos dos embarcados que é a privacidade. Uma possível solução apresentada no artigo para isso, é realizar os cálculos de algumas estatísticas no próprio dispositivo e posteriormente enviar essas informações.  



	O outro desafio é referente ao modelo de negócio.  Para o modelo que utiliza uma infraestrutura de nuvem é relativamente simples realizar essas cobranças, podendo cobrar um determinado valor por quantidade de requisições ou por dias de uso . Já para os embarcados, onde, será  executado nos mais diversos hardwares e  muitas vezes os dispositivos estarão offline se torna mais difícil aplicar esses tipos de cobrança. 


	Outro ponto abordado é referente a realização de aprimoramentos nos  modelos. Na infraestrutura em nuvem onde todos os usuários utilizam um mesmo modelo, é mais fácil realizar a coleta de dados para realizar os novos treinamentos. Já para os embarcados não é tão simples, principalmente por causa das variedades de modelos existentes, no entanto, já existem algumas possíveis soluções para esse problema. Dentre elas se encontra o “Federated Learning” 
	

