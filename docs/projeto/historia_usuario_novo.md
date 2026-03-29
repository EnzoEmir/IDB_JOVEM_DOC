# Introdução

O presente documento tem como objetivo apresentar as histórias de usuário elaboradas para o desenvolvimento do projeto da disciplina **TÉCNICAS DE PROGRAMAÇÃO EM PLATAFORMAS EMERGENTES - (FGA0242)** voltado à criação de uma plataforma web para a **Igreja de Deus (IDB Jovem e Teen)**. O projeto consiste em uma landing page estratégica destinada à divulgação de eventos, apresentação da identidade do grupo, localização e centralização de informações essenciais para a comunidade, visando otimizar a comunicação e o engajamento dos membros e visitantes <a href="#REF1" id="cit-1">[1]</a>.

As histórias de usuário são uma técnica fundamental na Engenharia de Requisitos Ágil, utilizadas para representar funcionalidades, resultados ou características desejadas no software. Elas são criadas a partir da escuta ativa das necessidades dos usuários e servem como guia para o desenvolvimento.

Cada história de usuário é construída de forma a responder três perguntas essenciais:  

- **Quem?** — Quem é o usuário ou persona envolvida na interação.  

- **O que?** — Qual é a ação, necessidade ou funcionalidade desejada.  

- **Por que?** — Qual é o valor, objetivo ou benefício buscado por meio daquela ação.

### Construção das Histórias de Usuário

As histórias de usuário foram escritas seguindo o modelo clássico:

> **Como [usuário], quero [ação], para [atingir um objetivo].**

Essa estrutura ajuda a garantir que cada história represente uma necessidade real do usuário, deixando claro o objetivo e o valor gerado pela funcionalidade.

### Definição dos Critérios de Aceitação

Para cada história de usuário, foram estabelecidos critérios de aceitação claros e objetivos. Esses critérios funcionam como referência para confirmar se a funcionalidade entregue atende aos requisitos previamente acordados e, sobretudo, às expectativas da cliente.

### Participantes


<font size="3"><p style="text-align: center">Tabela 1: Participantes</p></font>

<div align="center">

<table>
  <thead>
    <tr>
      <th align="center">Nome</th>
      <th align="center">Data</th>
      <th align="center">Hora</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/EnzoEmir">Enzo Emir</a></td>
      <td align="center">29/03/2026</td>
      <td align="center">14:00</td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/GabrielSMonteiro">Gabriel Monteiro</a></td>
      <td align="center">29/03/2026</td>
      <td align="center">14:00</td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/Leticia-Arisa-K-Higa">Leticia Arisa</a></td>
      <td align="center">29/03/2026</td>
      <td align="center">14:00</td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/MM4k">Marcelo Makoto</a></td>
      <td align="center">29/03/2026</td>
      <td align="center">14:00</td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/dudaa28">Maria Eduarda</a></td>
      <td align="center">29/03/2026</td>
      <td align="center">14:00</td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/VictorPontual">Victor Pontual</a></td>
      <td align="center">29/03/2026</td>
      <td align="center">14:00</td>
    </tr>
  </tbody>
</table>
</div>


<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/dudaa28">Maria Eduarda</a></p>

## Sumário

- [H01 – Acesso à Landing Page](#h01)
- [H02 – Calendário de Eventos](#h02)
- [H03 – Navegação de Materiais](#h03)
- [H04 – Redirecionamento de Compra](#h04)
- [H05 – Disponibilidade em Eventos](#h05)
- [H06 – Criação e Edição de Eventos](#h06)
- [H07 – Gestão de Programação](#h07)
- [H08 – Inscrição Externa](#h08)
- [H09 – Sincronização de Agenda](#h09)
- [H10 – Formulário de Inscrição de Voluntário](#h10)
- [H11 – Notificação de Candidatura](#h11)
- [H12 – Armazenamento de Dados de Voluntários](#h12)
- [H13 – Aprovação de Candidatos](#h13)
- [H14 – Contagem de Voluntários por Evento](#h14)
- [H15 – Login Administrativo](#h15)
- [H16 – Multi-Administradores](#h16)
- [H17 – Gestão de Estoque](#h17)

---

##  Histórias de Usuário

A tabela [2](#tabela-modelo) será utilizada como modelo para a elaboração das histórias de usuário do projeto. Ela padroniza os principais elementos necessários, como a descrição da necessidade, critérios de aceitação, prioridade, status de validação, entre outros. O objetivo é garantir consistência, rastreabilidade e clareza em todas as histórias documentadas.

<p align="center">Tabela 2: <i>Modelo para História de Usuário.</i></p>
<a name="tabela-modelo"></a>
<div align="center">
<table>
  <thead>
    <tr>
      <th><strong>Item</strong></th>
      <th><strong>Descrição</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID</td>
      <td>USx</td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td>Código do requisito</td>
    </tr>
    <tr>
      <td>Tema</td>
      <td>Título</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td>Eu, como <em>[tipo de usuário]</em>, desejo <em>[ação desejada]</em> para <em>[objetivo]</em></td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>- [Critério 1] <br> - [Critério 2]</td>
    </tr>
    <tr>
      <td>Prioridade Usuário</td>
      <td>Alta, Média, Baixa</td>
    </tr>
    <tr>
      <td>Status</td>
      <td>Se a história foi validada ou não pelo usuário</td>
    </tr>
  </tbody>
</table>
</div>
<p style="text-align: center; font-size: 10pt;">Fonte: <a href="https://github.com/dudaa28">Maria Eduarda</a></p>



### História 01 — Acesso à Landing Page

<font size="3"><p style="text-align: center">Tabela: Acesso à Landing Page</p></font>

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | H01                                                                          |
| **Tema**                 | [Experiência do Usuário e Engajamento](../backlog_novo/#tema1)              |
| **Descrição**            | Como visitante, quero acessar uma página inicial moderna para conhecer os objetivos da IDB Jovem & Teen e encontrar rapidamente eventos, materiais ou vídeos. |
| **Critérios de Aceitação** | - Landing page com design moderno e responsivo  <br> - Seção destacada com objetivos da IDB Jovem & Teen <br> - Links navegáveis para eventos, materiais e vídeos <br> |
| **Prioridade**           | -                                                                          |
| **Status**               | Não iniciado                                                                 |

---

<a name="h02"></a>

### História 02 — Calendário de Eventos

<font size="3"><p style="text-align: center">Tabela: Calendário de Eventos</p></font>

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | H02                                                                          |
| **Tema**                 | [Experiência do Usuário e Engajamento](../backlog_novo/#tema1)              |
| **Descrição**            | Como participante, quero visualizar uma aba de eventos em formato de calendário para planejar minha participação. |
| **Critérios de Aceitação** | - Calendário navegável por mês <br> - Eventos destacados nas datas corretas <br> - Visualização de horário e local ao clicar no evento <br> |
| **Prioridade**           | -                                                                          |
| **Status**               | Não iniciado                                                                 |

---

<a name="h03"></a>

### História 03 — Navegação de Materiais

<font size="3"><p style="text-align: center">Tabela: Navegação de Materiais</p></font>

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | H03                                                                          |
| **Tema**                 | [Experiência do Usuário e Engajamento](../backlog_novo/#tema1)              |
| **Descrição**            | Como usuário, quero acessar um catálogo dividido entre produtos físicos (camisetas, livros, etc) e digitais (e-books) para conhecer a produção da igreja. |
| **Critérios de Aceitação** | - Catálogo com abas de produtos físicos e digitais <br> - Descrição completa de cada produto <br> - Imagens de - qualidade <br> - Filtros por categoria |
| **Prioridade**           | -                                                                         |
| **Status**               | Não iniciado                                                                 |

---

<a name="h04"></a>

### História 04 — Redirecionamento de Compra

<font size="3"><p style="text-align: center">Tabela: Redirecionamento de Compra</p></font>

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | H04                                                                          |
| **Tema**                 | [Experiência do Usuário e Engajamento](../backlog_novo/#tema1)              |
| **Descrição**            | Como interessado em um material, quero ser redirecionado para sites externos de compra para finalizar a aquisição com segurança. |
| **Critérios de Aceitação** | - Botão de compra com redirecionamento seguro <br> - Links para Hotmart, e-inscrição ou plataformas de vendas <br> - Abertura em nova aba <br> - Confirmação visual do redirecionamento |
| **Prioridade**           | -                                                                         |
| **Status**               | Não iniciado                                                                 |

---

<a name="h05"></a>

### História 05 — Disponibilidade em Eventos

<font size="3"><p style="text-align: center">Tabela: Disponibilidade em Eventos</p></font>

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | H05                                                                          |
| **Tema**                 | [Experiência do Usuário e Engajamento](../backlog_novo/#tema1)              |
| **Descrição**            | Como participante de um evento presencial, quero saber quais produtos estarão à venda física no local. |
| **Critérios de Aceitação** | - Seção dedicada na página do evento com produtos disponíveis |
| **Prioridade**           | -                                                                         |
| **Status**               | Não iniciado                                                                 |

---

<a name="h06"></a>

### História 06 — Criação e Edição de Eventos

<font size="3"><p style="text-align: center">Tabela: Criação e Edição de Eventos</p></font>

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | H06                                                                          |
| **Tema**                 | [Gestão de Eventos](../backlog_novo/#tema2)                  |
| **Descrição**            | Como administrador, quero criar, editar e excluir eventos nacionais, definindo descrição, palestrantes, bandas e galeria de fotos. |
| **Critérios de Aceitação** | - Formulário completo para criação de eventos <br> - Campos para descrição, palestrantes, bandas e fotos <br> - Edição posterior sem perder dados <br> - Opção de soft delete ou desativação |
| **Prioridade**           | -                                                                          |
| **Status**               | Não iniciado                                                                 |

---

<a name="h07"></a>

### História 07 — Gestão de Programação

<font size="3"><p style="text-align: center">Tabela: Gestão de Programação</p></font>

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | H07                                                                          |
| **Tema**                 | [Gestão de Eventos](../backlog_novo/#tema2)                  |
| **Descrição**            | Como líder, quero cadastrar a programação detalhada (horário, atividade e descrição) de cada evento. |
| **Critérios de Aceitação** | - Interface para adicionar múltiplas atividades com horários <br> - Validação de conflito de horários <br> - Possibilidade de reordenar atividades <br> - Visualização de tabela da programação |
| **Prioridade**           | -                                                                          |
| **Status**               | Não iniciado                                                                 |

---

<a name="h08"></a>

### História 08 — Inscrição Externa

<font size="3"><p style="text-align: center">Tabela: Inscrição Externa</p></font>

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | H08                                                                          |
| **Tema**                 | [Gestão de Eventos](../backlog_novo/#tema2)                  |
| **Descrição**            | Como participante, quero ser redirecionado para o e-inscrição ou Sympla para realizar o pagamento da minha inscrição. |
| **Critérios de Aceitação** | - Botão de inscrição com redirecionamento seguro <br> - Integração com múltiplas plataformas <br> - Rastreamento de conversões <br> - Feedback visual do processo |
| **Prioridade**           | -                                                                          |
| **Status**               | Não iniciado                                                                 |

---

<a name="h09"></a>

### História 09 — Sincronização de Agenda

<font size="3"><p style="text-align: center">Tabela: Sincronização de Agenda</p></font>

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | H09                                                                          |
| **Tema**                 | [Gestão de Eventos](../backlog_novo/#tema2)                  |
| **Descrição**            | Como usuário, quero integrar os eventos diretamente ao meu Google Calendar. |
| **Critérios de Aceitação** | - Botão para adicionar evento ao Google Calendar <br> - Sincronização automática de detalhes (horário, local, descrição) <br> - Autenticação segura com Google <br> - Possibilidade de sincronizar múltiplos eventos |
| **Prioridade**           | -                                                                         |
| **Status**               | Não iniciado                                                                 |

---

<a name="h10"></a>

### História 10 — Formulário de Inscrição de Voluntário

<font size="3"><p style="text-align: center">Tabela: Formulário de Inscrição de Voluntário</p></font>

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | H10                                                                          |
| **Tema**                 | [Gestão de Voluntários](../backlog_novo/#tema3)                              |
| **Descrição**            | Como membro, quero preencher um formulário completo (incluindo antecedentes criminais) para me candidatar como voluntário. |
| **Critérios de Aceitação** | - Formulário com campos obrigatórios e opcionais claramente marcados <br> - Campos para dados pessoais e de antecedentes criminais <br> - Validação de dados em tempo real <br> - Confirmação de envio com ID de candidatura |
| **Prioridade**           | -                                                                          |
| **Status**               | Não iniciado                                                                 |

---

<a name="h11"></a>

### História 11 — Notificação de Candidatura

<font size="3"><p style="text-align: center">Tabela: Notificação de Candidatura</p></font>

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | H11                                                                          |
| **Tema**                 | [Gestão de Voluntários](../backlog_novo/#tema3)                              |
| **Descrição**            | Como responsável pelo evento, quero receber um e-mail automático sempre que houver uma nova candidatura para agilizar a validação. |
| **Critérios de Aceitação** | - E-mail automático ao receber candidatura <br> - Resumo dos dados do candidato no e-mail <br> - Configurar quem recebe e-mail por evento |
| **Prioridade**           | -                                                                          |
| **Status**               | Não iniciado                                                                 |

---

<a name="h12"></a>

### História 12 — Armazenamento de Dados de Voluntários

<font size="3"><p style="text-align: center">Tabela: Armazenamento de Dados de Voluntários</p></font>

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | H12                                                                          |
| **Tema**                 | [Gestão de Voluntários](../backlog_novo/#tema3)                              |
| **Descrição**            | Como administrador, quero que o sistema armazene os formulários dos voluntários para consultas futuras e histórico. |
| **Critérios de Aceitação** | - Banco de dados seguro para armazenamento <br> - Histórico completo de candidaturas <br> - Conformidade com LGPD |
| **Prioridade**           | -                                                                          |
| **Status**               | Não iniciado                                                                 |

---

<a name="h13"></a>

### História 13 — Aprovação de Candidatos

<font size="3"><p style="text-align: center">Tabela: Aprovação de Candidatos</p></font>

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | H13                                                                          |
| **Tema**                 | [Gestão de Voluntários](../backlog_novo/#tema3)                              |
| **Descrição**            | Como administrador, quero revisar e aprovar as candidaturas de voluntários para garantir que atendem aos requisitos necessários. |
| **Critérios de Aceitação** | - Interface de visualização detalhada da candidatura <br> - Botões de Aprovar/Rejeitar <br> - Campo para comentários de avaliação <br> - Notificação automática ao candidato sobre decisão |
| **Prioridade**           | -                                                                          |
| **Status**               | Não iniciado                                                                 |

---

<a name="h14"></a>

### História 14 — Contagem de Voluntários por Evento

<font size="3"><p style="text-align: center">Tabela: Contagem de Voluntários por Evento</p></font>

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | H14                                                                          |
| **Tema**                 | [Gestão de Voluntários](../backlog_novo/#tema3)                              |
| **Descrição**            | Como gestor, quero visualizar quantos voluntários estão inscritos e aprovados por evento para garantir que as equipes estejam completas. |
| **Critérios de Aceitação** | - Dashboard com contadores de inscritos vs aprovados <br> - Visualização por evento <br> - Export dos dados dos voluntários e funções |
| **Prioridade**           | -                                                                         |
| **Status**               | Não iniciado                                                                 |

---

<a name="h15"></a>

### História 15 — Login Administrativo

<font size="3"><p style="text-align: center">Tabela: Login Administrativo</p></font>

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | H15                                                                          |
| **Tema**                 | [Governança e Operações](../backlog_novo/#tema4)                             |
| **Descrição**            | Como líder, quero realizar login no sistema para acessar as ferramentas de gestão. |
| **Critérios de Aceitação** | - Página de login segura com validação de credenciais <br> - Autenticação com dois fatores <br> - Session management com timeout <br> |
| **Prioridade**           | -                                                                          |
| **Status**               | Não iniciado                                                                 |

---

<a name="h16"></a>

### História 16 — Multi-Administradores

<font size="3"><p style="text-align: center">Tabela: Multi-Administradores</p></font>

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | H16                                                                          |
| **Tema**                 | [Governança e Operações](../backlog_novo/#tema4)                             |
| **Descrição**            | Como administrador principal, quero que o sistema suporte pelo menos 6 líderes com permissões de gestão. |
| **Critérios de Aceitação** | - Auditoria de ações por administrador |
| **Prioridade**           | -                                                                          |
| **Status**               | Não iniciado                                                                 |

---

<a name="h17"></a>

### História 17 — Gestão de Estoque

<font size="3"><p style="text-align: center">Tabela: Gestão de Estoque</p></font>

| **Item**                 | **Descrição**                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **ID**                   | H17                                                                          |
| **Tema**                 | [Governança e Operações](../backlog_novo/#tema4)                             |
| **Descrição**            | Como administrador, quero cadastrar produtos na base de dados. |
| **Critérios de Aceitação** | - Formulário de cadastro de produtos |
| **Prioridade**           | -                                                                         |
| **Status**               | Não iniciado                                                                 |

##  Referências Bibliográficas

> <a id="REF1" href="#cit-1">1.</a>  PRESSMAN, Roger S.; MAXIM, Bruce R.. Engenharia de software: uma abordagem profissional. 8 Porto Alegre: AMGH, 2016, 940 p.


##  Histórico de Versão

| Versão | Data       | Descrição                                 | Autor(es)                                     | Revisor(es) |
|--------|------------|--------------------------------------------|-----------------------------------------------|-------------|
| `0.1`    | 29/03/2026 | Base História de Usuário | [Enzo Emir](https://github.com/EnzoEmir), [Gabriel Monteiro](https://github.com/GabrielSMonteiro), [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa), [Marcelo Makoto](https://github.com/MM4K), [Maria Eduarda](https://github.com/dudaa28), [Victor Pontual](https://github.com/VictorPontual) | [Enzo Emir](https://github.com/EnzoEmir), [Gabriel Monteiro](https://github.com/GabrielSMonteiro), [Leticia Arisa](https://github.com/Leticia-Arisa-K-Higa), [Marcelo Makoto](https://github.com/MM4K), [Maria Eduarda](https://github.com/dudaa28), [Victor Pontual](https://github.com/VictorPontual) |
| `0.2`    | 29/03/2026 | Documentação adicional | [Maria Eduarda](https://github.com/dudaa28) |     -     |