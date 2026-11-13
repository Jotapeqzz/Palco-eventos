# 1ª Entrega Parcial — Planejamento e Estrutura Inicial
**Projeto:** Palco — Plataforma de Gestão de Eventos com Inscrições
**Disciplina:** Desenvolvimento Front-End (2AV)

## 1. Objetivo, público-alvo e problema
**Objetivo:** permitir que uma empresa cadastre eventos, controle a disponibilidade de vagas e gerencie os participantes inscritos em cada um.

**Público-alvo:**
- Organizadores de eventos, que cadastram eventos e acompanham a ocupação.
- Participantes e atendentes, que realizam e cancelam inscrições.

**Problema que a solução resolve:** quando o controle é feito em planilhas ou mensagens, é comum aceitar mais inscritos do que a capacidade, não saber quais eventos já lotaram, perder informações e ter dificuldade para saber quem vai participar de cada evento.

## 2. Páginas que compõem a aplicação
| Página | Arquivo | Função |
|---|---|---|
| Início | `index.html` | Apresentação do sistema e acesso às demais áreas |
| Eventos | `eventos.html` | Lista de eventos com busca, filtro por situação, vagas e ocupação; cadastro, edição e exclusão |
| Inscrição | `inscricao.html` | Formulário validado para inscrever participantes, bloqueando eventos lotados ou encerrados |
| Participantes | `participantes.html` | Inscritos por evento, com busca e cancelamento de inscrição |

## 3. Proposta de identidade visual
Estamos pensando na nossa indentidade visual


## 4. Organização das interfaces
Todas as páginas têm o mesmo cabeçalho, com o nome Palco e o menu (Início, Eventos, Inscrição, Participantes), e abaixo dele o conteúdo da página. Em telas pequenas, o menu e os filtros quebram em linhas e os cartões de evento passam a ocupar uma coluna.

## 5. Estrutura inicial do projeto
```
palco-paginas/
├── index.html
├── eventos.html
├── inscricao.html
├── participantes.html
├── css/        um CSS por página
├── js/         um JS por página
├── assets/imagens/
└── README.md
```

## 6. Navegação
Todas as páginas já estão criadas e ligadas pelo menu do cabeçalho, permitindo ir de uma área para outra.

## 7. Escopo e etapas
**Concluído nesta etapa:** planejamento, definição das páginas, proposta visual, estrutura de pastas e arquivos, e navegação entre as páginas.

**Funcionalidades previstas, por página:**
- **Eventos:** cadastro com validação, edição, exclusão, busca, filtro por situação, quantidade de vagas e percentual de ocupação.
- **Inscrição:** formulário com validação, bloqueio sem vagas e e-mail repetido, mensagens de sucesso e erro.
- **Participantes:** lista por evento, busca e cancelamento de inscrição.
- **Todas:** persistência com `localStorage` e layout responsivo.
