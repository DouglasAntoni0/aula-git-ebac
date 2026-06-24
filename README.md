# Aula Git EBAC

![Git](https://img.shields.io/badge/Git-versionamento-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-fluxo%20de%20commit-181717?style=for-the-badge&logo=github&logoColor=white)

Exercício de formação voltado ao uso prático de Git e GitHub: clonar repositório, editar arquivo, registrar alteração e publicar o resultado em um repositório próprio.

## Objetivo

O repositório trabalha um fluxo essencial para qualquer atuação em engenharia de software e QA: modificar um artefato, manter histórico claro e entregar a alteração de forma rastreável.

## O que este projeto demonstra

| Competência | Evidência |
| --- | --- |
| Git workflow | Clone, alteração, commit e publicação |
| Rastreabilidade | Mudanças registradas no controle de versão |
| Organização de entrega | Arquivo de instrução e artefato de exercício separados |
| Comunicação técnica | README com contexto, objetivo e leitura profissional |

## Estrutura

```text
.
├── README.md
└── dados.txt
```

## Como reproduzir

```bash
git clone https://github.com/DouglasAntoni0/aula-git-ebac.git
cd aula-git-ebac
```

Edite `dados.txt`, registre a alteração e envie para o GitHub:

```bash
git status
git add dados.txt
git commit -m "Atualiza dados do exercicio"
git push
```

## Resultado técnico

A entrega reforça fundamentos de colaboração: clareza de alteração, histórico versionado e organização mínima para que outra pessoa entenda rapidamente o propósito do repositório.
