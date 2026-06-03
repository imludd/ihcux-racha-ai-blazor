# 💰 RachaAí - Dashboard de Finanças Coletivas

## 👩‍💻 Identificação

**Nome:** Ludmilla Santos
**Curso:** Ciência da Computação
**Instituição:** Centro Universitário UNA

---

## 📖 Sobre o Projeto

O RachaAí é uma aplicação desenvolvida em Blazor para auxiliar usuários no gerenciamento de despesas compartilhadas. Nesta atividade foi criada uma página Dashboard responsável por apresentar informações financeiras de forma clara e intuitiva, aplicando conceitos de Interação Humano-Computador (IHC) e Experiência do Usuário (UX).

---

## 🛠️ Tecnologias Utilizadas

* Blazor
* C#
* .NET
* Bootstrap

---

## 📸 Screenshot

Adicionar abaixo uma imagem da aplicação em execução.

```markdown
![Dashboard RachaAí](./screenshot.png)
```

---

## 🎨 Implementação Blazor

A hierarquia visual criada no Miro foi transformada em componentes Blazor utilizando o sistema de Grid do Bootstrap para organizar os elementos da interface.

Os cards de resumo foram posicionados no topo da página para destacar as informações mais importantes: Total a Receber, Total a Pagar e Saldo Geral. Logo abaixo foi implementada a listagem dos grupos ativos utilizando o componente reutilizável `GrupoCard`, facilitando a manutenção e organização do código.

O botão de ação rápida "Adicionar Novo Gasto" foi destacado visualmente para facilitar sua identificação pelo usuário.

---

## 🧩 Componentização

Foi criado o componente `GrupoCard.razor`, responsável por exibir:

* Nome do grupo;
* Categoria;
* Valor formatado em Real (R$);
* Indicação visual utilizando cores para representar créditos ou débitos.

Essa abordagem permite reutilizar o mesmo componente para diferentes grupos sem duplicação de código.

---

## ⚙️ Dificuldade Técnica

O maior desafio foi componentizar o `GrupoCard`, definindo parâmetros que permitissem reutilizar o componente para diferentes grupos mantendo a mesma estrutura visual. Também foi necessário tratar a exibição dinâmica das cores para indicar valores positivos e negativos de forma intuitiva ao usuário.

---

## 📚 Conceitos de UX Aplicados

* Visibilidade do Status do Sistema;
* Hierarquia Visual;
* Consistência Visual;
* Affordance em botões de ação;
* Tratamento amigável para listas vazias;
* Responsividade utilizando Bootstrap.
