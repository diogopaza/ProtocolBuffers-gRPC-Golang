<h1></h1>
<p>https://www.youtube.com/watch?v=_jQ3i_fyqGA</p>
<p>Os arquivos .proto definem estruturas serializadas pelo protocol buffer.</p>
<p>O comando <strong>protoc --go_out=. nomeArquivo</strong> gera código manualmente para o Go.</p>
<p><strong>go generate</strong> gera o arquivo atraves de uma tag colocada no inicio do arquivo go</p>
<p>Exemplo para ser usado diretamente em um arquivo go <em>//go:generate protoc --go_out=. ./user/user.proto
</em></p>
