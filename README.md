## O que são os algoritimos geneticos?

Os algoritimos geneticos são uma forma de aprendizado de maquina em que se usa da seleção natural para construir uma população que consiga resolver o problema


## Gerando o desafio

No programa desse repositorio temos um simples problema de descobrir qual o padrao certo que seja semelhante ao da matrix definida no comeco podemos observar a matrix no trecho de codigo abaixo 

https://github.com/brunoartc/genetic_algo_mileage/blob/27f00a6b9671ba3403030e2b7a462dc45ac19603/genetic.py#L4-L53

## Gerando os competidores

Com o nosso desafio em mãos, ou seja, a matrix que deve ser copiada, geramos nossas primeiras populações que foi fixada em apenas 50 

https://github.com/brunoartc/genetic_algo_mileage/blob/27f00a6b9671ba3403030e2b7a462dc45ac19603/genetic.py#L145

https://github.com/brunoartc/genetic_algo_mileage/blob/27f00a6b9671ba3403030e2b7a462dc45ac19603/genetic.py#L81-L87

com os competidores gerados conseguimos então fazer as geracoes passarem e então treinar nossos competidores 

https://github.com/brunoartc/genetic_algo_mileage/blob/27f00a6b9671ba3403030e2b7a462dc45ac19603/genetic.py#L147-L156

cada geração era constituida de algumas etapas


## Teste dos individuos

Para ver quem mais se aproximou do padrão testes eram feitos, que consistiam apenas em uma subtração de matrizes

https://github.com/brunoartc/genetic_algo_mileage/blob/27f00a6b9671ba3403030e2b7a462dc45ac19603/genetic.py#L97-L109

e era feito um ranking com esses scores

https://github.com/brunoartc/genetic_algo_mileage/blob/27f00a6b9671ba3403030e2b7a462dc45ac19603/genetic.py#L114-L119

depois da classificação dos individuos os 25 individuos mais fortes levavam seus 'genes' para frente

## Reprodução 

os individuos que ficaram no top 25 tinham seus genes aleatoriamente selecionados para gerarem 12 novos individuos
enquanto os outros eram apenas re-gerados

https://github.com/brunoartc/genetic_algo_mileage/blob/27f00a6b9671ba3403030e2b7a462dc45ac19603/genetic.py#L121-L139






