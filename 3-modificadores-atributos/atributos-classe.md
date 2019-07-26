# Atributos de Classe
## O que são atributos?
São elementos que definem a estrutura de uma classe. Estes são conhecidos também como **variáveis** de classe.
São dividos em dois tipos: Atributos de **instância** e atributos de **classe**. 

 - **de Instância:**
Seus valores determinam o estado de cada objeto.
 - **de Classe:**
 Possui um estado que é compartilhado por todos objetos de uma classe. Estes atributos podem ser chamados de **estáticos** (declara-se _**static**_).

 > Constantes são considerados atributos de classe quando estão fora de métodos.

 #### Observações
 > Métodos e atributos estáticos só podem acessar outros métodos e atributos estáticos da mesma classe, já que dentro de um método estático não se tem acesso a referência _**this**_, pois um método estático é chamado através da classe e não de um objeto.