# Microsoft-AI-Search-Index

## Crie um recurso do Azure AI Search

Acesse o portal https://portal.azure.com/ e clique em "Criar um Recurso" 

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/3635637f-38c6-4093-b946-604e52020da6)

No Marketplace procure por "Azure AI Search" e depois clique em "Criar"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/cfe22b3d-2270-4362-bf32-0e314ed44b3d)

Preencha os campos como na imagem e depois clique "Alterar o Tipo do Preço"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/9e7308dd-2f4d-40a8-928b-59174ff78b4a)

Selecione "Básico" ou "Gratuito", recomendo "Básico"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/cd7a21d4-6e48-4517-a8c4-4a9daca07821)

Depois clique em "Revisar + Criar"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/b7c93a12-f765-42ea-b481-17d7ab12ea76)

Depois de ser validado com sucesso clique em "Criar" e aguarde a "Implantação"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/db35e705-e623-4b35-8f39-7f312317c15a)


Clique em "Ir para o Recurso"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/3bf4ea9a-b3dd-41b9-a54b-6cd2d4d7dbf3)

## Volte ao portal https://portal.azure.com para criar o novo recurso

## Crie um recurso de serviços de IA do Azure

Clique em "Criar um recurso" novamente

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/ffa5794d-5498-4777-9bcd-ab4c5e56f2d5)

Mude o idioma pra ingles e procure por "Ai Azure Services"... depois mude pra português novamente

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/aafea332-ca68-4a34-943b-6c2d57ac95fe)


Preencha os campos como na imagem abaixo, depois marque a caixinha antes de seguir adiante

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/8441cec4-3870-402c-b495-9071e9fc9886)

Depois clique em "Create" e aguarde a implantação

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/1aba35d5-b6eb-4ca8-8965-563eebc618cf)

Depois, na aba lateral esquerda vamos criar o 3º recurso

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/891b427e-a06f-40f6-a8f5-02f15df2a3e7)

## Crie uma conta de armazenamento

No Marketplace procure por "Conta de Armazenamento" então clique em "Criar"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/cc5599d9-5d23-413a-8dc6-565f97cfdcbe)

Preencha como na imagem e role pra baixo 

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/f8de71fd-f42c-4f4d-af40-4faeb5ff54db)


Configure o restante como na imagem abaixo

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/b4d2c43c-9ddb-49a1-8494-ffecb774be0e)

Clique em "Examinar"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/d1eb106d-46cb-41ff-8112-7aa6562869ac)

Depois clique em "Criar", aguarde a "Implantação"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/e6bde626-6eaa-4473-9efe-84bdd15b5066)

Entre na "Conta de Armazenamento" no painel esquerdo 

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/98a05c4f-310b-41f3-82b9-4d52ddf2b5a0)

Clique no recurso

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/0f33035b-cdce-4de9-898c-984aaa1ab3d6)

Vá em "Configuração"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/bc49cd24-13d8-42c9-990d-be3c7375fca6)

Clique em "Permitir acesso anônimo ao Blob" e salve

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/afb7ef43-6d25-4482-b9b4-438ebf9077b3)

"Salvar"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/514bb845-89ed-4bac-ab1d-abd92e8ab6fb)

## Carregar documentos para o armazenamento do Azure

Agora vá para "Containers"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/c8e7884f-ffad-4e54-b1a4-bc83552cb534)

Clique em " + container"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/394fbc79-b5a1-47c1-8c11-98e6863b105a)

Configure o container como na imagem abaixo e depois clique em "Criar"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/013c047a-7e99-4da7-8a3e-11d126983709)

Copie este link e abra em uma aba no navegador ----> https://aka.ms/mslearn-coffee-reviews

Clique em "Visão Geral" e depois "Carregar"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/8552b362-5ef1-4b32-9520-96e5f802d532)

Extraia o conteudo do link para uma pasta chamada "avaliações"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/48261812-6b62-4ce0-85a6-9d4aa8165a21)

Suba a pasta de avaliações e selecione "coffee-review"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/60a698b5-b37d-4dea-b1a7-b75522a2cc52)

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/daea2e42-aef3-47fe-98e9-2c4e4c23b76d)

Depois clique em "carregar"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/87dd9228-ec55-4cac-a912-81e3eff7de7c)

Aguarde o carregamento

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/9412e3e3-9ecb-464b-bed4-40ac9f36d949)

## Indexar os documentos

Clique em "Pagina Inicial" e depois clique no seu recurso "Search" ou "busca"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/cdfc8e63-1dcd-4562-ab86-4914b84f5f8c)

Depois clique em "Importar Dados"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/06d5f18e-dc1d-45d2-acd8-c0fb6fdf30b2)

Selecione "Armazenamento de Blob do Azure"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/5882afcb-a5e2-4075-b417-45a847d22ac5)

Preencha os dados como na imagem e vá em "Escolher uma conexão existente"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/b2144b66-0c21-4961-a0fb-a37116725876)

Clique no recurso que você criou anteriormente

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/1599a1c9-1990-4857-8487-ad55cd7e0407)

depois em "coffee-reviews"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/ffc74781-3c50-4ecf-9418-99e1534f901f)

Por ultimo clique em "Selecionar"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/c3cf053d-bc47-4ceb-87f0-168e9d1c604e)

"Pasta de blobs" deixe em branco e adicione a descrição, depois clique em "proximo..."

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/ae445e3a-a8ed-4c70-a563-7309d09c11ae)

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/9e1816f0-aea8-4968-8013-fb450cfcb3b0)
