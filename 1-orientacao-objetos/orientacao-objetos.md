#Orientação a Objetos
## O que é Orientação a Objetos?
Definição formal:
 >*"O termo orientação a objetos significa organizar  o mundo real como uma coleção de objetos que incorporam estrutura de dados e um conjunto de operações que manipulam estes dados."*
## Vantagens:
- Organização
- Escreve menos
- Concentração de responsabilidades
- Reaproveita Código
##### Exemplo de Objeto:

```java
// Uma classe é um objeto
public class Pessoa {

    // Atributos são características do objeto
    private String nome;
    private int idade;
    private double altura;
    private double peso;
    private Pais paisNascimento // este atributo faz referência a um outro objeto do tipo País.
    
    public Pessoa(String nome, int idade, double altura, double peso, Pais paisNascimento){
        this.nome = nome;
        this.idade = idade;
        this.altura = altura;
        this.peso = peso;
        this.paisNascimento = paisNascimento;
    }

    // Métodos são ações do objeto
    public void falar() {
        Sysout("Olá Mundo");
    }

    public void andar() {
        Sysout("Andando...");
    }

    public void respirar() {
        Sysout("Respirando....")
    }
}
```
