<img align=left src="https://i.imgur.com/P9fjzh4.png" height=150 alt="badge-challenge">

<h2 align=center>Challenge ONE Back End - Java</h2>

<div align=center>

<img height="80" margin="10" src="https://i.imgur.com/9Gq6RS0.png">
</div>

### Sprint 01: Crie seu próprio conversor de moeda

<br> 

## História

Nesta oportunidade foi solicitado para nós Devs a criação de um conversor de moeda utilizando a linguagem Java. As
características solicitadas por nosso cliente são as seguintes:

O conversor de moeda deverá:

- Converter de Reais a Dólar
- Converter de Reais a Euro
- Converter de Reais a Libras Esterlinas
- Converter de Reais a Peso Argentino
- Converter de Reais a Peso Chileno

Lembrando que deve ser possível também converter de forma inversa.


<br>



### Conversão

- As unidades de conversão são divididas em Classes, cada classe possui suas unidades em forma de atributo estático (que
  seria uma instância da Classe). Cada unidade possui um **símbolo**, um **fator multiplicador** (que é usado no método
  para fazer a conversão entre as unidades) e o seu **nome**.
- Uma unidade pode ser **convertida para outra** chamando seu próprio método convert, assim:

```java
BigDecimal result = REAL.convert(new BigDecimal("1"), DOLAR);
```

! O fator multiplicador das moedas é o valor equivalente de 1 em relação ao Dolar, para facilitar a conversão entre
elas.

### GUI

- [x] Conforme sugerido para este Challenge, foi utilizado o kit de componentes GUI do próprio Java, chamado **Swing**,
  onde podemos criar componentes e interfaces gráficas com o paradígma orientado a objetos.

- [x] Fácil expansão e adição de novas unidades de conversão
- Para adicionar novas unidades, basta criar uma subclasse
  Unit</a>.

- Para adicionar a tela referente a essa nova unidade de conversão basta:

  1- Criar uma classe que estenda a classe
  abstrata 

  2- Implementar e concretizar os métodos abstratos.

  3- Adicionar essa nova tela ao objeto na NavBar,
  conforme

- Para criar qualquer outra tela, basta criar um classe que estenda de JPanel e implemente a
  interface 
<br>

## Tecnologias utilizadas

- Linguagem: Java 8
- IDE: 
- Inteface (GUI): 
- Testes: 
- Currency API

<br><br>
# Conversor-de-Moeda
