<div align="center">
  <img src="https://github.com/Ka-Soares/animation/assets/145347801/3eb7de64-6d80-47ce-bbf0-9154aaf7fce5" width=60% />
</div>

# Global Solution - FIAP

O desafio proposto foi desenvolvido a pedido da Hapvida NotreDame Intermédica para ser realizado o desenvolvimento e ideação de uma solução para algum dos problemas que nos foram apresentados, no atual projeto, o monitoramento remoto da saúde de pacientes foi escolhido para ser solucionado. Nesse arquivo você encontrará a justificativa do projeto, os objetivos que ele propõe e a descrição do produto.

Este ainda é relacionado a matéria Computational Thinking with Python, ministrada pelo Professor Francisco Bezerra.

# Descrição do Projeto

O Hapvida Away é um software desenvolvido para abordar o problema do monitoramento remoto da saúde e fornecer assistência rápida a pacientes, especialmente em situações de emergência. Muitas pessoas enfrentam dificuldades para comparecer ao hospital ou necessitam de orientação imediata, o que pode resultar em situações estressantes e, em alguns casos, falta de primeiros socorros adequados, podendo até custar vidas.

# Principais Funcionalidades
O foco principal do Hapvida Away é atuar como um assistente virtual para melhorar a qualidade de vida dos pacientes do Hapvida NotreDame Intermédica. A principal função do software inclui:

<h3>Assistência Personalizada:</h3> Os usuários podem fornecer sintomas, e o assistente virtual sugere a especialidade médica adequada. Por exemplo, se um usuário relatar problemas de audição, o software pode recomendar a busca por um médico otorrinolaringologista.

<h3>Orientação de Primeiros Socorros:</h3> Em situações específicas, como queimaduras, o assistente fornece orientações de primeiros socorros. Por exemplo, alertando contra o uso de produtos "refrescantes" como pastas de dente e instruindo a não aplicar panos sobre o local afetado.

# Estruturas Utilizadas 

O desenvolvimento do Hapvida Away incorpora diversas estruturas de programação para garantir seu funcionamento eficaz:

<h3>Estruturas Condicionais e de Repetição:</h3> Utilização de estruturas condicionais como if e loops for para detectar condições e executar operações repetitivas.

<h3>Funções com Passagem de Parâmetros e Retorno:</h3> Implementação de funções para executar partes do código diversas vezes, além de possibilitar o funcionamento do chatbot com a biblioteca Gradio.

<h3>Validação de Dados de Entrada do Usuário:</h3> Utilização de estruturas condicionais (if) para identificar se as entradas do usuário correspondem às funcionalidades do programa.

<h3>Armazenamento de Dados em Variáveis e Listas:</h3> Uso de listas para identificar palavras-chave fornecidas pelo usuário e armazenamento de informações relevantes em variáveis.

<h3>Processamento Adequado das Informações:</h3> Utilização de elif e else para garantir que informações incongruentes não afetem negativamente o funcionamento do código.

<h3>Apresentação de Resultados Utilizando f-strings:</h3> Utilização de f-strings para apresentar resultados de maneira clara e concisa.

----------

# Implementação do Código

O código do Hapvida Away foi desenvolvido com o intuito de criar um assistente virtual eficiente para o monitoramento remoto da saúde, fornecendo orientações e assistência rápida aos pacientes. Abaixo, detalhamos a implementação do código:

<h3>Biblioteca Utilizada</h3>
Gradio: Biblioteca responsável por executar o chatbot de forma visual. Oferece a possibilidade de integração via API em sites, além de elementos de HTML e CSS para personalização.

<h3>Listas de Palavras-chave</h3>
Foram criadas listas de palavras-chave que o programa reconhecerá para direcionar as interações do usuário:


```
ajuda: Comandos relacionados à ajuda.

informacao: Comandos relacionados a obter informações.

emergencia1 e emergencia2: Palavras-chave relacionadas a situações de emergência.

otorrino e psicologo: Palavras-chave associadas a especialidades médicas.

queimaduras: Palavras-chave relacionadas a situações de queimaduras.
```

<h3>Estruturas e Funcionalidades no Código</h3>
O código utiliza diversas estruturas de programação para criar o assistente virtual:

<h3>Função Chat:</h3>

A função chat é a parte central do programa, executando todas as partes condicionais do código.
Recebe dois parâmetros: message (mensagem do usuário) e history (não utilizado neste momento, mas destinado a armazenar o histórico de interações).
Implementa condicionais para identificar palavras-chave e direcionar o chatbot para as respostas adequadas.
Função Emergência:

A função emergencia é chamada quando um usuário tem uma pergunta relacionada a sintomas específicos (por exemplo, dor na cabeça, dor na garganta, stress, tristeza, etc).
Identifica palavras-chave nas mensagens do usuário e fornece recomendações de especialistas.

<h3>Interface Gráfico-Visual Gradio:</h3>
Utiliza a biblioteca Gradio para criar uma interface gráfica e visual para o chatbot.

<h3>Execução e Comandos Disponíveis</h3>
O código é executado através da variável hapvida_away, que inicia a interface visual do Gradio. O usuário pode interagir com o chatbot através de comandos como "Ajuda", "Informação", "Emergência" e palavras-chave associadas a especialidades médicas e situações específicas.

## 👑 <a>Colaboradores do grupo Hapvida-Away</a>
<div style="display: inline_block"><br>
<p>
  <img src="https://github.com/Projeto-Dev-Aula/cp2-front-web-2sem/assets/145347801/900140b6-2724-452a-a822-296d38ace27f" width="75" height="75" style="width:75px;max-width:75px;height:75px" />  Eduardo Brites - RM 552943 <br>
</p>

<p>
  <img src="https://github.com/Projeto-Dev-Aula/cp2-front-web-2sem/assets/145347801/addf3154-41e5-4227-ba6d-887d3ea737a1" width="75" height="75" style="width:75px;max-width:75px;height:75px" /> Karolina Soares - RM 554187 
</p>
</div>



