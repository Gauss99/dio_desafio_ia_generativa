<div class="image">
  <img src="https://eu-images.contentstack.com/v3/assets/blt6b0f74e5591baa03/bltfd36e68ac7a0f3b2/651b29bb3671b45abcc7e4c8/Generative_AI_(2).png?disable=upscale&width=1200&height=630&fit=crop" width="850" height="478">
</div>

## Descrição do Projeto 📚

Este projeto utiliza uma plataforma de IA Generettiva para auxiliar numa tarefa específica.

## Conjunto de Dados 💾

O conjunto de dados utilizado neste projeto consiste de uma imagem a qual será cedida ao **Copilot** para extrair o texto desta imagem utilizando apenas um **prompt**.

## Metodologia 📘

O projeto inical se trata de utilizar a ferramenta do *OpenAI* no Azure para performar tais tarefas. Entretanto, é necessário a aplicação a parte no [Link da aplicação do OpenAI](https://customervoice.microsoft.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR7en2Ais5pxKtso_Pz4b1_xUNTZBNzRKNlVQSFhZMU9aV09EVzYxWFdORCQlQCN0PWcu) para que isso seja possível.

O guia do lab que está presente nesse [Link](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/13-azure-openai.html) basicamente faz a instrução de 2 atividades diferentes, sendo uma delas prompt normal para a LLM:

<div class="image">
  <img src="./Imagens_readme/img1.png"  width="800" height="400">
</div>

E também um prompt para o modelo de imagens do OpenAI, o DALL-E.

<div class="image">
  <img src="./Imagens_readme/img2.png" width="800" height="400">
</div>

Como o acesso dessas ferramentas dentro do Azure demandam análise da Microsoft e ainda demandam um email corporativo para que a ferramenta seja liberada, foi optado por usar o Copilot presente no próprio Windows 11.

<div class="image">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2a/Microsoft_365_Copilot_Icon.svg/640px-Microsoft_365_Copilot_Icon.svg.png" width="640" height="640">
</div>

Na primeira etapa, foi feito o *upload* de uma imagem para o **Copilot** e pedido para transcrever o texto da imagem:.

<div class="image">
  <img src="./Imagens_readme/pergunta_copilot.png" width="800" height="400">
</div>

O **Copilot** conseguiu transcrever todo o texto de uma imagem, que se tratava de um *plot* gráfico, quase perfeitamente como visto na imagem de saída:

<div class="image">
  <img src="./Imagens_readme/saida_copilot.png" width="800" height="300">
</div>

A outra atividade foi pedir para o **Copilot** gerar uma imagem a partir de um prompt. Foi passado o seguinte pedido:

"Imagine a imagem de como seria a cidade de Tokio daqui 100 anos"

O resultado retornado pelo **Copilot** foram as duas imagens a seguir:

<div class="image">
  <img src="./Outputs/imagens/img_gen_1.png" width="1024" height="1024">
</div>


<div class="image">
  <img src="./Outputs/imagens/img_gen_2.png" width="1024" height="1024">
</div>

Essas foram apenas 2 de diversas tarefas possíveis utilizando os assistentes virtuais baseados em LLM's. Esses assistentes podem tornar um trabalho de desenvolver algum código ou pensar alguma coisa muito mais fácil, entretanto, é necessário avaliar bem os resultados e considerar adaptações, principalmente em códigos gerados por esses assistentes.

## Repositório do Projeto 🗂️

[![Repo Card](https://github-readme-stats.vercel.app/api/pin/?username=Gauss99&repo=dio_desafio_ia_generativa&bg_color=000&border_color=30A3DC&show_icons=true&icon_color=30A3DC&title_color=E94D5F&text_color=FFF)](https://github.com/Gauss99/dio_desafio_ia_generativa)

## Conclusão 🔚

Com esse projeto, foi possível explorar a IA Generativa e obter resultados muito satisfatórios acerca do *prompt* inicial. Na garande parte dos casos, principalmente se tratando de auxílio em programação e ferramentas de extração de texto em imagens, é necessário pouca ou nenhuma modificação para que tudo funcione.
