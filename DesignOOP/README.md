# Esse repositório descreve 3 técnicas dentro de POO

# Herança

Herança é quando uma classe puxa características de outra. A grande vantagem dela é que evita repetição de código, já que a classe filha aproveita atributos e métodos da classe pai. Isso também ajuda a organizar melhor, pois cria uma hierarquia clara. Além disso, é bem mais simples de entender.

Mas herança tem seus problemas. Quando usada em excesso, deixa o código engessado e difícil de mudar. Nem sempre faz sentido a relação de “pai e filho”, e isso pode causar confusão. Outro ponto é que as classes ficam muito presas umas às outras, o que limita a flexibilidade se comparado com Composição.  

---

# Composição / Associação

Na composição e associação, uma classe usa outra em vez de herdar. Isso dá mais flexibilidade que a herança e se parece mais com a vida real, como um carro que tem um motor. Essa abordagem evita dependências tão fortes entre classes.  

O ponto negativo é que pode gerar mais código e, às vezes, **confundir a responsabilidade de cada classe**. Mesmo assim, quando bem usada, a composição leva vantagem sobre a herança por permitir trocar partes do sistema sem quebrar tudo.  


---

# Injeção de Dependência

A injeção de dependência vai um passo além da composição. Em vez de uma classe criar os objetos de que precisa, ela recebe esses objetos prontos, normalmente de fora. Isso deixa o código muito mais solto, com menos acoplamento do que composição e herança. A grande vantagem é que facilita bastante a manutenção e os testes, já que você pode trocar facilmente uma dependência real por uma falsa. Em projetos grandes, é muito mais poderosa do que apenas herança ou composição.  

O lado negativo é que, pode ser meio confuso. Além disso, normalmente depende de ferramentas extras, como o Spring, e isso adiciona uma certa complexidade ao projeto. Por isso, em sistemas pequenos ou simples, pode ser um exagero, sendo mais prático ficar só com herança ou composição.  

---

