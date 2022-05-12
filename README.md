# s3-file-storage-example

Amazon AWS

#Criar Serviço S3
Create bucket
  >Coloque um nome
  >Desmarque Block all public acess
  >Marque "I acknowledge"
  >Create bucket
  
#Credenciais de Acesso para o arquivo yml:
  >no site da AWS, clique no nome de usuário, 
  My Security Credentials, Acess Keys
  >Copie as duas chaves e cole no application.yml do projeto Spring
  >No arquivo application.yml, não necessita colocar a região
  >Em application/bucket/name, coloque o nome do bucket
  
#Para testar o upload de arquivos pelo Postman, use
  >Body, form-data, key = file, marque file, escolha o arquivo, e dê um send 