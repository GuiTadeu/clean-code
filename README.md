# Clean Code

Repositório criado para estudo dos princípios do Código Limpo com base no curso Clean Code: Writing Code for Humans da Pluralsight.

## Agenda
- [x] Intro
- [ ] Principles
- [ ] Naming
- [ ] Conditionals
- [ ] Functions
- [ ] Classes
- [ ] Comments
- [ ] Staying Clean

## Intro

### Por que escrever código limpo importa?

Código é como uma piada, se você tem que explicar é ruim.
Donald Knuth: Programação é a arte de dizer para outro humano o que o computador deve fazer.
Marin Fowler: Qualquer tolo escreve código que o computador entenda. Bons programadores escrevem código que outros programadores entendam.

1. Ler código é muito mais dificil que escrever
2. Código ruim gera débito técnico e isso afeta os projetos afastando os desenvolvedores
3. Cuidar do código agora faz com que seja mais fácil de lidar com ele no futuro.
4. Ser desleixado fará com que as entregas sejam mais demoradas no futuro
5. Você ganha valor como profissional

### Parabéns, você é um autor

Um autor que escreve um livro, artigo ou outro texto:
- Pratica a escrita como profissão
- Constrói documentações
- Criador de uma teoria ou plano

Cada linha do nosso código será lida por aproximadamente 10+ times...

Autores particionam seus livros em capitulos, Titulos, Paragrafos.
De forma semelhante particionamos em Namespaces, Classes e Métodos.

### Ler código em voz alta ajuda a expor os problemas

Verbalizar enquanto você lê o código ajuda a expor redundâncias e seções confusas.
Portanto, ajuda você a concentrar seus esforços em ser mais expressivo.

### Recursos

- Code Complete (Steve McConnell)
- Clean Code (Robert C. Marting)
- The Pragmatic Programmer (Andrew Hunt & David Thomas)

## Principles

1. A ferramenta certa
2. Remover ruídos
3. Auto-documentação

### Boundaries - Usando a ferramenta certa

Evite utilizar dois idiomas no mesmo arquivo como, por exemplo, Javascript em Strings Java.
Sempre que puder, mantenha-se nativo a ferramente que está utilizando, isso traz vantagens como:

- Código colorido
- Sintaxe verificada
- Separação de responsabilidades
- Reusabilidade

Lembre-se: Toda tecnologia é potencialmente um mal.

### Maximize o sinal sob o ruído

É como ouvir música. No código definimos sinal usando a regra de TED:

- Terse (conciso) - O código não deve ser excessivamente prolixo
- Expressive - É claro o que o código está fazendo
- Does one thing - Deve ter uma responsabilidade clara e fazer isso bem.

Ruídos são como:

- Complexidade ciclomática
- Indentação excessiva
- Classes enormes
- Comentários desnecessários
- Sem espaços
- Métodos longos
- Repetição
- Nomes ruins
- Verbosidade excessiva
- Código zumbi (?)
- Etc...

### Por que é importante reduzir o ruído?

Quando lemos código, nosso cérebro é o compilador.
Um estudo determinou que seres humanos podem armazenar cerca de 7 itens na memória de curto prazo ao mesmo tempo. Isso afeta no nosso código:

1. Número de parâmetros por método
2. Número de métodos numa classe
3. Número de váriaveis num escopo

Outro motivo, o sinal decai naturalmente com o tempo enquanto o ruído cresce naturalmente como o tempo. Por isso devemos refatorar constantemente para evitar criar uma grande bagunça que precisa ser substituída em vez de mantida.

