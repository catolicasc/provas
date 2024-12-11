# Prova de JavaScript, CSS e HTML

## Instruções:
1. Utilize os **painéis do JSFiddle** para separar o HTML, CSS e JavaScript.
2. Resolva todos os exercícios de forma progressiva nos respectivos painéis.
3. A complexidade aumenta ao longo das questões.

---

### Questão 1
**Crie uma página com um botão que exiba um alerta quando clicado.**

- O botão deve ter o texto "Clique aqui!".
- Ao clicar no botão, um alerta com a mensagem "Bem-vindo!" deve ser exibido.

**Painéis do JSFiddle:**
- **HTML:** Crie o botão com a tag `<button>`.
- **CSS:** Estilize o botão com uma cor de fundo e bordas arredondadas.
- **JavaScript:** Use o evento `onclick` para exibir o alerta.

---

### Questão 2
**Adicione uma caixa de texto e um botão que exiba o valor da caixa abaixo do botão.**

- Quando o botão for clicado, o texto digitado deve aparecer abaixo.

**Painéis do JSFiddle:**
- **HTML:** Crie uma `<input>` para a caixa de texto e um `<button>` para o envio.
- **CSS:** Centralize os elementos e adicione uma borda na caixa de texto.
- **JavaScript:** Use `document.getElementById` ou `querySelector` para capturar o texto e criar um novo elemento para exibi-lo.

---

### Questão 3
**Crie um contador que aumenta o valor ao clicar em um botão.**

- Adicione um botão com o texto "Incrementar".
- O contador deve começar em 0 e aumentar a cada clique.

**Painéis do JSFiddle:**
- **HTML:** Adicione um elemento para exibir o valor do contador e um botão.
- **CSS:** Estilize o contador para destacar o número.
- **JavaScript:** Utilize uma variável global para armazenar o valor do contador e atualize o DOM ao clicar no botão.

---

### Questão 4
**Crie uma lista onde itens podem ser adicionados dinamicamente.**

- Adicione uma caixa de texto e um botão "Adicionar à lista".
- Cada clique no botão deve adicionar um item à lista.

**Painéis do JSFiddle:**
- **HTML:** Use uma `<ul>` ou `<ol>` para a lista, uma `<input>` e um `<button>`.
- **CSS:** Estilize os itens da lista com margens e bordas.
- **JavaScript:** Utilize `document.createElement` para criar os itens da lista dinamicamente.

---

### Questão 5
**Adicione um botão para remover itens da lista.**

- Cada item adicionado deve ter um botão "Remover" ao lado.
- Quando o botão for clicado, o item correspondente deve ser excluído.

**Painéis do JSFiddle:**
- **HTML:** Crie os itens com botões "Remover" dinâmicos.
- **CSS:** Diferencie os estilos dos botões "Adicionar" e "Remover".
- **JavaScript:** Use `removeChild` para excluir o item da lista.

---

### Questão 6
**Adicione alternância de tema (claro/escuro).**

- Adicione um botão "Alterar Tema".
- Ao clicar, altere o tema da página entre claro e escuro.

**Painéis do JSFiddle:**
- **HTML:** Insira um botão "Alterar Tema".
- **CSS:** Crie duas classes (`.claro` e `.escuro`) com estilos diferentes.
- **JavaScript:** Use `classList.toggle()` para alternar as classes do `<body>`.

---

### Questão 7
**Crie uma barra de progresso que aumenta ao clicar em um botão.**

- Adicione um botão "Carregar".
- Cada clique no botão deve aumentar a largura da barra.

**Painéis do JSFiddle:**
- **HTML:** Crie um `<div>` para a barra e outro para o container.
- **CSS:** Estilize a barra com uma cor de fundo e largura inicial de 0.
- **JavaScript:** Use a propriedade `style.width` para aumentar a largura.

---

### Questão 8
**Adicione um cronômetro decrescente.**

- Adicione um botão "Iniciar".
- O cronômetro deve contar de 10 a 0, atualizando a cada segundo.

**Painéis do JSFiddle:**
- **HTML:** Crie um elemento para exibir o tempo e o botão.
- **CSS:** Centralize o cronômetro e o botão.
- **JavaScript:** Use `setInterval` para reduzir o valor do cronômetro e `clearInterval` para parar quando atingir 0.

---

### Questão 9
**Crie uma tabela interativa com dados dinâmicos.**

- Adicione uma tabela com colunas "Nome" e "Idade".
- Use uma caixa de texto e botão para inserir novos dados na tabela.

**Painéis do JSFiddle:**
- **HTML:** Insira uma `<table>` e um formulário com `<input>` e `<button>`.
- **CSS:** Estilize a tabela com bordas e alternância de cores nas linhas.
- **JavaScript:** Use `insertRow` e `insertCell` para adicionar dados dinamicamente.

---

### Questão 10
**Adicione validação ao formulário de cadastro.**

- Crie um formulário com campos "Nome", "Email" e "Senha".
- Valide:
  - Nome: Pelo menos 3 caracteres.
  - Email: Um endereço válido.
  - Senha: No mínimo 6 caracteres.

**Painéis do JSFiddle:**
- **HTML:** Crie um formulário com `<input>` e um botão "Enviar".
- **CSS:** Destaque os campos com erro usando `border-color: red`.
- **JavaScript:** Use `addEventListener` no evento `submit` e `preventDefault()` para impedir o envio até a validação passar.

---

**Boa sorte!**
