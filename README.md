<h1></h1>
<p>Os arquivos .proto definem estruturas serializadas pelo protocol buffer.</p>
<p>O comando <strong>protoc --go_out=. nomeArquivo</strong> gera código manualmente para o Go.</p>
<p><strong>go generate</strong> gera o arquivo atraves de um comentario colocado no inicio do arquivo go</p>
<p>Exemplo para ser usado diretamente em um arquivo go <em>//go:generate protoc --go_out=. ./user/user.proto
</em></p>
