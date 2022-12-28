# Markdown simples
---
## Itálico
Para colocar uma palavra em *itálico*, podemos colocá-la entre asteriscos simples ou entre underlines simples.

Ex:
\_CursoemVideo_
\*CursoemVideo*

Resultado: 
_CursoemVideo_
*CursoemVideo*

## Negrito
Para usar o __negrito__, basta colocar asteriscos duplos ou underlines duplos para delimitar o termo.

Ex:
\__CursoemVideo__
\**CursoemVideo**

Resultado:
__CursoemVideo__
**CursoemVideo**

## Riscado (strike)
Para riscar um texto, coloque-o entre dois símbolos de til.

Ex:
\~~CursoemVideo~~

Resultado:
~~CursoemVideo~~

## Dá pra misturar?
É possível também juntar as formatações de forma hierárquica, como por exemplo:

Ex:
\__*CursoemVideo*__

Resultado:
__*CursoemVideo*__

# Listas
---
## Listas numeradas
Pra criar uma **lista numerada**, comece a linha com um **número qualquer**, seguido de um **ponto**. O primeiro número da lista vai indicar onde ela começa os itens seguintes, se estiverem em linhas consecuticvas, vão continuar a sequência.

Ex:<br>
1\. Brasil<br>
0\. Bélgica<br>
9\. Argentina<br>
3\. Peru

Resultado:
1. Brasil
0. Bélgica
9. Argentina
3. Peru

## Listas com marcadores
Basta usar um asterisco seguido de um espaço ou um traço seguido de espaço no início de uma linha para que ele seja parte de uma lista demarcada.

Ex:<br>
\* Opção 1<br>
\* Opção 2<br>
\* Opção 3<br>
\* Opção 4

Resultado:
* Opção 1
* Opção 2
* Opção 3
* Opção 4

## Lista de tarefas
Colocando um sinal \- \[ ] ou \- \[x] antes de cada item, criamos listas de tarefa com itens marcados ou desmarcados.

Ex:<br>
\- \[ ] pão<br>
\- \[x] leite<br>
\- \[ ] manteiga

Resultado:
- [ ] pão
- [x] leite
- [ ] manteiga

# Títulos e linhas horizontais
---
Para criar títulos, podemos usar de uma \# até seis \###### para definir o nível do título para que o conteúdo fique organizado corretamente.

Para criar linhas horizontais, podemos usar três traços \--- ou três asteriscos ***

# Teste 1
---
## Teste 2
---
### Teste 3
---

# Imagens
---
Para inserir uma imagem, vamos usar o símbolo ![ ]( ) onde a descrição fica entre colchetes e o endereço da imagem entre parênteses.

Ex:

\!\[Logo Python]\(https://cdn.iconscout.com/icon/free/png-256/python-3629591-3032289.png)

Resultado:
![Logo Python](https://cdn.iconscout.com/icon/free/png-256/python-3629591-3032289.png)

# Links
---
Para inserir links, a simbologia é semelhante à usada com as imagens, apenas removemos o sinal de exclamação.

Ex:
\[Meu GitHub]\(https://github.com/alejandroalosilla)

Resultado:
[Meu GitHub](https://github.com/alejandroalosilla)

# Trechos de código
---
Como o __GitHub__ é um rede social para programadores, nada mais interessante do que aprendermos a demarcar nossos códigos e comandos. Podemos usar dois tipos de marcação:

## Comando isolado
Se for citar um comando apenas, basta colocá-lo entre crases.

Ex:
Gostaria de maiores informações sobre o comando \`window.document.querySelector()` da linguagem JavaScript.

Resultado:
Gostaria de maiores informações sobre o comando `window.document.querySelector()` da linguagem JavaScript.

## Trecho de código
Para compartilhar um código com mais linhas, basta colocar todas elas dentro de um grupo delimitado entre três crases consecutivas (sem espaço entre elas).

Ex:
Olha só o programa que criei em __Python__:

```
num = int(input('Digite um número: ')) 
if num % 2 == 0: 
 print(f'O valor {num} é PAR') 
else: 
 print(f'O valor {num} é ÍMPAR') 
print('Fim do Programa')
```

# Ligações entre conteúdos
---
Quando criamos conteúdos em markdown para o GitHub, podemos relacionar conteúdos com outros ou com pessoas usando essas marcas.

## Citação
Ao responder alguém, podemos realizar citações a outras mensagens completas ou a trechos dela, usando sinais de > no início da linha.

Ex:<br>
Como **Steve Jobs** disse uma vez:<br>
\> Decidir o que não fazer é tão<br>
\> importante quanto decidir<br>
\> o que fazer<br>

Resultado:
> Decidir o que não fazer é tão<br>
> importante quanto decidir<br>
> o que fazer

Bela frase!

## Menções a Usuários
Se você precisar mencionar algum usuário, pode indicar o nome do perfil logo após o símbolo de @.

Ex:
Durante o curso, usamos o perfil @gafanhotos para exercitar as ações em Git e GitHub
Se o perfil realmente existir, podemos clicar sobre o nome para ter acesso à página principal do usuário.

## Menções a Issues
Também podemos mencionar *Issues* e *Pull Requests* de nosso repositório usando o símbolo de # seguido do número do elemento (sem espaços).

Ex:
Analisando a Issue #3, vamos rever o que foi indicado pelo usuário.

# Símbolos
---
## Escapando símbolos
Até o momento, vimos que temos vários símbolos que servem para criar formatações. Mas e se por acaso quisermos mostrar exatamente o símbolo sem seu efeito de formatação? A resposta é simples: usamos barra invertida \ antes do símbolo para eliminar o efeito de formatação.

Ex:<br>
Podemos criar títulos usando \\## antes do texto<br>
Podemos criar citações usando \\> antes do conteúdo<br>
Podemos adicionar imagens usando \\!\\[descrição]\\(endereço)

Resultado:<br>
Podemos criar títulos usando \## antes do texto<br>
Podemos criar citações usando \> antes do conteúdo<br>
Podemos adicionar imagens usando \!\[descrição]\(endereço)

## Emojis
Existem códigos especiais para emojis em markdown, que devem ser representados entre símbolos ::

Ex:<br>
Boas iniciativas merecem aplausos : clap :<br>
Fatos importantes merecem atenção : eyes :<br>
Momentos difíceis requerem força : muscle :<br>
Mensagens bem escritas merecem um like : +1 :

Resultado:<br>
Boas iniciativas merecem aplausos :clap:<br>
Fatos importantes merecem atenção :eyes:<br>
Momentos difíceis requerem força :muscle:<br>
Mensagens bem escritas merecem um like :+1:

# Tabelas
---
Criar tabelas em markdown é extremamente simples. Basta usar as barras em pé(pipes) | e as barras deitadas(traços) - de forma organizada.

Ex:<br>
Ano \| Curso \| Professor \| Aulas<br>
\:---: \| ---: \| :--- \| :---:<br>
2013 \| HTML+CSS+JS | Gustavo Guanabara | 36<br>
2018 \| Hardware | Alfredo Jr | 28<br>
2019 \| Python | Alejandro Alosilla | 15

Resultado:
Ano | Curso | Professor | Aulas
:---: | ---: | :--- | :---:
2013 | HTML+CSS+JS | Gustavo Guanabara | 36
2018 | Hardware | Alfredo Jr | 28
2019 | Python | Alejandro Alosilla | 15
