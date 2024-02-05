<h1>
    <a href="https://web.dio.me/track/microsoft-azure-ai-fundamentals?page=1&search=&tab=path/">
     <img align="center" width="60px" src="https://hermes.dio.me/tracks/4d998d5c-36c1-497b-8da0-8db465c820eb.png"></a>
    <span> Azure Cognitive Search: Utilizando AI Search para indexação e consulta de dados</span>
</h1>

## O que precisa ser feito?

O desafio propõe que seja criada uma pesquisa que funcione juntamente com um serviço de inteligência artificial para identificar palavras chave e sentimentos (utilizando também o serviço de armazenamento do Azure).

[Documentação](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html)

## Primeira etapa: Criando recurso do Azure AI Search:   

01 - Clique em "Azure AI Search" e vá em "Criar"

<img align="right" src="https://github.com/miguelfmds/bootcamp-microsoft-azure-ai-fundamentals/assets/157380435/b54ccba1-e01c-4e90-84ea-c19cb2e80423" width=""/> 

02 - Configure dessa maneira (altere o nome do recurso para a maneira que preferir)
<img align="right" src="https://github.com/miguelfmds/bootcamp-microsoft-azure-ai-fundamentals/assets/157380435/dd738a26-9e91-496a-97c3-475ffeb87ccb" width=""/> 

03 - Aguarde terminar a implantação
<img align="right" src="https://github.com/miguelfmds/bootcamp-microsoft-azure-ai-fundamentals/assets/157380435/333e8d97-a3d7-4b53-807b-b5b7ba89ed56" width=""/> 

## Segunda etapa: Criando recurso do Azure AI Services:  

01 - Clique em "Serviços Cognitivos" e configure da maneira que já vimos anteriormente nos LAB's anteriores
<img align="right" src="https://github.com/miguelfmds/bootcamp-microsoft-azure-ai-fundamentals/assets/157380435/cce227fd-028c-4073-9e28-a8817d606fe9" width=""/>

02 - Aguarde implantação
<img align="right" src="https://github.com/miguelfmds/bootcamp-microsoft-azure-ai-fundamentals/assets/157380435/333a1f5b-6581-45c4-a554-863aa6cc1a7d" width=""/>

## Terceira etapa: Criando o armazenamento (storage):  

01 - Clique na opção "Contas de armazenamento"
<img align="right" src="https://github.com/miguelfmds/bootcamp-microsoft-azure-ai-fundamentals/assets/157380435/fa3c11b7-0730-4820-852d-1c85115b04ec" width=""/>

02 - Em seguida, vamos na opção "Criar"
<img align="right" src="https://github.com/miguelfmds/bootcamp-microsoft-azure-ai-fundamentals/assets/157380435/9ccc0d95-ecef-4cbc-bbe2-4eb1c692decf" width=""/>

03 - Configure dessa maneira (se surgir alguma dúvida, consulte a documentação linkada acima), clique em "Examinar", avance e clique em "Criar"
<img align="right" src="https://github.com/miguelfmds/bootcamp-microsoft-azure-ai-fundamentals/assets/157380435/ce56441c-aeb2-4236-a351-155a191696f0" width=""/>

## Quarta etapa: Permitindo acesso anônimo ao Blob:  

Como nosso laboratório é apenas didático (com o objetivo de aprender os princípios da inteligência artificial com o Azure), precisamos permitir o acesso anônimo ao blob para simplificar e facilitar nossas implementações!

01 - Após criar o armazenamento, entre no mesmo e navegue até a guia "Configurações" e clique em "Configuração", marcando as opções abaixo. Logo após, clique em "Salvar":
<img align="right" src="https://github.com/miguelfmds/bootcamp-microsoft-azure-ai-fundamentals/assets/157380435/b32f74a4-d148-4fb4-b7e6-bfed3671b258" width=""/>

## Quinta etapa: Criando o container: 

01 - Ainda dentro do armazenamento que foi criado, navegue até a aba "Armazenamento de dados" e selecione a opção "contêineres". E então, clique na opção "+Contêiner":
<img align="right" src="https://github.com/miguelfmds/bootcamp-microsoft-azure-ai-fundamentals/assets/157380435/b2e7f1bf-9c60-4fd6-939b-7014939ae41c" width=""/>

02 - Logo em seguida, preencha a aba "Nome" com "coffeereviews" e configure da maneira que está exposta na imagem abaixo:
<img align="right" src="https://github.com/miguelfmds/bootcamp-microsoft-azure-ai-fundamentals/assets/157380435/55e76bc3-77e4-497d-b901-a3c6faf31e3f" width=""/>

## Sexta etapa: Carregar o Blob: 

01 - Selecione o contêiner que foi criado (nesse caso, "coffeereviews"):
<img align="right" src="https://github.com/miguelfmds/bootcamp-microsoft-azure-ai-fundamentals/assets/157380435/d13ab3b8-7011-4dc6-8ba4-b489f3a778a8" width=""/>

02 - Na nova página, vá na opção "Carregar": 
<img align="right" src="https://github.com/miguelfmds/bootcamp-microsoft-azure-ai-fundamentals/assets/157380435/189984e5-8e0b-470d-aae2-37c4670e02d2" width=""/>

03 - Faça o download dos arquivos na documentação linkada acima e, logo em seguida, faça o upload dos arquivos baixados:
<img align="right" src="https://github.com/miguelfmds/bootcamp-microsoft-azure-ai-fundamentals/assets/157380435/30ccc47e-96a5-4804-8535-9ca96362326b" width=""/>

## Sétima etapa: Importação e indexação dos dados: 

01 - Voltamos para o AI Search, selecione o elemento criado e então clique na opção "Importar dados":
<img align="right" src="https://github.com/miguelfmds/bootcamp-microsoft-azure-ai-fundamentals/assets/157380435/97cc7f87-5d97-4c48-9ed2-4cd3060daaa9" width=""/>
