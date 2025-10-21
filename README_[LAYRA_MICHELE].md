# 📚Gerencioteca

Um **sistema completo** para o gerenciamento de uma biblioteca escolar, permitindo o **cadastro de livros, alunos, empréstimos e devoluções**.  
Seu objetivo é **automatizar** e **otimizar** o controle de acervo e circulação de exemplares, facilitando o trabalho de bibliotecários e professores.

## 🧭 Índice
- 📘 Visão Geral (##-visão-geral)
- ⚙️ Funcionalidades (##️-funcionalidades)
- 💻 Tecnologias (##-tecnologias)
- 🚀 Como Usar (##-como-usar)
- 🧩 Próximas Atualizações (##-próximas-atualizações)
- 👥 Contribuidores (##-contribuidores)
- 📞 Contato (##-contato)

## 📘 Visão Geral

O **Sistema de Gerenciamento de Biblioteca Escolar** foi desenvolvido para instituições de ensino que desejam modernizar o controle de seus acervos.  
Com interface intuitiva e funcionalidades automatizadas, o sistema proporciona **rapidez**, **segurança** e **eficiência** nas operações diárias.

## ⚙️ Funcionalidades

- Cadastro de livros (título, autor, ISBN, categoria, quantidade)
- Cadastro de alunos e funcionários
- Registro de empréstimos e devoluções
- Controle de prazos e notificações automáticas
- Relatórios estatísticos de uso da biblioteca
- Sistema de login e autenticação
- Pesquisa avançada de exemplares

## 💻 Tecnologias

| Categoria                    | Tecnologia Utilizada        |
|------------------------------|-----------------------------|
| **Linguagem de Programação** | Python (Flask)              |
| **Banco de Dados**           | MySQL                       |
| **Estrutura**                | MVC (Model-View-Controller) |
| **Sistema Operacional**      | Ubuntu 22.04 LTS            |

## 🚀 Como Usar

1. **Clone** este repositório:
   
   git clone https://github.com/seu-usuario/sistema-biblioteca.git

2. **Acesse** a pasta do projeto:

cd sistema-biblioteca

3. **Instale** as dependências:

pip install -r requirements.txt

4. **Configure** o banco de dados (arquivo .env)

5. **Execute** o servidor:

python app.py

6. **Acesse** o sistema no navegador:

http://localhost:5000

### 💡Exemplo: Registro de um novo livro
novo_livro = Livro(titulo="Dom Casmurro", autor="Machado de Assis", isbn="123456789", categoria="Romance")
db.session.add(novo_livro)
db.session.commit()
print("📘 Livro cadastrado com sucesso!")

"Objetivos do Projeto"
Criar uma solução digital que simplifique o gerenciamento de acervos escolares, promova o uso consciente de recursos e incentive a leitura entre os alunos.
O sistema busca unir tecnologia e educação de forma acessível e sustentável.

### 🧩 Próximas Atualizações

- ✅Cadastro de livros

- ✅Sistema de login

- 🟥Integração com biblioteca digital

- 🟥Módulo de recomendação de leitura

- 🟥Relatórios em PDF

### 🔗Repositórios Relacionados
https://github.com/devchallenge-io/biblioteca-backend.git
https://github.com/paulojp-dev/projeto-biblioteca-java.git

## 👥 Contribuidores

Agradecimentos especiais aos desenvolvedores e colaboradores deste projeto:

@usuario1 — Desenvolvedor Backend
@usuario2 — Designer de Interface
@usuario3 — Gerente de Projeto
___________________________________________________________________________________________________________________________________________________________________________

## 📞 Contato

📧 Email: contato\gerencioteca@escola.com
🌐 Site: www.gerencioteca.com
💬 LinkedIn: linkedin.com/in/gerencioteca
