# 🚀 Oficina Flutter — Minha Primeira Aplicação em Flutter

> Repositório oficial da oficina **"Minha Primeira Aplicação em Flutter"**, ministrada por **Mayara Vieira**.  
> Nesta oficina de 2 horas, vamos aprender a configurar o ambiente Flutter no Windows, entender a estrutura de um projeto, conhecer a linguagem **Dart**, e criar juntos nosso primeiro app rodando na web! 💙

---

## 🧭 Estrutura da Oficina

**⏱ Duração:** 2 horas  
**💻 Formato:** Prática guiada (sem slides)  
**📚 Materiais:**
- [ ] Notion com exemplos de código e explicações teóricas (widgets, sintaxe Dart etc.)  
- [ ] Este repositório com o passo a passo de instalação e execução do projeto  

---

## 🎯 Objetivos

### Objetivo geral
Apresentar os fundamentos do Flutter e Dart, guiando o participante na criação de sua primeira aplicação.

### Objetivos específicos
- Configurar o ambiente Flutter no Windows  
- Entender a estrutura de um projeto Flutter  
- Executar o famoso *Hello World*  
- Conhecer os principais widgets e conceitos do Flutter  
- Explorar brevemente a linguagem Dart  

---

## ⚙️ Configuração do Ambiente (Windows)

> Siga os passos abaixo com calma para configurar tudo antes ou durante a oficina 👇  

---

### 🧩 1. Instalar o Git

Baixe e instale o Git pelo site oficial:  
🔗 [https://git-scm.com/downloads](https://git-scm.com/downloads)

Durante a instalação, mantenha as opções padrão.  
Após instalado, verifique se está tudo certo:

```bash
git --version

🪄 2. Baixar o Flutter SDK

Baixe o SDK do Flutter para Windows:
🔗 https://flutter.dev/docs/get-started/install/windows

Depois de baixar, extraia o arquivo .zip em um diretório fácil, por exemplo:

C:\src\flutter

⚙️ 3. Adicionar o Flutter ao PATH

    No menu iniciar, procure por Editar variáveis de ambiente do sistema.

    Clique em Variáveis de ambiente....

    Em Variáveis do sistema, encontre e edite a variável Path.

    Clique em Novo e adicione o caminho:

    C:\src\flutter\bin

    Salve e feche.

Teste se funcionou:

flutter --version

🩺 4. Verificar o ambiente

Execute o comando:

flutter doctor

Ele mostrará o status da sua instalação.
Os avisos sobre Android Studio podem ser ignorados se você for usar o navegador (Chrome).
🧱 5. Criar e rodar o projeto Flutter

Dentro da pasta onde deseja criar o projeto, execute:

flutter create oficina_flutter
cd oficina_flutter
flutter run -d chrome

Após isso, o app abrirá no navegador com o texto padrão:

Flutter Demo Home Page

✨ Parabéns! Você acabou de rodar seu primeiro app Flutter!
🗂️ Estrutura do Projeto Flutter

A estrutura básica de um projeto Flutter é assim:

lib/
  └── main.dart        → Ponto inicial do app
android/               → Arquivos para build no Android
ios/                   → Arquivos para build no iOS
web/                   → Build para rodar no navegador
pubspec.yaml           → Dependências do projeto

Durante a oficina, vamos entender cada parte dessa estrutura e modificar o arquivo main.dart.
💡 Próximos Passos

Após configurar o ambiente:

    Acesse o Notion com o conteúdo da oficina (link será adicionado em breve)

    Copie o código de exemplo e execute no projeto.

    Explore o que são widgets, estados e o hot reload do Flutter.

## 🧑‍💻 Tecnologias Utilizadas

| 🛠️ Ferramenta | 💡 Função |
|----------------|-----------|
| [**Flutter**](https://flutter.dev/) | Framework para criação de apps multiplataforma |
| [**Dart**](https://dart.dev/) | Linguagem de programação usada pelo Flutter |
| [**Git**](https://git-scm.com/) | Controle de versão |
| [**Visual Studio Code**](https://code.visualstudio.com/) | Editor de código recomendado |

---

> 📄 Este repositório é de uso **educacional e livre** para reuso com atribuição.

> 💻 Se quiser testar o Flutter sem instalar nada, use o ambiente online do **DartPad**:  
> 🔗 [https://dartpad.dev/](https://dartpad.dev/)

