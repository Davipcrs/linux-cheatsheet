# Permissões de acesso a arquivos no linux:
Existem 3 permissões, usuário (Dono), grupo e outros.  
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
O Primeiro octal é a permissão do Dono do Arquivo  
O Segundo octal é a permissão do GRUPO Dono do Arquivo  
O Terceiro octal é a permissão dos Outros do Arquivo  

    ```shell
    chmod 000 "file/path"
    ```

### Permissões Especiais
