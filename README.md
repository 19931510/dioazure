# Criando Processos de Redundância de Arquivos na Azure


1- Criação do Azure Data Factory: fazer a criação do Data factory

2- Configurar o Integration runtime

![image](https://github.com/user-attachments/assets/232bfc82-1942-42be-80d5-71a37f07e12a)

Apos a criação do Integration runtime é feita a conexão no linked service, com acesso ao ambiente on-primese

![image](https://github.com/user-attachments/assets/f2c26432-c4e1-4d45-abc8-a4286a278283)


3- No Data Factory, crie um novo pipeline, que é a estrutura que orquestrará o fluxo dos dados.
- Adicione atividades de cópia que moverão os arquivos das fontes para os destinos, criando redundância.

- ![image](https://github.com/user-attachments/assets/e8bdae3f-7d70-4119-abfa-800815a670ed)


4- Fonte e Destino de Dados:- Configure os Linked Services para conectar as fontes  e os destinos.
![image](https://github.com/user-attachments/assets/3deea04b-0636-4ba4-89bb-50e69eac2fba)

 Utilize o painel de monitoramento do Data Factory para acompanhar a execução dos pipelines. Configure alertas para casos de falha ou problemas no processo.






