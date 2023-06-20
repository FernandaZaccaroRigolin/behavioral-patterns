# behavioral-patterns
Curso Padrões de Projeto - COMPORTAMENTAIS

* CHAIN OF RESPONSABILITY
  ```
  Evita acoplar o remetente de uma requisição ao seu
  destinatário ao dar a mais de um objeto a chance de
  servir a requisição. Compõe os objetos em cascata e
  passa a requisição pela corrente até que um objeto a
  sirva.(GOF)
  ```
* MEMENTO
  ```
  Sem violar o encapsulamento, capturar e externalizar o
  estado interno de um objeto para que o objeto possa ter
  esse estado restaurado posteriormente.(GOF)
  ```
* COMMAND
  ```
  Encapsular uma requisição como um objeto, permitindo
  que clientes parametrizem diferentes requisições, filas
  ou requisições de log, e suportar operações reversíveis.(GOF)
  ```
* ITERATOR
  ```
  Prover uma maneira de acessar os elementos de um
  objeto agregado seqüencialmente sem expor sua
  representação interna.(GOF)
  ```
* OBSERVER
  ```
  Definir uma dependência um-para-muitos entre objetos
  para que quando um objeto mudar de estado, todos os
  seus dependentes sejam notificados e atualizados
  automaticamente.(GOF)
  ```
 * STATE
  ```
  Permitir a um objeto alterar o seu comportamento quanto
  o seu estado interno mudar. O objeto irá aparentar mudar
  de classe.(GOF)
  ```
* STRATEGY
  ```
  Definir uma família de algoritmos, encapsular cada um, e
  fazê-los intercambiáveis. Strategy permite que algoritmos
  mudem independentemente entre clientes que os
  utilizam.(GOF)
  ```
* TEMPLATE METHOD
  ```
  Definir o esqueleto de um algoritmo dentro de uma
  operação, deixando alguns passos a serem preenchidos
  pelas subclasses. Template Method permite que suas
  subclasses redefinam certos passos de um algoritmo
  sem mudar sua estrutura.(GOF)
  ```
