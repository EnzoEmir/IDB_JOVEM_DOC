# Guia de Contribuição para o projeto

Este documento fornece um guia passo a passo sobre como contribuir para o projeto **IDB Jovem**. Por favor, leia atentamente antes de iniciar sua contribuição.

## 📋 Pré-requisitos

* Git instalado na sua máquina
* Acesso ao repositório: https://github.com/EnzoEmir/IDB_JOVEM_DOC
* Conhecimento básico de Git
* Editor de texto com suporte a Markdown
* Conhecimento básico de formatação Markdown

---

## 🔄 Fluxo de Trabalho

### 1. Clone do Repositório

```bash
git clone https://github.com/EnzoEmir/IDB_JOVEM_DOC.git
cd IDB_JOVEM_DOC
```

---

### 2. Criação de Branch

1. Atualize a branch principal:

```bash
git checkout main
git pull origin main
```

2. Crie uma nova branch para sua contribuição:

```bash
git checkout -b tipo/nome-da-sua-contribuicao
```

📌 **Padrão de branches:**

* `docs/...` → documentação
* `feature/...` → novas funcionalidades
* `fix/...` → correções de bugs

---

### 3. Desenvolvimento

1. Faça suas alterações no projeto
2. Siga os padrões definidos no README.md
3. Faça commits organizados
4. Mantenha sua branch atualizada:

```bash
git pull origin main
```

---

### 4. Commit das Alterações

Utilize o padrão:

```bash
git commit -m "docs: adiciona seção de integrantes"
```

📌 **Padrão de commits:**

* `docs:` documentação
* `feat:` nova funcionalidade
* `fix:` correção de bug

---

### 5. Push da Branch

```bash
git push origin tipo/nome-da-sua-contribuicao
```

💡 Dica (primeira vez):

```bash
git push -u origin tipo/nome-da-sua-contribuicao
```

---

### 6. Criação do Merge Request (MR)

1. Acesse o repositório no GitLab

2. Clique em **"Create Merge Request"**

3. Configure:

   * **Source branch:** sua branch
   * **Target branch:** `main` (ou `docs`, se for só documentação)

4. Preencha:

   * Título claro
   * Descrição do que foi feito
   * Prints ou evidências (se necessário)

5. Adicione revisores

6. Clique em **"Create Merge Request"**

---

## 🔍 Processo de Revisão

1. **Revisão**

   * Outro membro da equipe revisa
   * Pode sugerir mudanças

2. **Correções**

   * Faça ajustes necessários
   * Dê push novamente (atualiza o MR automaticamente)

3. **Aprovação**

   * Após aprovação, o MR é aceito
   * O código/documentação é integrado ao projeto

---

## 🧠 Boas Práticas

* Commits pequenos e claros
* Nomes de branch descritivos
* Não subir arquivos desnecessários
* Sempre testar antes de subir
* Manter o README atualizado

---

## 🤝 Código de Conduta

* Respeite todos os membros da equipe
* Seja claro e objetivo nas comunicações
* Aceite feedbacks construtivos
* Colabore com o time

## :round_pushpin: Histórico de Versão
<div align="center">
    <table>
    <tr>
        <th>Data</th>
        <th>Data de Revisão</th>
        <th>Versão</th>
        <th>Descrição</th>
        <th>Autor</th>
    </tr>
    <tr>
        <td>28/03/2026</td>
        <td>28/03/2026</td>
        <td>1.0</td>
        <td>Criação inicial</td>
        <td><a href="https://gitlab.com/GabrielSMonteiro">Gabriel Monteiro</a></td>
    </tr>
    </table>
</div>