# Modificadores de Acesso
## Como controlar acesso?
Modificadores de acesso são padrões de visibilidade de acesso às **classes**, **atributos** e **métodos**.

Exemplos de tipos de modificadores:
- **public** (pode ser acessado de qualquer lugar.)
- **private** (não são acessados por classes externas nem por classes herdadas.)
- **protected** (acessável por classes do mesmo pacote ou por herança.)
- **default** (são acessíveis sommente por classes do mesmo pacote, não sendo necessário definir nenhum tipo de modificador na sua declaração. O compilador identifica o *default*.)

> Modificador de acesso também é chamado de **Modificador de Visibilidade**

[![Tabela Modificadores Devmedia](table-modificadores-acesso-devmedia.jpg)](https://www.devmedia.com.br/metodos-atributos-e-classes-no-java/25404)

#### Dicas importantes:
 - Cada classe é responsável por controlar seus atributos.
 - Uma validação por exemplo, não deve ser controlada por quem está usando a classe e sim por ela mesma. Isso centraliza a responsabilidade e facilita futuras mudanças.
 - Uma boa prática é que seus atributos sejam *private* e **quase todos** seus métodos sejam *public*

[Próxima sessão - Atributos de Classe](atributos-classe.md)