# Changelog

Todas as mudanças relevantes deste projeto são documentadas neste arquivo.

O formato segue o [Keep a Changelog](https://keepachangelog.com/pt-BR/1.1.0/)
e o projeto adota o [Versionamento Semântico](https://semver.org/lang/pt-BR/).

## [1.1.0] - 2026-09-28

### Adicionado
- Testes para validação de notas inválidas.
- Exibição da média com uma casa decimal.
- Aprovação com distinção para médias maiores ou iguais a 9,0.

### Alterado
- Cálculo da média reescrito sem o uso de for.

### Corrigido
- Correção da situação do aluno para média 7,0, que passou a ser considerada como Aprovado.

## [1.0.0] - 2026-09-14

### Adicionado

- Cálculo da média aritmética das notas.
- Classificação da situação do aluno: Aprovado, Recuperação ou Reprovado.
- Execução pela linha de comando (`npm start -- <notas>`).
- Integração contínua com testes e verificação de Conventional Commits.
