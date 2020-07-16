# Comece por aqui...
> "Mas qual linguagem devo usar? Qual sistema? Qual SO? Java? Python? C#? Hein?"
> -- O iniciante afobado

Vamos devagar, antes de pensar em qual linguagem você vai começar, qual sistema ou qualquer outra dessas dúvidas, precisamos entender o que é um programa e como podemos estrutura-lo.

> "Não adianta tentar te ensinar a falar inglês ou alemão se você não sabe o que quer falar"
> -- Programador sábio

Tenha em mente que seu computador apesar de ser uma ferramenta maravilhosa, capaz de executar milhões de instruções por segundo e poder fazer milhões de coisas, de alguma meneira ele precisa saber quais são as instruções que ele deve executar, certo? Nessa frase parece óbvio, mas é importante ter essa noção bem clara ao escrever qualquer tipo de programa, você precisa pensar em todo o contexto que seu programa vai encontrar e saber lidar com as situações que podem acontecer.

**Exemplo:**
Gosto de um exercício que me passaram quando comecei a estudar esse tipo de coisa em um curso técnico. Se imagine na seguinte situação: Você está em seu carro andando a 80 km/h e percebe que algo está errado e suspeita que um pneu furou, como seria o procedimento para resolver esse problema?

Você precisa se preocupar com uma série de situações que não são declaradas aqui. Inicialmente eu apenas disse que o carro estava em movimento em uma velocidade considerável, mas não sei onde o carro está, não sei em que faixa o carro está, nem se o pneu está mesmo furado ou se estiver, qual pneu está com problemas, então ao tentar resolver o problema você precisa estar atento a todos esses detalhes e o nível de detalhamento que você vai entrar aqui vai ditar o quanto seu programa será preparado para lidar com situações inesperadas, veja:

- Primeiro, verifique em qual faixa você está
	- Caso não esteja na faixa da direita, vá mudando de faixa até chegar a faixa mais a direita
- Existe acostamento? 
	- Caso exista, vá para o acostamento
  - Caso não exista, encontre um local seguro
- Desligue o carro
- Se estiver de cinto de segurança, retire-o (que coisa feia se não estiver! :| )
- Retire a chave do contato
- Verifique os 4 pneus e veja se há problemas
	- Se não houver problemas, volte para o carro e siga viagem
- Vá até o porta malas
- Abra usando a chave
- Pegue o macaco
- Pegue a chave de rodas
- Pegue o estepe
- Vá até o pneu furado
- Levante o carro
- Solte os parafusos da roda com problemas
- Retire os parafusos
- Retire a roda com problemas
- Coloque o estepe no lugar da roda com problemas
- Recoloque os parafusos
- Desça o carro
- Guarde a roda com problemas no lugar do estepe
- Guarde a chave de rodas
- Guarde o macado
- Feche o porta malas
- Feche o porta malas usando a chave
- Volte para a posição do motorista
- Coloque o sinto de segurança
- Dê partida no carro
- Entre na pista com cuidado
- Siga viagem

Já parou para pensar na quantidade de rotinas descritas aqui? Agora pense que você fez um script que é capaz de fazer isso tudo, mas você se esqueceu nesse script de por exemplo, de frear o carro ao chegar no acostamento, como você acha que seu programa vai se comportar? Se estamos falando de um computador, ele não sabe que precisa frear o carro e vai continuar andando... provavelmente na vida real vc terá problemas aqui.

Um programa se comporta exatamente assim. Você sempre precisa se preocupar com o "caminho feliz", que é quanto tudo está exatamente como você imaginou, mas também deve se preocupar com as situações adeversas e preparar seu programa para lidar com elas.

Você seria capaz de fazer esse exercício em formato de [fluxograma](https://pt.wikipedia.org/wiki/Fluxograma)? É um ótimo modo de começar a modelar as coisas.

## E como um progama se parece?
Uma das formas mais eficientes de entender como um programa funciona é usando uma linguagem didática chamada [portugol](https://pt.wikipedia.org/wiki/Portugol), que é muito parecido com uma linguagem chamada [Pascal](https://pt.wikipedia.org/wiki/Pascal_(linguagem_de_programa%C3%A7%C3%A3o)). Mas calma, comercialmente essa linguagem não é mais muito popular (apesar de ter sido muito há alguns anos atrás), mas ela é importante aqui para vermos alguns conceitos e esses são os mesmos na grande maioria das linguagens. Foquem na ideia! :)
