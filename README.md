# Exercícios de POO

7 exercícios para treinar programação orientada a objetos.

Exercício 1

Seguindo o diagrama UML a seguir, implemente a classe Veiculo e seus
métodos. Após a implementação, testar cada um dos métodos via console.
 - acelerar(): este método acrescenta um valor de +20 no atributo velocidade.
 - abastecer(int combustivel): recebe como parâmetro uma quantidade de combustível e atribui a listrosCombustivel. 
 OBS: O limite do tanque de combustível é de 60 litros, validar para não ultrapassar.
 - frear(): a cada chamada do método diminui a velocidade em 20. Não aceitar a chamada do método se o veiculo estiver parado.
 - pintar(String cor): recebe uma cor como parâmetro e altera o atributo.
 - ligar(): Verifica se o veículo já se encontra ligado, caso não, liga o carro.
 - desligar(): Verifica se o veículo já se encontra desligado, caso não, desliga o carro. Não permitir que desligue o veículo com (velocidade > 0).

![image](https://user-images.githubusercontent.com/69171098/140646830-f38394b9-921a-44f4-b3de-5471ecf68bdd.png)


Exercício 2

Seguindo o diagrama UML a seguir, implemente as classes, interfaces e as
saídas do programa. Após a implementação, testar cada um dos métodos via
console.

calculaImposto( ): método para calcular imposto sobre um 
produto com a seguinte regra:
• Livros:
1. Se o livro for de tema = “educativo” não se deve cobrar 
imposto, retornar 0.
2. Caso seja de qualquer outro tema, calcular imposto de 10% 
sobre o preço do livro.
• Video Game:
1. Se o vídeo game for usado, calcular imposto de 25% sobre 
o preço do videogame.
2. Se o vídeo game não for usado, calcular imposto de 45% 
sobre o preço do videogame.

listaLivros( ): lista todos os livros que uma loja tem, caso a 
lista de livros seja vazia, mostrar no console "A loja não tem 
livros no seu estoque.".

listaVideoGames ( ): lista todos os vídeo games que uma 
loja tem, caso a lista de vídeo games seja vazia, mostrar no 
console "A loja não tem video-games no seu estoque.".

calculaPatrimonio( ): Soma os preços de todos produtos da 
loja e retorna este valor como double.

![image](https://user-images.githubusercontent.com/69171098/140646976-7d9e935b-d9ba-45db-b907-71c414b3333f.png)

![image](https://user-images.githubusercontent.com/69171098/140646994-5aaa6b1b-1013-4c83-916b-fecb72fed5c8.png)

UML
![image](https://user-images.githubusercontent.com/69171098/140647024-bc8ba24d-24d8-42b7-8902-e70afdfed2bb.png)


Exercício 3 

Seguindo o diagrama UML, implemente as classes e exiba no console
conforme a imagem a seguir:
![image](https://user-images.githubusercontent.com/69171098/140647096-9f662d96-3a89-4776-8c06-3e8f6920d066.png)

1 - Usando o conceito de polimorfismo, implemente o método lvlUp(), de forma que o Mago ao subir de nível possua um aumento maior nos
atributos Mana e Inteligência e o Guerreiro possua um aumento maior nos atributos Vida e Força.
2 - Implemente o método attack() de forma que siga a seguinte regra:
Mago 🧹 : ( Inteligência * Level ) + numeroRandomico( 0 até 300 ).
Guerreiro ⚔: ( Força * Level ) + numeroRandomico( 0 até 300 ).
3 -  Exiba a quantidade de Personagens criados, utilize atributo static para
implementar a solução.


Exercício 4

![image](https://user-images.githubusercontent.com/69171098/140647208-ea6ed608-10bc-4028-b914-1025d489bb9c.png)


Exercício 5

Aproveitando a questão anterior (4) - Exclua da Lista as pessoas com idade
inferior a 18 anos. E exiba a quantidade da lista antes e depois da
exclusão. (Não reescreva o código do item 01).

Exercício 6

![image](https://user-images.githubusercontent.com/69171098/140647244-fe286c2e-dede-434b-b2cb-f6ce2beb5d06.png)


Exercício 7

Considerando os conceitos de Orientação a Objetos, crie uma classe Pai de nome Funcionário com os seguintes atributos (nome, idade e salário) e mais
três classes Filhas (Gerente, Supervisor e Vendedor). Na classe Funcionário deve existir um método de nome bonificação que retorna o salário, nas
classes filhas deve existir o mesmo método bonificação porem com as seguintes regras: 
Para Gerente, o método bonificação deve retornar o salário + 10000.00;
Para Supervisor, o método bonificação deve retornar o salário + 5000.00;
Para Vendedor, o método bonificação deve retornar o salário + 3000.00;
Por fim, criar uma classe principal que instancie objetos de Gerente, Supervisor e Vendedor e adicione no mínimo um valor para cada atributo e
imprima cada funcionário (Gerente, Supervisor e Vendedor) com suas devidas bonificações.










