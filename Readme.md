

## Criando a Base do projeto
```bash
# Iniciando um projeto Node 
$ npm init -y

# Instalando o Typescript e dependencias jest
$ yarn add typescript jest @types/jest ts-node ts-jest

# Inicializar um projeto com Typescript
$ npx tsc --init

# Rodar o projeto
$ npx ts-node src/main.ts

# Gera o arquivo de configuracoes do jest 
$ npx ts-jest config:init 
```

## **Orientação a Objetos**
 
 **Objeto** é uma junção de características e comportamento. 

## **Algumas definições**

### **Comportamento** 
  É o que faz os clientes ganharem ou economizarem dinheiro. </br>
  Quanto mais **comportamento**, _mais estrutura será necessária para suportá-lo_.


### **Estrutura** 
  É o que mantém o comportamento de pé, sem colapsar. </br>
  Pense na estrutura como: **métodos, classes, módulos, serviços** e principalmente a relação entree cada uma delas.  


## **Clean Code**

## Refactoring

 "É a alteração feita na estrutura interna do software para torná-lo mais fácil de ser entendido e menos custoso de ser modificado, _sem alterar seu comportamento observável_"
 **Martin Fowler**
 </br>
 </br>
 **Refactoring** é um investimento, torna o software sustentável e competitivo.
 </br>


 **Refatore :** 
 * Com um **propósito**, evite refatorar apenas por refatorar.
 * Na hora de **adicionar** novas funcionalidades.
 * Quando for **corrigir** um defeito.
 * Quando precisar **entender** uma parte do código.

 ## Code Smells

* **Nomes estranhos** de variáveis, métodos e classes. 
* **Números Mágicos** substituir numeros mágicos por constantes. 
* **Comentários** Código comentado não deve ser comitado e deve ser apagado.
* **Linha em Branco** dentro do método não deve ter linha em branco, apagar as linhas em branco.
* **Código Duplicado** aplicar extração de método.
* **Longa Lista de Parâmetros** aplicar extração de classe.
* **Variáveis declaradas longe da utilização** levar a declaração da variável para perto da utilização.
* **Variáveis com declaração conjunta** desfazer junção, declarando a variável isoladamente.
* **Condições confusas** remover condições aninhada por clausulas guarda.
* **Consolidar expressão condicional** remover aninhamento.
* **Introduzir comando ternário** sempre que der, não utilizar ternário aninhado.
* **Falta de tratamento de exceções** substituir o código de erro por exceção.

## TDD - Test-Driven Development

Os testes automatizados são a **unica forma** que temos para _garantir que o código funciona e continuará funcionando_.
</br>
</br>
Os testes manuais são importantes, **principalemnte para a aceitação por parte de usuários-chave**, mas devem ser complementares e _não garantem que não existirá a regressão ao longo do tempo_.



