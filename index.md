## Padrão GRASP

Boa noite galerinha,

Primeiro vamos entender o que é padrão. Padrão é uma solução geral para um problema que ocorre com frequência dentro de um determinado contexto. Beleza? e agora o que quer dizer GRASP? GRASP é a sigla para General Responsibility Assignment Software Patterns, ou seja, tratam-se de padrões de software responsáveis pela descrição de princípios de fundamental importância  para a atribuição de responsabilidades em projetos orientados a objetos, oferecendo um melhor desempenho do código, e trabalhando acerca de solucionar problemas, garantindo melhor interface do projeto.

O GRASP possúi 4 padrões básicos:

###Information Expert
###Creator
###High Cohesion
###Low Coupling
###Controller

##Information Expert

O que é?
É conhecido por ser o princípio fundamental para atribuir responsabilidade a uma classe.

Benefícios:
###Encapsulamento é mantido;
###Fraco acoplamento (facilidade de manutenção);
###Alta coesão (objetos fazem tudo relacionado à sua própria informação).

##Creator

O que é?
Atribua à classe a responsabilidade de criar uma instância da outra classe.

Benefícios:
###Facilidade no desenvolvimento do projeto e compreensão.

##High Cohesion

O que é?
Atribuir uma responsabilidade para que a coesão se mantenha alta.

Benefícios:
###Melhor claridade e facilidade de compreensão do projeto;
###Simplificação da manutenção;

##Low Coupling

O que é?
Atribui as responsabilidades de modo que o acoplamento entre classes permaneça baixo.

Benefícios:
###Menor dependência entre as classes;
###Mudar de uma classe que tem menor impacto sobre outras classes;
###Maior potencial de reutilização.

##Controller

O que é?
Sim o conhecido controller do MVC, feito por atribuir responsabilidades para receber ou lidar com um evento do sistema.

Benefícios:
###Diminui a sensibilidade da camada de apresentação em relação à lógica de domínio;
###Oportunidade para controlar o estado do caso de uso;

Ou seja, conhecendo esses padrões é possível manter o reaproveitamento e a manutenção do seu código, seja por você ou por outra pessoa.
