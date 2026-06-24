# Aula Git EBAC

![Git](https://img.shields.io/badge/Git-versionamento-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-fluxo%20de%20commit-181717?style=for-the-badge&logo=github&logoColor=white)
![QA](https://img.shields.io/badge/QA-rastreabilidade-0A66C2?style=for-the-badge)

Exercício de formação voltado ao uso prático de Git e GitHub: clonar repositório, editar arquivo, registrar alteração e publicar o resultado em um repositório próprio.

O foco não está em complexidade de código. O foco está em processo: entender como uma mudança sai da máquina local, vira commit, entra no histórico e pode ser revisada por outra pessoa. Esse é um fundamento direto para qualquer atuação em Quality Engineering.

## Objetivo

O repositório trabalha um fluxo essencial para engenharia de software e QA:

- obter uma cópia local do projeto;
- modificar um arquivo de exercício;
- verificar alterações;
- criar commit com mensagem clara;
- publicar o resultado no GitHub;
- manter o repositório compreensível para consulta futura.

Esse ciclo aparece diariamente em projetos reais: automações são versionadas, evidências podem ser anexadas, correções passam por revisão e pipelines dependem de histórico confiável.

## O que este projeto demonstra

| Competência | Evidência | Valor profissional |
| --- | --- | --- |
| Git workflow | Clone, alteração, commit e publicação | Base para colaboração técnica |
| Rastreabilidade | Mudanças registradas no controle de versão | Facilita auditoria e investigação |
| Organização de entrega | Arquivo de instrução e artefato de exercício separados | Evita confusão sobre objetivo do repo |
| Comunicação técnica | README com contexto e comandos | Ajuda quem revisa ou acessa depois |
| Mentalidade de QA | Cuidado com histórico e clareza | Sustenta evidências e documentação de testes |

## Estrutura

```text
.
├── README.md   # Documentação do exercício
└── dados.txt   # Arquivo usado na prática de alteração
```

O arquivo `dados.txt` funciona como artefato de exercício. Ele permite simular uma mudança simples e registrar essa alteração com Git.

## Como reproduzir

Clone o projeto:

```bash
git clone https://github.com/DouglasAntoni0/aula-git-ebac.git
cd aula-git-ebac
```

Verifique o estado inicial:

```bash
git status
```

Edite `dados.txt` e confira a diferença:

```bash
git diff
```

Registre a alteração:

```bash
git add dados.txt
git commit -m "Atualiza dados do exercicio"
git push
```

## Critérios de uma boa entrega neste exercício

Uma entrega bem organizada deve ter:

- arquivo correto alterado;
- commit com mensagem compreensível;
- repositório publicado no GitHub;
- README explicando o objetivo;
- ausência de arquivos desnecessários;
- histórico limpo o suficiente para revisão.

## Leitura de QA

Para um profissional de qualidade, Git ajuda a responder perguntas importantes:

- qual versão foi testada;
- qual commit introduziu uma mudança;
- qual arquivo foi modificado antes de uma falha;
- qual evidência pertence a qual entrega;
- quando uma automação foi ajustada;
- se um bug está ligado a mudança recente.

Por isso, mesmo uma tarefa simples de Git tem conexão direta com rastreabilidade e qualidade de entrega.

## Resultado técnico

A entrega reforça fundamentos de colaboração: clareza de alteração, histórico versionado e organização mínima para que outra pessoa entenda rapidamente o propósito do repositório.

## Competências evidenciadas

- Uso inicial de comandos Git.
- Publicação de projeto no GitHub.
- Controle de alteração em arquivo textual.
- Escrita de documentação contextual.
- Visão de rastreabilidade aplicada à rotina de QA.

## Próximos passos possíveis

- Criar branches para simular fluxo de Pull Request.
- Adicionar checklist de revisão antes do commit.
- Registrar exemplos de mensagens de commit boas e ruins.
- Conectar o exercício a um fluxo básico de CI apenas para validação de Markdown.

## Conclusão

Este repositório demonstra um fundamento: nenhuma entrega técnica deveria ser uma caixa-preta. Git, README e histórico claro são ferramentas simples, mas poderosas para qualidade, colaboração e confiança no trabalho entregue.
