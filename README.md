# O-Poder-do-AI-Search-Transformando-Dados-em-Resultados-
O AI Search ajuda a organizar dados e automatizar buscas, 
facilitando o trabalho com relatórios ou feedbacks de clientes. 
Também dá pra usar em projetos reais, criando sistemas de busca 
personalizados pra sites ou plataformas. Com a IA, ainda é possível 
fazer análises mais avançadas, como identificar sentimentos, padrões 
ou gerar recomendações automáticas, deixando tudo mais prático e inteligente.

🚀 Passo a Passo para Consulta de Dados com Azure
1 - 💻 Criar o Recurso AI Search

   ▪️Acesse o portal do Azure e clique em Criar Recurso.
   ▪️Escolha Azure AI Search na lista.
   ▪️Configure as opções:
       ▪️Assinatura: escolha uma existente ou crie uma nova.
       ▪️Nome: insira um nome exclusivo para o serviço.
       ▪️Localização: escolha uma região, como "US East" ou outra disponível.
       ▪️Plano de Preços: selecione Basic para iniciar.
       ▪️Clique em Criar.
       ![Passo01](https://github.com/user-attachments/assets/1995ee18-d4f3-4b9f-bde6-11c308c173f6)
       
2 - 💻 Criar o Recurso Azure AI Services

   ▪️Volte ao portal do Azure e clique em Criar Recurso.
   ▪️Escolha a categoria IA + Machine Learning e selecione Azure AI Services.
   ▪️Preencha as informações em Noções Básicas, como assinatura, nome e região.
   ▪️Clique em Criar para finalizar.
   ![Passo02](https://github.com/user-attachments/assets/fea5178f-f01e-42c1-a630-ae62bc6cc068)

3 - 💻 Criar Conta de Armazenamento no Storage Accounts

   ▪️No portal do Azure, clique em Criar Recurso e selecione Storage Accounts.
   ▪️Preencha as informações:
       ▪️Assinatura, Nome e Localização.
       ▪️Configure as opções em Noções Básicas conforme necessário.
   ▪️Clique em Criar.
   ![Passo03](https://github.com/user-attachments/assets/2d3fb256-c3da-4a27-8bcd-ecac160ef68f)
   📍️Configurar a Conta de Armazenamento
    ▪️Após a criação, é necessário liberar o acesso:
       ▪️Acesse Configurações > Configuração e ative a opção Permitir acesso anônimo ao blob.
       ▪️Clique em Salvar.
       ![Passo04](https://github.com/user-attachments/assets/8fd8a9af-f65f-42c1-9bdf-71abdba52294)
        Em seguida:
       ▪️Vá para Armazenamento de Dados > Contêineres e crie um novo contêiner.
       ▪️No campo Nível de Acesso, escolha a última opção de acordo com o print.
       ▪️Insira o nome sugerido na documentação no link: 
       https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html e clique em Salvar.
       ![Passo05](https://github.com/user-attachments/assets/f5dde191-e05f-4b46-a0f3-c8c3ff189f15)
       ▪️Faça o upload dos arquivos indicados na documentação diretamente no contêiner criado 
       (https://aka.ms/mslearn-coffee-reviews)
       ![Passo06](https://github.com/user-attachments/assets/79125597-3b1c-4412-b1a7-95145e1f080b)

4 - 📂 Configurar e Consultar os Dados no AI Search

    ▪️Volte para o recurso AI Search criado anteriormente.
    ▪️Clique em Importar Dados para carregar as informações do contêiner criado.
    ▪️Verifique se os dados foram importados corretamente.
    ▪️Use o Search Explorer para consultar os resultados.
    ![Passo07](https://github.com/user-attachments/assets/8935bf27-c687-4594-86e8-1fc17a955fa1)

       




