# Core

Aqui contém o núcleo do sistema! O que realmente é essencial para o funcionamento.
As funcionalidades, as entidades mães do sistema, e os adaptadores que comunicaram
o interior do sistema com o externo.

## Directory Domain

Tudo aquilo que sofre mudanças ou são alterados pelas regras de negócios do sistema
se encontram na pasta `Domain`, também chamadas de entidades. Elas são a representação
dos dados puros que sofreram alterações pelos casos de usos.

## Directory Use Cases

As ações do sistema que operam sobre os Domains, como cálculos e regras que ditam
o funcionamento do negócio tal como o que é preciso fazer para criar uma diária e
suas consequências.

## Directory Interface Adapters

Core deverá ficar completamente desacoplada a tudo que não seja java puro! A camada
de interface adapters é a camada ponte entre o exterior a o inferior. Ela dita
contratos que as camadas externdas deveram seguir sempre para que possa assim
enviar 
