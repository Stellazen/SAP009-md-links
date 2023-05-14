# Markdown Links
Projeto 04 da turma 009 da Laboratória.
## Sobre oque é esse projeto
O objetivo deste projeto era criar uma ferramenta de linha de comando (CLI) e a própria biblioteca instalável em JavaSript.
## Como Utilizar
* Para instalar execute o segundo comando no terminal:<br>
```npm i md-links-stellazen```
* Depois de instalado é possível utilizar os seguintes comandos:<br>
```md-links ./caminhoDaPasta``` ou ```md-links ./caminhoDaPasta/nomeDoArquivo```<br>
que vai retornar todos os links que existirem em arquivos Markdown.
* Também pode ser inserida a flag --validate, desta maneira:<br>
```md-links ./caminhoDoArquivo --validate```<br>
que vai retornar os links presentes no arquivo e seus respectivos status HTTP, com 'ok' ou 'fail'.
* Da mesma maneira também podemos inserir a flag --stats:<br>
```md-links ./caminhoDoArquivo --stats ```<br>
Que irá retornar a quantidade de links totais e links únicos.<br>
* E, por último, podemos utilizar combinando as duas flags:<br>
```md-links ./caminhoDoArquivo --stats --validate ```<br>
Que irá retornar a quantidade de links totais, únicos e quebrados.<br>
## Tecnologias Utilizadas
✅ NodeJs
✅ JavaScript
✅ Jest
✅ Github
✅ Trello


