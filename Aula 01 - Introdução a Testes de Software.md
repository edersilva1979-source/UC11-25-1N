# 🚀 Aula 1 – Introdução a Testes de Software

## 🎯 Objetivos da Aula

* Entender o que são **testes de software**.
* Compreender **por que testar é importante**.
* Conhecer os **benefícios dos testes** no ciclo de desenvolvimento.
* Diferenciar **tipos básicos de testes**.
* Ter um **primeiro contato com artefatos de teste** (documentos, casos, relatórios).

---

## 🧩 O que são Testes de Software?

👉 Testar software é o processo de **verificar se o sistema funciona como deveria** e **garantir qualidade** antes que chegue ao usuário final.

💡 Analogia:
Pensa num carro 🚗. Antes de lançar no mercado, a montadora testa:

* O motor funciona bem?
* Os freios seguram?
* O ar condicionado gela?

No software é igual: antes de “entregar para rodar na rua”, precisamos validar que tudo está ok.

---

## 🤔 Por que precisamos de Testes?

* **Encontrar erros cedo** 🐛 → corrigir depois é mais caro.
* **Garantir qualidade** ⭐ → software mais confiável.
* **Melhorar a experiência do usuário** 👩‍💻.
* **Facilitar manutenção** 🔧 → código mais previsível.

📉 Sem testes → bugs em produção → prejuízo, frustração do usuário, perda de confiança.

---

## 📂 Documentos e Artefatos de Teste

Além do código, criamos **documentos auxiliares** que ajudam a organizar os testes:

* **Plano de Teste** 📑 → descreve **o que será testado, como e quando**.
* **Casos de Teste** 📝 → passo a passo para validar uma funcionalidade.
* **Relatórios de Teste** 📊 → registram o que foi testado e os resultados.

💡 Exemplo simples de **Caso de Teste** (login):

* **Objetivo:** Validar login com credenciais corretas.
* **Passos:**

  1. Acessar tela de login.
  2. Inserir usuário válido.
  3. Inserir senha válida.
  4. Clicar em "Entrar".
* **Resultado esperado:** Usuário acessa o sistema.

---

## 🧪 Tipos de Testes (Visão Geral)

Na prática, existem vários tipos de testes. Vamos só dar uma passada rápida hoje (os detalhes ficam para próximas aulas):

* **Testes de Unidade** 🔬 → validam **pequenas partes do código**, como funções e métodos.
* **Testes de Integração** 🔗 → checam se **módulos diferentes trabalham bem juntos**.
* **Testes Funcionais** ⚙️ → validam **se o sistema atende aos requisitos**.
* **Testes de Caixa Branca** 📖 → olham para dentro do código (estrutura).
* **Testes de Caixa Preta** 🕵️ → olham só o comportamento externo (entrada/saída).

---

## 📌 Recapitulando

* Testar = garantir qualidade e reduzir riscos.
* Documentos de teste ajudam a organizar o processo.
* Já existem diferentes tipos de teste, mas hoje só conhecemos a visão geral.

---

## 🏠 Atividade para Fixar

📌 Imagine que você está testando um **aplicativo de delivery** 📱🍕.

1. Crie **um caso de teste simples** para verificar o cadastro de usuário.
2. Defina **o resultado esperado**.
