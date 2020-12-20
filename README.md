# Resumo

Projeto com implementação de arquitetura DDD e xUnit para os testes.

## Problema:

- Um determinado produto financeiro recolhe imposto de renda apenas quando o cliente faz o seu resgate. O cálculo do IR segue a seguinte lógica abaixo:
- Até 1 ano de aplicação: 22,5% sobre o lucro
- De 1 a 2 anos de aplicação: 18,5% sobre o lucro
- Acima de 2 anos de aplicação: 15% sobre o lucro
- A aplicação não pode ser igual ou menor que zero
- A data de resgate não pode ser menor que a data de aplicação
