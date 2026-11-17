# Palco — Plataforma de Gestão de Eventos com Inscrições

**Disciplina:** Desenvolvimento Front-End (2AV)

## Integrantes
- Marcos Gabriel Rocha Galvão
- Iago Vinicius Bandeira dos Santos
- João Pedro Gonçalves De Lima
- Iasmim Sales Rodrigues
- Miguel Victor victor de Oliveira Santos

## Descrição da solução
O **Palco** é uma aplicação web feita com HTML, CSS e JavaScript puros, sem frameworks e sem back-end, para ajudar uma empresa a organizar seus eventos. Com ela, o organizador cadastra eventos, acompanha as vagas disponíveis e consulta quem está inscrito, enquanto o participante escolhe um evento e faz sua inscrição de forma simples. Os dados ficam salvos no navegador, usando `localStorage`.

## Páginas da aplicação
| Página | Arquivo | O que apresenta |
|---|---|---|
| Início | `index.html` | Apresentação do Palco, indicadores (eventos cadastrados, participantes inscritos e vagas disponíveis), próximos eventos e chamada para gerenciar eventos |
| Eventos | `eventos.html` | Formulário "Novo evento", busca por nome ou local, filtro por situação e cartões dos eventos com vagas e ocupação |
| Inscrição | `inscricao.html` | Formulário de inscrição com nome completo, e-mail e escolha do evento |
| Participantes | `participantes.html` | Tabela de inscritos com filtro por evento, busca por nome ou e-mail e ação de cancelar inscrição |

## Principais funcionalidades
- Cadastro, edição e exclusão de eventos, com nome, data, local, capacidade e descrição
- Pesquisa de eventos por nome ou local e filtro por situação (disponível, lotado ou encerrado)
- Cálculo automático de inscritos, vagas restantes e percentual de ocupação de cada evento
- Indicadores na página inicial: total de eventos, participantes inscritos e vagas disponíveis
- Inscrição de participantes, bloqueando evento lotado, evento encerrado e e-mail repetido no mesmo evento
- Lista de participantes com filtro por evento, busca por nome ou e-mail e cancelamento de inscrição
- Validação dos formulários e mensagens de sucesso, erro e confirmação
- Persistência dos dados com `localStorage` e layout responsivo para computador e celular

## Identidade visual
- **Cores:** roxo `#6a4fd8`, lilás `#ebe7fb`, preto `#0b0b0b`, fundo cinza-claro `#f7f7f7` e cinza para textos de apoio
- **Fontes:** Archivo Narrow nos títulos e Source Serif 4 nos textos
- **Logo:** quadrado roxo com a letra "P", acompanhado de "palco." e "GESTÃO DE EVENTOS"

## Estrutura de arquivos
```
palco-paginas/
├── index.html
├── eventos.html
├── inscricao.html
├── participantes.html
├── css/
│   └── index.css
│   └── eventos.css
│   └── inscricao.css
│   └── participantes.css
│     
├── js/
│   ├── index.js
│   ├── eventos.js
│   ├── inscricao.js
│   └── participantes.js
├── assets/
│   └── imagens/
├── README.md
└── PLANEJAMENTO.md
```

## Como executar
1. Baixe e extraia a pasta do projeto.
2. Abra o arquivo `index.html` em um navegador moderno (Chrome, Edge ou Firefox).
3. Não é necessário instalar nada nem usar servidor.


## Divisão das responsabilidades
- **Marcos Gabriel e Miguel Victor:** HTML/CSS e responsividade
- **João Pedro:** JavaScript de eventos
- **Iago Vinicius:** JavaScript de inscrições e participantes
- **Iasmim Sales Rodrigues:** documentação e telas
