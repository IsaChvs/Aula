O GitHub é uma plataforma que oferece serviços de hospedagem para projetos código-fonte amplamente utilizado por desenvolvedores e equipes de desenvolvimento para colaborar em projetos de sotfware. Na aula aprendemos a usar o github, desde a configuração inicial até a criação de um repositório. Aqui está um guia passo a passo sobre como começar a usar o GitHub:

- Crie uma conta gratuita, preenchendo nome de usuário, endereço de e-mail e criar uma senha.
- Faça o download do Git e instale-o no seu computador.
- No canto superior direito, clique no ícone + e selecione "New repository".
- Preencha o nome do repositório, adicione uma descrição (opcional) e escolha se o repositório será público ou privado.
- Clique em "Create repository"
- Ao criar um novo repositório no GitHub, você pode marcar a opção para adicionar um arquivo README automaticamente. Se você já tiver um repositório existente, pode adicionar um novo arquivo README.md diretamente no GitHub ou localmente.

Adicionar um README.md no Github:
- Vá para o repositório no GitHub
- Clique em "Add file" e selecione "Create new file".
- Nomeie o arquivo como README.md
- Adicione o conteúdo desejado no editor.
- Comite as mudanças clicando em "commit new file".
  
Adicionar um README.md localmente:
- Navegue até o diretório do seu repositório local.
- Crie um novo arquivo chamado README.md.
  (touch README.md)
- Edite o arquivo com seu editor de texto ou IDE.
- Adicione o arquivo ao Git
  (git add README.md)
- Faça o commit e o push das alterações
  (git commit -m "Add README.md"
   git push origin main)


As principais funcionalidades do GitHub:
  
- O arquivo README é a primeira coisa que as pessoas veem ao visitar o repositório. Ele deve conter informações sobre o projeto, como instalar e usar o software.
- Para trabalhar em um projeto localmente, clone o repositório para o seu computador.
- Para contribuir em um projeto que você não possui acesso direto, faça um fonk do repositório. Isso cria uma cópia do repositório no seu perfil GitHub.
- Para sugerir mudanças em um repositório, faça um pull request.


No GitHub, o Markdown é amplamente utilizado em arquivos README.md, issues, pull requets, e wikis. Aqui está um guia básico de como usar Markdown no GitHub:
- Use # para criar cabeçalhos. O número de # determina o nível do cabeçalho.
- Para texto em negrito envolva-o com dois asteriscos ** ou dois underlines __.
  (**Texto em negrito**)
- Para texto em itálico envolva-o com um asterisco * ou um underline _.
  (*Texto em itálico*)
- Para listas não ordenadas use asteriscos *, sinais de adição +, ou hífens -.
- Para listas ordenadas use números seguidos por um ponto.
- Links: Use colchetes [] para o texto do link e parênteses () para URL.
- Imagens: Similar aos links, mas com um ponto de exclamação ! antes.
- Código em linha use crases `.
- Use três crases ``` para criar blocos de código. Pode-se especificar a linguagem para destaque de sintaxe.
  ```python
def hello_world():
    print("Hello, World!")










  
