<!DOCTYPE html>
<html>
  <head>
     <meta charset="UTF-8">
  </head>
  <body>
    <h1 align = "center">Projeto Fórum</h1>
    <hr>
    <h3>Acesso ao Sistema:</h3>
    <p>https://replit.com/@MarcosAniCury/StackOverflow-by-me#Main.java</p>
    <hr>
    <h3>Equipe:</h3>
    <ul>
      <li>Danniel Henrique Correa Vieira</li>
      <li>Letícia Americano Lucas</li>
      <li>Marcos Any Cury Vinagre Silva</li>
    </ul>
    <hr>
    <h3>Projeto:</h3>
    <ul>
      <li>Main.java: Classe Main, classe principal do projeto ao qual todo o sistema gira em torno.
      <li>Diretório CRUD:</li>
      <ul>
        <li>CRUD.java: Classe CRUD, no qual faz todo o gerênciamento de acesso aos bancos de dados.
        <li>Registro.java: Interface que apresenta os métodos que os objetos a serem incluídos no CRUD devem conter.
      </ul>
      <li>Diretório arvoreBPlus:
      <ul>
        <li>ArvoreBMais_ChaveComposta_Int_Int.java: Contém o par de chaves idUsuario e idPergunta, e facilita na busca por perguntas de um mesmo usuário.
      </ul>
      <li>Diretório dados:
      <ul>
        <li>arvore_pergunta_respostas.db: Contém os dados que associa perguntas às respostas dela.
        <li>arvore_usuario_pergunta.db: Contém os dados que associa usuário às perguntas dela.
        <li>arvore_usuario_resposta.db: Contém os dados que associa usuário às respostas dela.
        <li>arvore_voto_pergunta.db: Contém os dados que associa votos às perguntas dela, tendo como principal objetivo gravar votos de usuário em pergunta.
        <li>arvore_usuario_resposta.db: Contém os dados que associa usuário às respostas dela.
        <li>arvore_voto_pergunta.db: Contém os dados que associa votos às perguntas dela, tendo como principal objetivo gravar votos de usuário em pergunta.
        <li>arvore_voto_resposta.db: Contém os dados que associa votos às respostas dela, tendo como principal objetivo gravar votos de usuário em respostas.
        <li>email_hash_c.db: Contém os dados gerados que foram armazenados em memória secundária sobre a tabela hash em cesto do email. 
        <li>email_hash_d.db: Contém os dados gerados que foram armazenados em memória secundária sobre a tabela hash em diretório do email.
        <li>listainvertida_blocos.db: Armazenamento dos blocos na lista invertida.
        <li>listainvertida_dict.db: Armazenamento dos dicionario na lista invertida.
        <li>pergunta_hash_c.db:Contém os dados gerados que foram armazenados em memória secundária sobre a tabela hash em cesto das perguntas.
        <li>pergunta_hash_d.db: Contém os dados gerados que foram armazenados em memória secundária sobre a tabela hash em diretório das perguntas.
        <li>perguntas.db: Contém os dados gerados pelo hash sobre perguntas e são armazenados em memória secundária.
        <li>resposta.hash.c.db: Contém os dados gerados que foram armazenados em memória secundária sobre a tabela hash em cesto da resposta.
        <li>resposta.hash.d.db: Contém os dados gerados que foram armazenados em memória secundária sobre a tabela hash em diretório da respostas.
        <li>resposta.db: Contém os dados gerados pelo hash sobre respostas e são armazenados em memória secundária.
        <li>usuario_hash_c.db: Contém os dados gerados que foram armazenados em memória secundária sobre a tabela hash em cesto do usuario.
        <li>usuario_hash_d.db: Contém os dados gerados que foram armazenados em memória secundária sobre a tabela hash em diretório do usuario.
        <li>usuarios.db: Contém os dados gerados pelo hash sobre usuarios e são armazenados em memória secundária.
        <li>voto_pergunta_hash_c.db: Contém os dados gerados que foram armazenados em memória secundária sobre a tabela hash em cesto do voto/pergunta.
        <li>voto_pergunta_hash_d.db: Contém os dados gerados que foram armazenados em memória secundária sobre a tabela hash em diretório do voto/pergunta.
        <li>voto_resposta_hash_c.db: Contém os dados gerados que foram armazenados em memória secundária sobre a tabela hash em cesto do voto/resposta.
        <li>voto_resposta_hash_d.db: Contém os dados gerados que foram armazenados em memória secundária sobre a tabela hash em diretório do voto/resposta.
      </ul>
      <li>Diretório Entidades:
      <ul>
        <li>Pergunta.java: Entidade Pergunta utilizada no projeto.
        <li>Resposta.java: Entidade Resposta utilizada no projeto.
        <li>Voto.java: Entidade Voto utilizada no projeto.
        <li>Usuario.java: Entidade Usuario utilizada no projeto.
      </ul>
      <li>Diretório HashExtensivel:
      <ul>
        <li>HashExtensivel.java: Arquivo utilizado para criação da tabela Hash Extensivel.
        <li>RegistroHashExtensivel.java: Interface que apresenta os métodos que os objetos a serem incluídos na tabela hash extensível devem conter.
      </ul>
      <li>
      <ul>
        <li>pcvEmail.java: Esta classe representa o par chave valor de um email, no caso, o email e o idUsuario.
        <li>pcvPergunta.java: Esta classe representa o par chave valor de uma pergunta, no caso, o idUsuario e o idPergunta.
        <li>pcvResposta.java: Esta classe representa o par chave valor de uma resposta, no caso, o idUsuario e o endereço no arquivo.
        <li>pcvUsuario.java: Esta classe representa o par chave valor de um usuario, no caso, o idUsuario e o endereço no arquivo.
        <li>pcvVoto.java: Esta classe representa o par chave valor de um voto, no caso, o idVoto e o endereço no arquivo.
      </ul>
      <li>Diretório listaInvertida:
      <ul>
        <li>ListaInvertida.java: Classe da criação da lista invertida para acrescentar ou deletar itens da lista, diferente da padrão a lista invertida inverte a hierarquia da informação, sendo assim, ao invés de uma lista de documentos contendo termos, é obtida uma lista de termos, referenciando documentos.
      </ul>
    </ul>
  </body>
</html>
 
