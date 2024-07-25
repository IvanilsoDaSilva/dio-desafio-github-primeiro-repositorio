O GIT é um sistema distribuido e seguro e possui as seguintes estruturas para isso: 

Blobs
- As bloobs git são objetos que contem o arquivo
- Contem o tipo do arquivo, seu tamanho e o conteudo. Ex.: "Blob \0 Ola Mundo"
- As bloobs possuem meta dados do arquivo
- Bloco básico de composição
- Possui o SHA dos seus meta dados

Trees
- Armazena as Bloobs e outras Trees (Monta uma estrutura de pastas)
- Ex.: "Tree \0 blob sa4d8s texto.txt"
- As bloobs possuem meta dados das bloobs
- Responsavel pela estrutura dos arquivos
- Possui o SHA dos seus meta dados

Commits
- Junta toda a operação
- Contem a tree, seu commit antecessor, autor, mensagem, timestamp. Ex.: "Commit tree: s3s3sd1, parente: s3s3sd1, autor: Autor, mensagem: 'FEAT: tal', timestamp: 11-12-2024"
- Possui o SHA dos seus meta dados

[git-commands](https://github.com/IvanilsoDaSilva/git-commands)