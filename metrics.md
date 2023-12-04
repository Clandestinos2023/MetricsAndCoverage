# Após análise, foi possível categorizar as tratativas em 4 grupos:

## Method body is too long (15 errors)
Esse erro não possui tratativa, visto que os métodos problemáticos são os de inicialização das views e são padrões inalteráveis.

## Class has too many fields (12 errors)
Esse erro se deve ao fato de que algumas views possuem muitos campos e componentes, logo não há tratativas.

## Logical expression too complex (2 errors)
Esse erro se deve as validações feitas nas classes de funcionário, onde é necessário antes de efetuar qualquer ação, validar se todos os campos estão preenchidos e se as 2 senhas estão iguais.

## Method declares too many parameters (2 errors)
Esse erro se deve ao fato dos métodos relacionados ao select e update de funcionário no banco de dados possuir muitos parâmetros. A solução pro mesmo é passar um objeto Funcionario ao invés de tantos parâmetros. A melhoria ainda não foi implementada, mas está em progresso.
