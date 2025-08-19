
# 👋 Bem-vindos à Organização de Engenharia de Software

![Curso](https://img.shields.io/badge/Curso-Engenharia%20de%20Software-green)  
![Status](https://img.shields.io/badge/Status-Em%20Andamento-yellow)  
![GitHub](https://img.shields.io/badge/GitHub-Classroom-blue)  

---

## 📚 Sumário

- [🏛️ Sobre a Organização](#️-sobre-a-organização)  
- [📁 Regras de Uso do Repositório](#-regras-de-uso-do-repositório)  
  - [1. Criação de Branches](#1-criação-de-branches)  
  - [2. Organização dos Arquivos](#2-organização-dos-arquivos)  
- [📂 Repositórios por Disciplina](#-repositórios-por-disciplina)  
- [🔧 Tutorial: Como Subir Seus Projetos Usando Git](#-tutorial-como-subir-seus-projetos-usando-git)  
- [🔗 Links Úteis](#-links-úteis)  
- [📫 Dúvidas ou Sugestões](#-dúvidas-ou-sugestões)  

---

## 🏛️ Sobre a Organização

Esta organização foi criada para concentrar todos os **projetos, atividades e exemplos práticos** das disciplinas do curso de **Engenharia de Software**.  

Aqui os alunos encontrarão repositórios com:  

- Exemplos de **Arquitetura de Software** (Layered, MVC, MVVM, Hexagonal, Microsserviços, etc.)  
- Exercícios práticos de **Design Patterns**  
- Projetos de **Sistemas Distribuídos** e **Microsserviços**  
- Atividades de **Mineração de Dados** com **Python e Pandas**  
- Estudos de casos integrados em diferentes tecnologias (Java, TypeScript, Python, C++ etc.)  

O objetivo é fornecer um **ambiente colaborativo e centralizado**, onde cada turma pode versionar seus trabalhos, acompanhar boas práticas e compartilhar conhecimento.  

---

## 📁 Regras de Uso do Repositório

### 1. Criação de Branches

Cada aluno deve criar sua branch com o seguinte padrão:  

```
feature/SEU_NOME_EM_MAIUSCULAS_SEPARADO_POR_UNDERSCORE
```

Exemplo:

```
feature/JOAO_SILVA
```

---

### 2. Organização dos Arquivos

Dentro da sua branch, crie uma pasta com seu nome:  

```
JOAO_SILVA/
```

E organize suas atividades da seguinte forma:  

```
JOAO_SILVA/
 ├── atividade1/
 ├── atividade2/
 └── readme.md
```

---

## 📂 Repositórios por Disciplina

Abaixo estão alguns dos repositórios disponíveis nesta organização:

### 📐 Arquitetura de Software
- `layered-arch-examples` → exemplos de arquitetura em camadas  
- `mvc-arch-examples` → exemplos com MVC  
- `mvvm-arch-examples` → exemplos com MVVM  
- `hexagonal-arch-example` → exemplo de arquitetura hexagonal (Ports & Adapters)
- 
### ⚙️ Microsserviços
- `order-microservice`  
- `notification-microservice`  
- `inventory-microservice`  

### 📊 Mineração de Dados
- `pandarizando` → exemplos com **Python e Pandas**  

### 🌐 Programação WEB
- `projeto-web-api`    


### 🎨 Repositórios de trabalhos dos alunos
- `design-patterns-T02N` → trabalhos da turma T02N - 2025 (1º Sem)  
- `design-patterns-T03N` → trabalhos da turma T03N - 2025 (1º Sem)
- `design-patterns-T04N` → trabalhos da turma T04N - 2025 (1º Sem)
- `T01N-arquitetura-de-software` → trabalhos da turma T01N - 2025 (2º Sem)

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

- [Portal do curso de Engenharia de Software da FAG](https://www.fag.edu.br/engenharia-software)  
- [DevMedia – Arquitetura: introdução, camadas e concorrência](https://www.devmedia.com.br/arquitetura-de-software-introducao-camadas-e-concorrencia/26124)  
- [Gran Cursos Online – Arquiteturas de Software: fundamentos](https://blog.grancursosonline.com.br/arquiteturas-de-software-fundamentos/)  
- [SoftDesign – Os 10 tipos de arquitetura e melhores práticas](https://www.softdesign.com.br/blog/desenvolvimento-ou-consultoria-em-arquitetura-de-software-como-escolher/)  

---

## 📫 Dúvidas ou Sugestões

Entre em contato com o professor pelo e-mail:  
📧 **lucasmartins@fag.edu.br**  

Bons estudos! 🚀
