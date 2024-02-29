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

"Pasta de blobs" deixe em branco e adicione a descrição, depois clique em "proximo..."  e aguarde a validação!

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/ae445e3a-a8ed-4c70-a563-7309d09c11ae)

Em "Anexar IA" selecione o seu recurso

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/faea6e6a-4c75-4c85-8722-f3d1890b0181)

Em "Adicionar enriquecimentos" configure como na imagem

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/1dbd94c5-a07d-4a5d-ace3-390303febde1)

Selecione as caixinhas como na imagem abaixo

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/79d04918-4dd9-450a-95dc-c4564ac8297a)

Clique em "Salvar os enriquecimentos..." 

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/0d290dc8-a014-4107-b07d-a4488d6c2cc0)

Ao escolher a caixinha "Projeção de imagem" se aparecer o erro acima clique em "Escolher uma conexão existente"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/c7b29866-1bc1-41da-87f9-ec8b5edc9c38)

Selecione o recurso que você criou anteriormente

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/0b5ce9a5-ad3f-4cd8-8d09-461e91a4f581)

Depois selecione "Projeção de blob do Azure: Documento", não altere o nome do container abaixo

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/9b8399a8-8a9d-4833-81c1-597244011048)

Depois clique em "Próximo..." e aguarde a validação

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/9fdcf6a4-d0ab-4274-bc99-f413077294bd)


Altere somente o nome do index

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/ea01fb8d-5ad4-45e3-b755-e34065048402)

Para todos os que já vieram selecionados por padrão adicione a caixinha "Filtrável" 

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/056c68c0-e47d-406a-b6a6-1d59f4596da2)

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/90032f33-8fa4-4507-b715-0c43ffb14ffd)

Clique em "Criar Indexador" e aguarde a validação

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/0c0a07fb-f644-4615-a4bc-414c542bf271)

Altere o nome do indexador para "coffee-indexer" e mantenha a configuração da agenda como está

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/1e5e40bd-7264-40ab-b063-9edaf35d7e84)


Clique em "Opções Avançadas" e Certifique-se de que a caixinha "Base-64 Encode Keys" esteja selecionada

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/a67f47ea-7b92-4a8d-98bc-f89579c06f88)

Não altere mais nada e clique em "Enviar" e aguarde a notificação da pesquisa

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/8ae9d038-154d-4c87-a671-5f3bcb042810)

Vá ao "Gerenciamento de Pesquisa", depois em "indexadores"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/c50db24f-a000-43d2-8019-e70d4977cf48)

Selecione "coffee-indexer"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/aac58bf7-587e-4516-ac6a-30414eaa5aee)

Volte ao "Overview" e va na aba "Search Explorer"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/73653103-3f01-43da-945b-d13e72917fb8)

Clique no view para ver o JSON

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/01163abf-4084-44e1-a070-29739715abf1)


No campo do editor de consultas JSON , copie e cole:

{
    "search": "*",
    "count": true
}

Selecione "Search"

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/bef3027a-96f1-4cef-9149-394bb185f67a)

Por fim toda a informação

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/69685f4c-1199-44fa-b672-901f423fcb18)

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/0d6ec29f-f083-4433-9215-4ff238a50c4c)



## Revise o armazenamento de conhecimento

Retorne a "Storage Accounts" e clique no recurso

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/6a9cd6af-0ecd-49bb-960d-375f92ef06e0)

Selecione qualquer um dos arquivos .jpg

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/ada0142a-1e83-4741-8692-83485d8e8392)


Selecione "Editar" para ver as imagens

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/7922335b-fc2f-440d-ae01-d13659989edc)

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/3e84dfd3-acb3-4bc1-9e7c-37f715dde3ea)

![image](https://github.com/pedroheinrich/Microsoft-AI-Search-Index/assets/97209403/e1707922-aa9b-4aef-acf0-51be434d1948)

