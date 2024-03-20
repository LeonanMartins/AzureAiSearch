# AzureAiSearch
Descrição de uma analise realizada em Azure Ai Search.
Primeiramente vamos acessar o portal do Azure através do site https://portal.azure.com/ e então vamos selecionar Create a Resource.
Então a primeira opção de recurso será o Azure AI Search, a qual vamos procurar e selecionar. Depois vamos selecionar a nossa assinatura, o nosso grupo de recursos, daremos um nome ao serviço e então escolhemos o quanto vamos gastar (Melhor opção é o basic).
Depois é só clicar em review and create.
Agora precisamos voltar ao portal e então criar um recurso de IA, através do Azure Ai Services e fazemos os mesmo procedimentos anteriores( nome de recursos, preço e etc..).
Vamos precisar criar um local para armazenamento, então no portal vamos clicar em storage account , sendo que repetiremos os passos de criação anteriores, com a diferença que agora precisamos selecioar a performance( standart) e a redundância (LRS) e entãoo pode selecionar review and create.
Agora vamos nas configurações do strorage acount para alterar algumas configurações de segurança. Vamos habilitar o acesso anonimo de Blob e salvamos.
Clicamos em conteainer da barrea de ferramentas, e então vamos criar um container com a definição do anonymous read access em  anonymous read access for containers and blobs.
Dentro de containers vamos fazer o upload dos arquivos baixados na documentação.
Voltamos então no Ai Search, selecionamos o nosso mecanismo de busca, clicamos em importar dados e selecionamos o container criado.
E agora já podmos analisar os dados através do Search Explorer.
