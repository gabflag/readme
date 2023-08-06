## Guia para Baixar e Executar Projetos no GitHub

Bem-vindo ao guia passo a passo para baixar e executar projetos do GitHub em sua máquina. Não se assuste com a quantidade de linhas desse readme, a ideia é que qualquer pessoa possa segui-lo. Este guia foi criado para pessoas com pouca experiência técnica ou apenas com suporte para quem gosta de passos-a-passos, portanto, siga os passos com atenção para ter sucesso em executar qualquer projeto de forma tranquila 😁

1️⃣Passo 1: Instalação do Git
Baixe e Instale o Git: Primeiro, você precisará instalar o Git em sua máquina. O Git é uma ferramenta que permite clonar e colaborar em projetos do GitHub. Baixe a versão apropriada para o seu sistema operacional em git-scm.com (https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Instalando-o-Git) e siga as instruções de instalação.

2️⃣ Passo 2: Clonando um Repositório
Temos duas formas de fazer isso de forma bem fácil e sem complicações, via CLI ou via interface gráfica:

- Via CLI:
  
    Encontre o Repositório: Acesse o repositório do projeto no GitHub, que você deseja baixar e executar.
    Copie o URL: No canto superior direito do repositório, clique no botão "Code" e copie o URL exibido.
  ![image](https://github.com/gabflag/readme/assets/95552879/5688d1aa-d297-4800-b851-2c4ef4dbe648)

  Abra o Terminal: No seu computador, abra o terminal ou prompt de comando. No Windows, você pode usar o "Prompt de Comando" ou o "PowerShell".

  Navegue para a Pasta: Use o comando cd para navegar até a pasta onde deseja armazenar o projeto. Por exemplo, para ir para a área de trabalho:

      cd Área\de\Trabalho

  Clone o Repositório: Use o comando git clone seguido do URL que você copiou anteriormente. Cole o URL após o comando e pressione Enter.
  Ficaria algo parecido com isso:

       git clone https://github.com/gabflag/code_done.git

  Agora você já tem os arquivos do repositório pronto para uso 🎉


- Via Interface gráfica (GUI):

  Encontre o Repositório: Acesse o repositório do projeto no GitHub, que você deseja baixar e executar.
  Faça o download do arquivo .ZIP
![image](https://github.com/gabflag/readme/assets/95552879/f444a471-d19f-4660-8129-f17d4b990fa1)

  Feito o download agora é só descomprimir os arquivos na pasta que você deseja. Caso não saiba como descomprimir um arquivo recomendo utilizar o programa 7zip
  (https://www.7-zip.org/)

3️⃣ Passo 3: Executando o Projeto

  Navegue até a Pasta do Projeto: Use o comando cd novamente para entrar na pasta do projeto que você acabou de clonar.
  
    cd NOME_DO_PROJETO
  
  Siga as Instruções: Dentro do repositório, leia o arquivo README.md. O README fornecerá detalhes sobre como configurar e executar o projeto. Ele também pode conter informações sobre dependências específicas que você precisa instalar.

4️⃣ Passo 4: Contribuindo (Opcional - Avançado)

  Criando um Branch: Se você quiser contribuir com o projeto, é uma boa prática criar um novo branch para suas alterações. Use o comando abaixo para criar um novo branch e trocar para ele:
    
    git checkout -b meu-novo-recurso
    Faça Suas Alterações: Faça as alterações desejadas no projeto usando seu editor de código favorito.

  Commit e Push: Após fazer suas alterações, use os comandos abaixo para salvar suas alterações localmente e enviá-las para o GitHub:
  
    git add .
    git commit -m "Adicionando novo recurso"
    git push origin meu-novo-recurso
    
  Crie um Pull Request: No repositório no GitHub, você verá um botão "Pull Request". Clique nele para iniciar uma solicitação de pull, descrevendo suas alterações. Os mantenedores do projeto revisarão suas alterações e, se tudo estiver certo, as mesclarão ao projeto principal.

# Conclusão

Agora você tem o conhecimento necessário para baixar, executar e até mesmo contribuir com projetos no GitHub. Lembre-se de sempre ler o README.md do projeto para obter instruções específicas. Divirta-se explorando projetos interessantes e aprendendo mais sobre programação! Se tiver dúvidas, consulte a documentação oficial do Git e do GitHub ou peça ajuda na comunidade.
