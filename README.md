<img align=left src="https://i.imgur.com/P9fjzh4.png" height=150 alt="badge-challenge">

<h2 align=center>Challenge ONE Back End - Java</h2>

<div align=center>

<img height="80" margin="10" src="https://i.imgur.com/9Gq6RS0.png">
</div>

### Sprint 01: Crie seu próprio conversor de moeda

<br> 

## História

História
Curso: Java e Orientação a Objetos
Turma: G8 - ONE
Módulo: Praticando Java: Challenge Conversor de Moedas

Conversor de Moedas é um projeto cujo seu objetivo central é automatizar o processo de conversão entre diferentes moedas, garantindo que os participantes possam realizar trocas de valores de forma precisa e eficiente Neste desafio, foi solicitado aos desenvolvedores a criação de um conversor de moedas utilizando a linguagem Java. O objetivo principal do. As funcionalidades exigidas pelo cliente são as seguintes:
O conversor de moedas deverá:
•	Converter de Reais para Dólar
•	Converter de Reais para Euro
•	Converter de Reais para Libras Esterlinas
•	Converter de Reais para Peso Argentino
•	Converter de Reais para Peso Chileno
Além disso, o sistema também deve permitir a conversão inversa entre as moedas.

Conversão
As unidades de conversão são estruturadas em classes, com cada classe contendo suas unidades como atributos estáticos, que representam instâncias da própria classe. Cada unidade possui um símbolo, um fator multiplicador (usado no método de conversão entre as unidades) e um nome. 

Interface Gráfica (GUI)
Para a criação da interface gráfica, foi utilizado o kit de componentes Swing do Java. Esse kit permite a construção de componentes visuais com base no paradigma orientado a objetos, oferecendo uma solução prática e eficaz para a construção de interfaces gráficas.
•	Facilidade de Expansão e Adição de Novas Unidades de Conversão:
Para adicionar novas unidades ao sistema, basta criar uma subclasse da classe Unit.
•	Como Adicionar uma Nova Tela de Conversão:
Para incluir uma nova tela de conversão, siga os seguintes passos:
1.	Crie uma classe que estenda a classe abstrata Screen.
2.	Implemente e concretize os métodos abstratos definidos na classe Screen.
3.	Adicione essa nova tela ao menu de navegação (NavBar) da aplicação.
•	Criação de Outras Telas:
Para criar outras telas, basta criar uma classe que estenda JPanel e implemente a interface Screen_Properties, adicionando-a à NavBar conforme necessário.

Tecnologias Utilizadas
•	Linguagem: Java 8
•	IDE: IntelliJ IDEA
•	Interface (GUI): Swing
•	Testes: JUnit
•	Currency API: AwesomeAPI

Link do repositório no GitHub Para questões técnicas, envie um email para: loisee.dev@gmail.com Para discussões sobre o projeto, utilize a seção de Issues no GitHub. Autores do projeto Seu Nome - Emilli Loise Moraes Campos
