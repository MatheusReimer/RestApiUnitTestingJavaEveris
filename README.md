# Esse é o processo pelo qual fiz o desenvolvimento do software com base na aula do estoque de cerveja da DIO
<h2>Os testes foram utilizados utilizando o framework de testes JUnit 5 em conjunto com o Mockito</h2>
<h3>Primeiramente o UML</h3></br>

  ![Screenshot_1](https://user-images.githubusercontent.com/56495954/127921592-876483d0-8505-4060-9126-2853c11739be.png)

</br>
<p>Neste projeto, ao invés de seguir com o controle de estoque de cervejas como sugerido pela DIO, foi realizado um desenvolvimento de um projeto REST 
baseado no gerenciamento de alunos para uma escola.
</p>
<p>Após a criação dos arquivos relacionados com Entidades,Controllers,Enums,Exceptions,Repositories e Services</br>
foram criados alguns arquivos teste de unitários na pasta tests.</br>
Primeiramente foram feitos testes unitários nos 2 métodos da classe StudentRepositoryTest utilizando  JUnit5. Conferidos estes métodos passamos para as outras classes.</br>
Nota-se que feito isso, é preciso mockar o StudentRepository porque sabe-se que o mesmo já está funcional.</br>
Utilizando então da ferramenta mockito, foram realizados os devidos testes nos métodos da classe StudentService para certificar que tudo estava correndo nos conformes
</p>
