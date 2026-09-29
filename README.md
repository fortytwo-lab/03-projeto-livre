# 🔐 Verificador de Senhas Vazadas

Sistema desenvolvido pela **FortyTwo Lab** como Projeto Livre da disciplina
de Programação Orientada a Objetos.

A aplicação permitirá verificar se uma senha já apareceu em vazamentos de
dados conhecidos, utilizando o serviço **Pwned Passwords**, disponibilizado
pelo Have I Been Pwned.

---

## 🎯 Objetivo

Desenvolver uma aplicação Java capaz de receber uma senha informada pelo
usuário, realizar o processamento necessário de forma local e consultar
uma API para verificar se essa senha aparece em bases de senhas comprometidas.

Ao final da consulta, o sistema deverá informar quantas vezes a senha
consultada foi encontrada nos dados disponibilizados pelo serviço.

---

## ⚙️ Funcionamento Planejado

O fluxo básico da aplicação será:

```text
Usuário informa uma senha
        ↓
Aplicação calcula o hash da senha
        ↓
Consulta ao serviço Pwned Passwords
        ↓
Processamento da resposta
        ↓
Exibição do resultado
```

Exemplo de resultado:

```text
Senha encontrada em vazamentos!

Esta senha apareceu 12.345 vezes
em bases de dados comprometidas.
```

ou:

```text
A senha não foi encontrada
nos dados consultados.
```

---

## 🔒 Privacidade da Senha

A senha informada pelo usuário não deverá ser enviada diretamente
pela aplicação ao serviço externo.

O processamento será realizado utilizando o mecanismo disponibilizado
pela API Pwned Passwords, permitindo realizar a consulta sem transmitir
a senha original.

Esse aspecto também fará parte do estudo realizado durante o
desenvolvimento do projeto.

---

## ✨ Funcionalidades Planejadas

A aplicação deverá permitir:

- 🔑 Informar uma senha;
- 🔐 Processar a senha localmente;
- 🌐 Consultar a API Pwned Passwords;
- 🔎 Verificar a ocorrência da senha;
- 🔢 Informar quantas vezes ela apareceu nos dados consultados;
- ⚠️ Apresentar o resultado de forma compreensível ao usuário;
- 🖥️ Disponibilizar uma interface gráfica simples.

As funcionalidades poderão ser refinadas durante o desenvolvimento.

---

## 🛠️ Tecnologias

Durante o desenvolvimento serão utilizadas:

- ☕ Java
- 🖥️ Java Swing
- 🌐 API REST
- 🔐 SHA-1
- 🌿 Git
- 🐙 GitHub

---

## 📚 Conceitos Trabalhados

O projeto permitirá explorar conceitos como:

- Programação Orientada a Objetos;
- interface gráfica com Java Swing;
- consumo de APIs;
- requisições HTTP;
- processamento de respostas;
- funções hash;
- tratamento de erros;
- privacidade e segurança;
- Git e GitHub.

---

## 📂 Estrutura do Projeto

```text
03-projeto-livre/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── src/
│   └── Código-fonte da aplicação
│
├── resources/
│   ├── icons/
│   └── images/
│
├── docs/
│   ├── uml/
│   ├── ui-ux/
│   │   ├── wireframes/
│   │   ├── mockups/
│   │   └── prototypes/
│   ├── diagrams/
│   └── presentations/
│
└── support/
    ├── documents/
    ├── videos/
    ├── tutorials/
    └── references/
```

---

## 🎨 Planejamento da Interface

O processo de planejamento da interface será documentado em:

```text
docs/ui-ux/
├── wireframes/
├── mockups/
└── prototypes/
```

Esses artefatos registram o processo de concepção da interface e não
necessariamente representam a aparência final da aplicação.

---

## 🌐 API

O projeto utilizará o serviço **Pwned Passwords**, disponibilizado pelo
Have I Been Pwned.

A integração com a API será implementada durante o desenvolvimento
do projeto.

A senha original não deverá ser enviada diretamente para o serviço.

---

## 🌿 Fluxo de Desenvolvimento

O desenvolvimento será realizado utilizando branches específicas para
novas funcionalidades, correções e melhorias.

Fluxo utilizado pela equipe:

`Branch` → `Desenvolvimento` → `Commit` → `Push` → `Pull Request` → `Review` → `Merge`

A branch `main` deverá manter versões integradas e estáveis do projeto.

---

## 🏷️ Versionamento

A evolução do projeto será registrada por meio de commits,
branches e tags.

O histórico do repositório deverá permitir acompanhar desde o
planejamento inicial até a implementação e integração com a API.

---

## 👥 Equipe

| Integrante | Função |
|---|---|
| Roger Moura Sarmento | Founder / Developer |

---

## 🚀 Como executar

As instruções de compilação, configuração e execução serão adicionadas
conforme a evolução da aplicação.

---

## 📄 Licença

Este projeto é distribuído sob a licença MIT.

---

### 🌌 FortyTwo Lab

**Software, ideias e a resposta para quase tudo. 🚀**

> **DON'T PANIC!**
