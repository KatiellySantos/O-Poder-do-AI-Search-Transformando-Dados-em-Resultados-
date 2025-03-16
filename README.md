# Projeto Azure Cognitive Search: Utilizando ALL Search para Indexação e Consulta de Dados

O Azure Cognitive Search organiza e automatiza a busca de dados, sendo uma poderosa solução para indexação e consulta. 
Com ele, é possível simplificar tarefas como relatórios e feedbacks de clientes, além de criar sistemas de busca personalizados 
para sites ou plataformas. Essa tecnologia também permite análises avançadas, como identificação de padrões, sentimentos e recomendações 
automáticas, tornando os processos mais inteligentes e eficientes.

🚀 Passo a Passo para Configuração e Uso do Azure Cognitive Search

1. 💻 Criar o Recurso Azure Cognitive Search

    1. Acesse o portal do Azure e clique em Criar Recurso.

    2. Selecione Azure Cognitive Search.

    3. Configure as opções:

       * Assinatura: utilize uma existente ou crie uma nova.
       * Nome: insira um nome exclusivo para o serviço.
       * Localização: escolha uma região, como "US East".
       * Plano de Preços: selecione Basic para começar.
        
    4. Clique em Criar.
 
    ![Passo01](https://github.com/user-attachments/assets/1995ee18-d4f3-4b9f-bde6-11c308c173f6)

2. 💻 Criar o Recurso Azure AI Services

    1. Retorne ao portal do Azure e clique em Criar Recurso.

    2. Escolha a categoria IA + Machine Learning e selecione Azure AI Services.

    3. Preencha as informações básicas, como assinatura, nome e localização.

    4. Clique em Criar para finalizar.
    
   ![Passo02](https://github.com/user-attachments/assets/fea5178f-f01e-42c1-a630-ae62bc6cc068)

3. 💻 Criar Conta de Armazenamento no Storage Accounts

    1. No portal do Azure, selecione Criar Recurso e escolha Storage Accounts.

    2. Preencha os campos obrigatórios:

       * Assinatura, Nome e Localização.
       * Ajuste as configurações conforme necessário.

    3. Clique em Criar.

   ![Passo03](https://github.com/user-attachments/assets/2d3fb256-c3da-4a27-8bcd-ecac160ef68f)

📍 Configuração do Armazenamento

 Após criar a conta de armazenamento:

   * Acesse Configurações > Configuração e ative a opção Permitir acesso anônimo ao blob. Clique em Salvar.

   ![Passo04](https://github.com/user-attachments/assets/8fd8a9af-f65f-42c1-9bdf-71abdba52294)
        
   * Vá até Armazenamento de Dados > Contêineres e crie um novo contêiner.
   * No campo Nível de Acesso, escolha conforme indicado na documentação. Insira o nome apropriado e clique em Salvar.   
   ![Passo05](https://github.com/user-attachments/assets/f5dde191-e05f-4b46-a0f3-c8c3ff189f15)
       
   * Faça o upload dos arquivos recomendados diretamente no contêiner
       (https://aka.ms/mslearn-coffee-reviews) ou veja a documentação do projeto em
     https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html e clique em Salvar.
     
   ![Passo06](https://github.com/user-attachments/assets/79125597-3b1c-4412-b1a7-95145e1f080b)

4. 📂 Configuração e Consulta de Dados no Azure Cognitive Search

      * Acesse o recurso Azure Cognitive Search criado anteriormente.
      * Clique em Importar Dados para carregar as informações do contêiner configurado.
      * Certifique-se de que os dados foram importados com sucesso.
      * Utilize o Search Explorer para consultar resultados e explorar as funcionalidades.

  ![Sem título](https://github.com/user-attachments/assets/bce28fd7-0d11-4389-83b9-5426b4a7442b)


       




