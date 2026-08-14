# IA-carol

Descrição do problema

O problema está relacionado a uma deficiência nos e-books é sites de leituras em geral, com a falta de acessibilidade com os deficientes visuais e a ideia e trazer uma IA que consiga cumprir com essa requisição utilizando o voice 


Publico

O publico alvo se trata de pessoas preferencialmente com deficiência visual 


Tratação do problema com IA

A questão é que e muito mais facil utilizar a IA para a leitura do que uma pessoa fisica ja que algumas pessoas com deficiências preferem e gostam de fazer as coisas sozinhas ou com o minimo de ajuda humana por conta da pena que certas pessoas tem e a tratam diferentes


Backlog

Documento com problema, público-alvo, objetivo da IA e requisitos da solução	
	leitura de textos e documentação da fonte	
	Fazer análise exploratória inicial 	Análise dos dados, distribuição das classes, exemplos e identificação de problemas	
	Escolher algoritmo de baseline	Definição do primeiro algoritmo/modelo a ser utilizado e justificativa da escolha	
	Treinar primeiro modelo	Modelo base treinado utilizando o dataset preparado

  Database

data set sobre reconhecimento óptico de caracteres (OCR).
  IAM Handwriting Database ou FUNSD Dataset


Como pode ser tratavel com IA

dificuldade de acesso a informações escritas por pessoas com deficiência visual.

  desenvolver um sistema capaz de reconhecer textos presentes em imagens utilizando OCR e posteriormente convertê-los em áudio, permitindo que o usuário tenha acesso às informações de forma independente.


  Tipos de problema

   O projeto se enquadra principalmente como classificação, pois a IA precisa identificar e classificar os caracteres, palavras ou informações presentes em uma imagem para determinar qual texto está sendo apresentado.


   Entrada e saida de dados

   O usuário utiliza a câmera do celular para fotografar o texto.

Um modelo de OCR identifica os caracteres presentes na imagem e transforma a imagem em texto digital.

A IA pode organizar, corrigir ou resumir o conteúdo reconhecido.

O texto é convertido em fala usando tecnologia de Text-to-Speech (TTS).

A pessoa recebe a informação por áudio, sem precisar enxergar o texto.


Comparativo


https://www.microsoft.com/en-us/ai/seeing-ai?utm_source=chatgpt.com

Microsoft Seeing AI  —  Microsoft	Aplicativo que utiliza IA e a câmera do celular para reconhecer e ler textos, documentos, placas e anotações em voz alta para pessoas cegas ou com baixa visão; é muito semelhante ao nosso projeto, principalmente na etapa de transformar texto visual em áudio.

https://support.google.com/accessibility/android/answer/9031274?hl=pt&utm_source=chatgpt.com 

Google Lookout	 —   Acessibilidade Android	Aplicativo que utiliza a câmera e visão computacional para reconhecer textos e objetos e fornecer informações por áudio para pessoas cegas ou com baixa visão; assim como nosso projeto, possui um modo específico para apontar a câmera para um texto e ouvi-lo.


Limitações 

Qualidade das imagens: imagens borradas, escuras ou com baixa resolução podem dificultar o reconhecimento do texto.
Tipo de texto: o modelo pode apresentar maior dificuldade com textos manuscritos, fontes diferentes, caracteres especiais ou textos muito pequenos.
Dataset limitado: o desempenho do modelo dependerá da quantidade, qualidade e diversidade dos dados disponíveis para treinamento.
Idioma: se o dataset utilizado tiver poucos exemplos em português, o modelo poderá apresentar erros em textos brasileiros.


ATIVIDADE 3

Aprendizado de maquina

    abordagem / como funcionaria no meu projeto / vantagens / desvantagens 

Extraído automaticamente/ a IA identificaria e aprenderia tudo das datasets/ pode reconhecer textos automaticamente sem intervenção humana./ um dataset pequeno ou  de dados historicos                                                                                                                                     de baixa                                                                                                                                  qualidade pode prejudicar o modelo.
                                                                           / novos exemplos podem ajudar o modelo a aumentar sua precisão./treinamento de modelos                                                                                                                                         /mais complexos pode exigir                                                                                                                                          bastante processamento.


 Regras seriam suficientes

 Não, uma solução baseada apenas em regras seria insuficiente para o nosso projeto.
Uma abordagem de regras do tipo “se... então...” funcionaria apenas em situações muito simples e previsíveis. Por exemplo
Se a imagem estiver muito escura, então solicitar ao usuário que tire outra foto.
Porém, o reconhecimento de textos em imagens envolve muitas variações, como diferentes fontes, tamanhos, ângulos, iluminação, caligrafias e fundos. Seria muito difícil criar regras para todas essas situações.


Riscos Tecnicos

Qualidade dos Dados

Os dados têm valores faltantes, inconsistências, ou erros de coleta? Limpeza de dados costuma consumir 60-80% do tempo em projetos reais.

Complexidade vs. Prazo

A abordagem escolhida é realizável dentro do semestre? Um modelo simples bem implementado vale mais que um complexo pela metade.
