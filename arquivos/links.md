# Links entre arquivos e diretórios
Existem 2 tipos de links o Hard Links e o Symbolic Links  
Raramente utilizamos o Hard Links pois são links para inodes de arquivos  
Symbolic Links são semelhantes a atalhos do Windows  
Uso da Ferramenta ln para criação dos links

### Link simbolicos
Symbolic Links pode ser utilizado em varias aplicações para habilitá-las. Um exemplo é o 
sites-avaliable e o sites-enable do Nginx.  
Conforme o arquivo nginx.md (link) utilizamos links simbolicos para habilitar arquivos de configurações de sites.  

Exemplo:  

´´´shellscript
ln -s arquivo-original atalho-novo
´´´

### Link Fisico (Hard Link)
