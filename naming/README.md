# Naming

Lembre-se sempre que "entender a intenção do programador é o maior dos problemas", por isso é importante usar nomes descritivos. Usar nomes comm abreviações pode tornar as coisas confusas, algo como:

P estava com muita raiva do G por insultar sua M. G chutou P no A. Ele caiu no C.

Ler o texto acima é cansativo e adiciona confusão desnecessária.

## Naming Classes

Escolher bons nomes de classes é importante para evitar que desenvolvedores suponham a responsabilidade de uma classe e coloque código que não deveria estar lá.

Uma classe bem projetada deve ter uma responsabilidade. E seu nome deve refletir isso. 

Definir o que é responsabilidade é dificil, mas você também pode se perguntar: Essas classe está fazendo muitas coisas?

### Class Naming Guideline

- Substantivos ao invés de verbos pois quando você cria uma classe está criando algo. Você deve ser capaz de imaginar essa coisa.
- Deve ser o mais específico possível pois isso leva a classes menores e mais coesas.
- Deve ter somente uma responsabilidade e o nome deve definir bem isso.
- Evite sufixos genericos que não agregam valor. Tente sempre imaginar a instância da classe, ela precisa ser lógica (ex: Product ao invés de ProductInfo ou ProductManager)

Definição de coesão do autor: Uma classe coesa tem métodos que interagem regularmente uns com os outros.

### Naming Methods

Os nomes dos métodos devem ser descritivos o sufiente para que não precisemos abri-lo para saber o que ele faz.

### Rubber Ducking

- Verbalizar ajuda sua criatividade
- Quando estiver travado, verbalize!
- Sobre nomeações, pergunte a si mesmo, estou descrevendo uma coisa? (ou muitas coisas?)

### Avoid Side Effects

Um método que tem o nome "CheckPassword" não deve salvar um usuário.
Garanta que os nomes dos seus métodos são com compreensíveis e contam a verdade.

### Naming Warning Signs

Se você usa And, If ou Or no nome de um método, talvez deva dividi-lo em 2.

### Avoid abbreviations

- Não padroniza
- Falamos sobre código, precisamos de nomes fáceis de falar

### Naming Variables: Boolean

Use is junto de algum substantivo/verbo.

### Naming Variables: Be Symmetrical

Exemplos: on/off, fast/slow, lock/unlock, min/max, etc...

### Summary

- O nome deve dizer algo
- Use nomes especificos
- Procure por efeitos colaterais
- Reduza abreviações
- Booleans devem soar como true/false
- Busque por simetria
- Verbalize quando travar em algo