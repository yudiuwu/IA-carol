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

  Abordagens comparativas
  
| Abordagem | Como Funcionaria | Vantagens | Desvantagens | Viabilidade |
|---|---|---|---|---|
| Aprendizado de Máquina | Aprende a reconhecer textos em imagens usando dados de treinamento e OCR. | Reconhece diferentes fontes e formatos. Pode melhorar com mais dados. | Exige dados históricos rotulados e pode apresentar risco de viés. | Alta — principal abordagem. |
| Sistemas Especialistas | Utiliza regras para tomar decisões, como verificar se a imagem está muito escura. | Fácil de implementar, totalmente explicável e útil para controlar situações específicas durante a leitura. | Não captura padrões sutis e é difícil criar regras para todas as formas de texto e imagens. | Média — viável como complemento ao OCR, mas não como solução principal. |              
                 


 Regras seriam suficientes

 Não, uma solução baseada apenas em regras seria insuficiente para o nosso projeto.
Uma abordagem de regras do tipo “se... então...” funcionaria apenas em situações muito simples e previsíveis. Por exemplo
Se a imagem estiver muito escura, então solicitar ao usuário que tire outra foto.
Porém, o reconhecimento de textos em imagens envolve muitas variações, como diferentes fontes, tamanhos, ângulos, iluminação, caligrafias e fundos. Seria muito difícil criar regras para todas essas situações.



  Riscos Tecnicos

 Falta De Dados
O projeto utilizará dados para reconhecimento de textos por OCR. Existe o risco de o dataset escolhido possuir poucos exemplos de textos em português ou pouca variedade de fontes, tamanhos e tipos de escrita.

 Desbalanceamento De Dados

Existe o risco de o dataset possuir uma quantidade muito maior de determinados tipos de caracteres, fontes ou formatos de texto do que outros. Fazendo o projeto ter desempenhos menores em alguns formatos de textos menos apresentados é desempenho melhor em textos mais populares
Qualidade dos Dados



 Complexidade vs. Prazo

A abordagem escolhida é realizável dentro do semestre? Existe o risco de tentar desenvolver um modelo de OCR muito complexo e não conseguir concluir todas as etapas dentro do prazo. Por isso, será priorizado um modelo funcional e adequado ao objetivo do projeto, em vez de uma solução excessivamente complexa.

 Qualidade dos dados

 As imagens utilizadas no treinamento e nos testes podem apresentar problemas como baixa resolução, iluminação inadequada, desfoque, diferentes ângulos ou textos manuscritos, deixando muito dificil a leitura da imagem.

  Outros riscos possíveis
Existe o risco de o dataset possuir poucos exemplos em português.
Existe o risco do OCR ser enviado para a leitura TTS é ter uma chance acabar tendo informações incorretas sendo passadas sendo necessário vários testes antes

   Atualização do escopo

 Previsão para 6 meses

Pretendo entregar
captura de imagens de textos utilizando a câmera do dispositivo;
Reconhecimento dos textos presentes nas imagens utilizando OCR e técnicas de Aprendizado de Máquina;
Conversão do texto reconhecido em áudio utilizando Text-to-Speech (TTS);
Validação básica da qualidade da imagem, identificando situações como baixa iluminação ou dificuldade de reconhecimento;
Testes com diferentes tipos de textos, fontes e condições de imagem;
Desenvolvimento de uma interface simples e acessível para utilização do sistema

Não acho que vou conseguir a tempo do prazo

Reconhecer perfeitamente qualquer tipo de texto ou caligrafia;
Substituir leitores humanos ou profissionais especializados;
Realizar diagnóstico médico ou outras atividades que dependam de interpretação profissional;
Garantir funcionamento perfeito em imagens de baixa qualidade;


Ativ 7

1-

Entradas, processamentos é saídas

Inicio: No meu sistema deve entrar, fotos ou escaneamentos da tela com textos ou algo que o usuário precise "ler"

Processo: É passado a ser convertido em OCR é TTS

Final: Vira áudio feito pela IA

Remoção: dados iguais, imagens repetidas ou desfocadas é null



Supervisionado, Não Supervisionado ou Por Reforço

Acredito que o supervisionado seja o mais adequado já que ele vai aprender é ter as respostas já das imagens que ele vai transcrever



Planejamento é divisão de dados

usar cross-validation por que o dataset não é tão grande com mais de mil dados

Aleatória, por que nosso data set não depende especificamente de datas, elas não interfeririam diretamente
Utilizar stratify já que existe a chance de repetir dados seja imagens ou escritas 

