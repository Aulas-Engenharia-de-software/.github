# 👋 Bem-vindos à Disciplina de Arquitetura de Software

![Disciplina](https://img.shields.io/badge/Disciplina-Arquitetura%20de%20Software-blue)
![Curso](https://img.shields.io/badge/Curso-Engenharia%20de%20Software-green)
![Status](https://img.shields.io/badge/Status-Em%20Andamento-yellow)

---

## 📚 Sumário

- [🏛️ Sobre a Disciplina de Arquitetura de Software](#️-sobre-a-disciplina-de-arquitetura-de-software)
- [📁 Regras de Uso do Repositório](#-regras-de-uso-do-repositório)
  - [1. Criação de Features](#1-criação-de-features)
  - [2. Organização dos Arquivos](#2-organização-dos-arquivos)
- [🔧 Tutorial: Como Subir Seus Projetos Usando Git](#-tutorial-como-subir-seus-projetos-usando-git)
- [🔗 Links Úteis](#-links-úteis)
- [📫 Dúvidas ou sugestões](#-dúvidas-ou-sugestões)

---

## 🏛️ Sobre a Disciplina de Arquitetura de Software

A disciplina de **Arquitetura de Software** tem como objetivo preparar os alunos para projetar sistemas robustos, escaláveis e de fácil manutenção, utilizando os principais estilos e padrões arquiteturais aplicados na indústria de software.

Durante a disciplina, estudaremos os seguintes conteúdos:

- Conceitos fundamentais de arquitetura de software  
- Diferença entre arquitetura e design de software  
- Padrões arquiteturais clássicos:  
  - Layered Architecture (Arquitetura em Camadas)  
  - MVC (Model-View-Controller)  
  - MVVM (Model-View-ViewModel)  
  - CQRS (Command and Query Responsibility Segregation)
- Arquiteturas orientadas a domínio:  
  - Onion Architecture  
  - Hexagonal Architecture (Ports and Adapters)  
- Arquiteturas modernas e distribuídas:  
  - Microsserviços  
  - SOA (Service-Oriented Architecture)  
  - Sistemas baseados em eventos  
- Princípios de design de software:  
  - SOLID  
  - DRY (Don't Repeat Yourself)  
  - KISS (Keep It Simple, Stupid)  
  - GRASP  
- Design Patterns aplicados à arquitetura:  
  - Singleton  
  - Strategy  
  - Observer  
  - Decorator  
  - Adapter  
  - Factory Method  
  - State  
- Documentação e boas práticas arquiteturais  
- Avaliação e trade-offs arquiteturais  

---

## 📁 Regras de Uso do Repositório

### 1. Criação de Features

Crie uma branch com o seguinte padrão:

```
feature/SEU_NOME_EM_MAIUSCULAS_SEPARADO_POR_UNDERSCORE
```

Exemplo:

```
feature/JOAO_SILVA
```

### 2. Organização dos Arquivos

Dentro da sua branch, crie uma pasta com seu nome, seguindo o padrão:

```
JOAO_SILVA/
```

Todo o seu código deve ficar dentro dessa pasta.  
**O nome da pasta deve seguir o padrão com seu nome em maiúsculas e underscore, mas não precisa ser igual ao nome da branch.**

Exemplo de estrutura:

```
feature/JOAO_SILVA/
└── JOAO_SILVA/
    ├── atividade1/
    ├── atividade2/
    └── readme.md
```

---

## 🔧 Tutorial: Como Subir Seus Projetos Usando Git

### Passo 1: Clonar o repositório principal

```bash
git clone https://github.com/Aulas-Engenharia-de-software/NOME_DO_REPOSITORIO.git
cd NOME_DO_REPOSITORIO
```

### Passo 2: Criar uma nova branch com seu nome

```bash
git checkout -b feature/SEU_NOME_EM_MAIUSCULAS_SEPARADO_POR_UNDERSCORE
```

Exemplo:

```bash
git checkout -b feature/JOAO_SILVA
```

### Passo 3: Criar sua pasta de trabalho

```bash
mkdir JOAO_SILVA
```

Coloque dentro dela todos os arquivos e atividades que você desenvolver.

### Passo 4: Adicionar, commit e enviar alterações

```bash
git add .
git commit -m "Adicionando minhas atividades iniciais"
git push origin feature/JOAO_SILVA
```

### Passo 5: Criar um Pull Request (PR)

1. Acesse o repositório no GitHub.
2. Clique em "Compare & pull request" (aparecerá automaticamente após o push).
3. Adicione uma descrição do que foi feito.
4. Clique em **"Create pull request"**.
5. Envie o Link do Pull Request como comentário particular no classroom da atividade.
   
---

## 🔗 Links Úteis

- <a href="https://www.fag.edu.br/engenharia-software" target="_blank">Portal do curso de engenharia de software da FAG</a>  
- <a href="https://www.devmedia.com.br/arquitetura-de-software-introducao-camadas-e-concorrencia/26124" target="_blank">DevMedia – Arquitetura: introdução, camadas e concorrência</a>
- <a href="https://blog.grancursosonline.com.br/arquiteturas-de-software-fundamentos/" target="_blank">Gran Cursos Online – Arquiteturas de Software: fundamentos</a>
- <a href="https://www.softdesign.com.br/blog/desenvolvimento-ou-consultoria-em-arquitetura-de-software-como-escolher/" target="_blank">SoftDesign – Os 10 tipos de arquitetura e melhores práticas</a>

---

## 📫 Dúvidas ou sugestões

Entre em contato com o professor pelo e-mail:  
📧 **lucasmartins@fag.edu.br**

Bons estudos! 🚀
