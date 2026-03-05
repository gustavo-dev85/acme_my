vamos ultilizar next.js para construir uma aplicação web seguindo um tutorial oficial com pequenos ajustes 

o projeto original está disponivel no site do next.js e la vai ter o passo a passo e a documentação da ferramenta.

criamos um repositorio e vamos acessar o codespace do github

dentro do vscode web nos criamos um arquivo chamado .gitingnore nele a gente chama pastas que não queremos que subam no commit por questões de economia de espaço, segurança e etc...

arquivo package.json criado nele adicionamos algumas configurações sendo elas;
"private":true, (avisa o sistema; projeto particular, não deixe ninguem de fora ver ou baixar)
"type": "module" (Na prática: Isso permite que você use a palavra mágica import para trazer ferramentas de outros arquivos.
Exemplo: import React from 'react';)

atraves do comando; npm i react@^18 react-dom@^18 next@^15^C
instalei dependencias das tecnologias citadas em versões especificaas por questão de segurança

apos a instalação geramos um arquivo chamado de "package-lock.json" não mexemos nele mas mesmo assim é muito importante pois as dependencias que instalamos precisam de outras e essas estão alocadas nesse arquivo