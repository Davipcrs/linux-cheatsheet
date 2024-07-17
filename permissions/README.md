# Permissões de acesso a arquivos no linux:
Existem 3 permissões, usuário (Dono), grupo e outros.  
A verificação pode ser feita usando o comando

```shellscript
ls -lah
```

### Alterar grupo e dono do arquivo
Utilizar os comandos de chown e chgrp  
Ambos tem um sintaxe parecida  

Para alterar todos os arquivos de um diretório podemos utilizar a opção -R  
Para visualizar todos os arquivos que tiveram permissões modificada podemos utilizar a opção -c

Exemplo:  

```shellscript
chown -Rc Username "path/to/file.txt"
chgrp -Rc Groupname "path/to/file.txt"
```

### Permissões Básicas

Para fazer a alteração pode ser feita por octais:  

  - 7 Full Controll
  - 6 Leitura e escrita
  - 5 leitura e execução
  - 4 leitura
  - 3 escrita e execução
  - 2 escrita
  - 1 execução
  - 0 sem permissão

Exemplo:

```shellscript
chmod 000 "path/to/file.txt"
```
    
O Primeiro octal é a permissão do Dono do Arquivo  
O Segundo octal é a permissão do GRUPO Dono do Arquivo  
O Terceiro octal é a permissão dos Outros do Arquivo  

### Permissões Especiais
