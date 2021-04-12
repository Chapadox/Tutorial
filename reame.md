## Introdução
<p>Nesse tutorial vamos aprender como criar um repositorio, e como subir os seus projetos no <strong>Github.</strong></p>

<p>Github e uma plataforma de <strong>armazenamento de codigo fonte e arquivos</strong>, muitos dizem também que o Github e uma rede social para devs. O Github também trabalha com controle de versão <strong><a href="https://git-scm.com">Git.</a></strong></p>

## Requisitos 

<p>Depois dessa breve introdução vamos de fato ao que interessa.</p>
<p>1- Antes de qualquer coisa e preciso que voce tenha uma conta ativa no Github, caso não tenha clique <a href="https://github.com/join">aqui</a></p>

<p>2- Instale o <strong><a href="https://git-scm.com">Git</a></strong> no seu computador, o Git suporta diversos sistemas operacionais.</p>

## Como instalar o Git 

<p>Abra o site do <strong><a href="https://git-scm.com">Git</a></strong> Depois clique em <strong>"Download 2.31.1 for Windows"</strong></p> 

![Git](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/kiwfz825kvk9i3agvd4x.png)

<br><p>Depois sera baixado um executavel, basta dar 2 cliques e ele sera aberto.</p>
<p>Depois disso e so basicamente dar <strong>Next</strong> em tudo, Ou se prefirir pode seguir esse <strong><a href="https://dicasdeprogramacao.com.br/como-instalar-o-git-no-windows/">Tutorial</a></strong> ele ensina passo a passo sobre a instalação do Git</p>

## Primeiros passos

<p>Na pasta do seu projeto abra um terminal. No <strong><a href="https://code.visualstudio.com/">Visual Studio Code</a></strong> pode se fazer isso utilizando o seguinte atalho <strong>Ctrl + Shift + P</strong></p> 
<p>Ira abrir um terminal como esse:</p>

![Terminal](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/i0ef60v8u2h3sj7gb9hn.png)


<p>Agora voce vera um menu drop-down no canto superior direito clique nele e selecione a seguinte opção <strong>New Git bash</strong> Clique nele para abrir o terminal integrado do Git.</p>


![Terminal](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/tviim64d6lkmmeclz5a2.png)

<p>Se voce ainda não estiver na pasta do seu projeto navegue ate la usando o comando <strong>cd "Diretorio"</strong> Sem as apas</p>

## Configurando o Git

<p>Agora vamos configurar o Git para podermos subir o nosso projeto</p>

<p>Ainda no Git bash digite <strong>git config --global user.name "Fulano"</strong>, Com esse comando estamos informando ao Git nosso username, voce pode colocar o nome de usuario utilizado no Github se preferir.</p>

<p>Agora digite <strong>git config --global user.email fulanodetal@exemplo.br</strong> isso informara para o git seu email, voce pode colocar o email utilizado no Github se preferir.</p>

<p>Exemplo</p>

    $ git config --global user.name "Eduardo"
    $ git config --global user.email tutorial@gmail.com

<p>Essa configuração e importante pois cada <strong>commit</strong> que fizermos essas informaçoes serão utilizadas e gravadas de forma imutavel nos <strong>commits</strong></p>

## Iniciando um repositorio

<p>Agora que ja instalamos o Git e configuramos vamos iniciar um <strong>Repositorio local</strong> Um repositorio local significa que vamos o <strong>controle de versões</strong> localmente.</p>

<p>Para iniciar um repositorio digite:</p>

    git init

<p>Depois desse comando sera criado uma diretorio oculto <strong>.git</strong> Nele sera armazenado todas as versões do seu projeto</p>

<p>Agora vamos adicionar todos os arquivos do projeto com o comando</p>

    git add .

<p>Isso fara que seu arquivos e diretorios sejam <strong>Rastreados</strong>. Agora vamos fazer um <strong>commit</strong>, Um commit server para fixarmos as mudanças no nosso projeto, ou seja se fizermos uma alteração que não deu certo podemos <strong>"voltar no tempo"</strong> e pegar um commit passado.</p>

<p>Para fazermos um commit utilizamos</p>