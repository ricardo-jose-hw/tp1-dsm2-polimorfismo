Pergunta: Discuta como a sobrecarga de construtores facilita a criação de objetos com diferentes conjuntos de informações, permitindo flexibilidade na instânciação de objetos.

Resposta: A sobrecarga de construtores permite criar objetos de uma mesma classe usando a mesma "assinatura", permitindo uma flexibilidade embora exija uma manipulação melhor para condicionais como: se estoque estiver zerado, exiba estoque esgotado, tendo que realizar mais uma etapa para esta condicional.


Pergunta: Como o polimorfismo por sobrescrita facilita a implementação de diferentes formas de pagamento dentro de um sistema sem alterar o código da classe base?

O polimorfismo permite que diferentes classes implementem suas próprias versões de um método herdado de uma classe base. Estendendo a classe principal, podemos alterar os métodos da secundária para que se alinhem com o necessário.


Pergunta: Explique como a sobrecarga de métodos permite implementar várias versões do método converter(), mesmo com diferentes tipos de dados e funcionalidades.

O método converter() pode realizar conversões diferentes dependendo dos argumentos recebidos, podendo realizar diferentes funções que anteriormente escrevíamos outro método do zero, dificultando a documentação e utilização dos demais.
