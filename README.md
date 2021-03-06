# Projeto app-model 📱 💻 🖥️ 🎅

>Este projeto será um modelo de aplicação

Objetivo é a utilização do mesmo em outros projetos

## Histórico de alterações

### 001 - Preparação do ambiente 

- Criação de pastas auxiliares que não aparecerão no github.
    - database (onde ficará um backup do banco de dados)
    - documents 
        - Kick Off (início do projeto, atribuições e o esperado do projeto) 
        - Busines case (objetivo, necessidades, previsões de entregas)
        - Proposta (orçamento para o cliente)
        - Especificação de requisitos (todos requisitos funcionais e designer)
        - Criação do Projeto (Passos para criação do projeto)
    - tests (para testes ocasionais)

- Criação de pastas para padrão MVC
    - service (onde ficarão as classes de serviço)
    - shared (comuns a todos os projetos)
      - scripts (comandos para o servidor)
      - styles (estilos para o frontend)
      - views (compartilhadas na aplicação)
    - source (onde ficará o código fonte)
        - App ou pasta Controller (onde ficarão as classes de controle)
        - Boot (arquivos de inicialização) 
            - Arquivos Config.php e Helpers.php (com configurações e funções auxiliares)
            - Pasta do Minify (responsável pela minificação dos arquivos)
        - Core (onde ficarão as classes padrão nos sistemas)
            - Controller.php (classes de controle)
            - Model.php (classes de modelo)
            - View.php (classes de visão)
            - Connection.php (classes de conexão)
            - Session.php (classes de sessão)
        - Models (onde ficarão as classes de modelo)
        - Support (onde ficarão as classes de suporte)
            - Email.php (classes de envio de e-mails) - [PHPMailer](https://github.com/PHPMailer/PHPMailer)
            - Message.php (classes de mensagens do sistema)
            - Pager.php (classes de paginação) - [paginator](https://packagist.org/packages/coffeecode/paginator)
            - Seo.php (classes de SEO) - [optimizer](https://packagist.org/packages/coffeecode/optimizer)
            - Thumb.php (classes de manipulação de imagens) - [cropper](https://packagist.org/packages/coffeecode/cropper)
            - Upload.php (classes de upload de arquivos) - [uploader](https://packagist.org/packages/coffeecode/uploader)
    - storage (onde ficam os arquivos de armazenamento)
        - files (onde ficam os arquivos enviados)
        - images (onde ficam as imagens)
        - medias (onde ficam as mídias)
    - themes (onde ficam os temas utilizados pelo sistema) 
    - vendor (onde ficam os pacotes de terceiros) * não carregado no github
- Criação dos arquivos na raiz
    - .htaccess (para configurações do servidor Apache)
    - composer.json (para configurações do composer)
    - index.php (para inicialização do projeto)

## Instalação

### Pré requisitos

- [WampServer](https://www.wampserver.com/en/)  - Para quem for trabalhar em localhost
- PHP >=^7.4.9 <8.0.0
- MySQL >=5.7.31
- [Composer](https://getcomposer.org/) - Para a criação do autoload
- [PHPMailer](https://github.com/PHPMailer/PHPMailer) - Para envio de emails
- [paginator](https://packagist.org/packages/coffeecode/paginator)
- [optimizer](https://packagist.org/packages/coffeecode/optimizer)
- [cropper](https://packagist.org/packages/coffeecode/cropper)
- [uploader](https://packagist.org/packages/coffeecode/uploader)
- [minify](https://packagist.org/packages/matthiasmullie/minify)
- [tinymce](https://www.tinymce.com/) - Editor de textos
- [Bootstrap](https://getbootstrap.com/) - para o CSS
- [jQuery](https://jquery.com/) - para algumas funções que serão utilizadas
- [Font Awesome](https://fontawesome.com/) - para deixar mais leve os ícones da aplicação

### Webservice de terceiros
- [ViaCEP](https://viacep.com.br/) - será utilizado para consulta de CEPs

## Software utilizado
- Visual Studio Code
- Notepad++

## Crédito

- Antonio Carlos Doná - [acdona](https://guithub.com/acdona)

### Agradecimentos
Agradeço à Microsoft, por disponibilizar gratuitamente, esse sensacional software o [**Visual Studio Code**](https://code.visualstudio.com/).

## Licença
Software de código fonte aberto licenciado conforme à [MIT](https://choosealicense.com/licenses/mit/)
