# Smartflow

![Imagem do WhatsApp de 2023-12-03 à(s) 12 24 33_52c79111](https://github.com/FdcDelCaro/Smartflow/assets/121201811/64ff74bc-5480-46a1-9b2a-81af7c378f83)

# Equipe

Felipe Del Caro: Desenvolvedor Back-End, Testes 
Daniele Kadanus: Desenvolvedor Back-End e front-end

# Descrição

"Smartflow" é, a princípio, um aplicativo para Android que permite ao usuário controlar seu consumo de água em m³ e acompanhar os valores da sua fatura até o momento do cálculo. Ele armazena o histórico de consumo e, com base nesse histórico, tem a capacidade de ajudar na detecção de possíveis vazamentos. O objetivo principal é ensinar como ler o hidrômetro e compreender a fatura.

No primeiro uso, solicita a leitura anterior, que pode ser obtida na fatura; em seguida, pede a leitura atual do hidrômetro. Após a inserção desses dados pelo usuário, realiza o cálculo e exibe na segunda tela o valor exato da fatura até o momento, com base nos valores da Sanepar. Também apresenta uma lista do consumo até aquele momento. Além disso, possui a função de ensinar o usuário a ler seu hidrômetro e fatura.

# Justificativa

A compreensão da fatura de água e o monitoramento do consumo representam 
desafios significativos para os clientes da Sanepar. A proposta de desenvolvimento 
do aplicativo SmartFlow surge como uma solução inovadora para enfrentar essas 
dificuldades, trazendo benefícios tanto para os clientes como para a própria 
empresa.  
O projeto visa atender aos Objetivos de Desenvolvimento Sustentável do Brasil (ODS 6: Água Potável e Saneamento e ODS 11: Cidades e Comunidades Sustentáveis) contribuindo para a construção de um futuro sustentável.
Para os clientes, o SmartFlow oferece uma ferramenta intuitiva que facilita o 
acompanhamento do consumo de água e a compreensão da fatura mensal. Ao 
inserirem as leituras do hidrômetro, os usuários poderão identificar áreas de 
desperdício, adotar medidas para reduzir o consumo e, consequentemente, 
economizar financeiramente. Com informações claras e acessíveis sobre o consumo 
ao longo do tempo, os clientes serão capacitados a tomar decisões mais 
conscientes e sustentáveis em relação ao uso da água. Dessa forma, o aplicativo 
promove a consciência ambiental e contribui para a preservação dos preciosos 
recursos hídricos. 

Além disso, ao fornecer uma ferramenta intuitiva e acessível para os 
clientes acompanharem e compreenderem seu consumo de água, reduzirá
a desinformação e, consequentemente, a necessidade de  deslocamentos desnecessários aos atendimentos presenciais. 
 
Em suma, a pesquisa para o desenvolvimento do aplicativo SmartFlow justifica-se 
pela necessidade de facilitar o acompanhamento e compreensão da fatura de água

# Quadro de visão
![QuadroVisaoProjeto_page-0001](https://github.com/FdcDelCaro/Smartflow/assets/121201811/18ad062f-c179-4281-a4d3-e3c314badbf5)

# Estado da Arte

Com base na investigação realizada por Danielle Kadanus e Felipe Del Caro sobre projetos similares ao seu, que visam o controle financeiro do consumo de água através de aplicativos, foi seguida uma metodologia estruturada:

Identificação de Projetos Semelhantes: Iniciaram a pesquisa verificando se existiam outros projetos com propósitos comparáveis ao deles.
Estabelecimento de Critérios de Inclusão e Exclusão: Definiram critérios para selecionar os estudos apropriados, priorizando artigos em língua portuguesa, focados em aplicativos gratuitos para controle de consumo de água.
Definição das Informações a serem Extraídas: Determinaram quais dados deveriam ser extraídos dos estudos selecionados para categorizá-los.
Avaliação dos Estudos Selecionados: Analisaram os estudos encontrados, descartando os que não se encaixavam nos critérios estabelecidos.
Interpretação dos Resultados: Compreenderam e interpretaram os dados coletados.
Apresentação da Revisão/Síntese do Conhecimento: Apresentaram a síntese do conhecimento obtido.
Ao revisararmos os estudos, encotramos dois trabalhos relevantes:

"Medidor de Consumo de Água e Energia Residencial com Monitoramento Remoto"

Foco no monitoramento remoto de água e energia usando um Raspberry Pi.
Não se concentra no reconhecimento facial.
"Controle de Consumo de Água Baseado em Reconhecimento Facial"

Visa controlar o consumo de água por meio do reconhecimento facial.
Utiliza essa tecnologia para gerenciar o fluxo de água e promover economia de recursos.
O projeto de Danielle e Felipe alinha-se com essa pesquisa, concentrando-se no desenvolvimento de um aplicativo para dispositivos Android. O objetivo é simplificar a compreensão do consumo de água, permitindo aos clientes inserir leituras do hidrômetro e calcular automaticamente o consumo.

Embora haja semelhanças com os trabalhos analisados, o projeto deles se destaca por sua abordagem prática. Não apenas fornece informações claras sobre o consumo de água, mas também reduz a desinformação e a necessidade de atendimentos presenciais. Isso responde diretamente ao problema identificado de alto volume de atendimentos devido à falta de compreensão das faturas de água.

O projeto não só promove a conscientização sobre o consumo consciente de água, mas também aprimora a eficiência e a experiência do cliente. Pode simplificar a vida dos usuários, evitando deslocamentos desnecessários e facilitando o acompanhamento do consumo de água. Representa, portanto, uma abordagem prática e inovadora para o problema identificado na pesquisa.


# MVP

Tela de Configuração Inicial:

Solicitação da leitura anterior do medidor, que pode ser obtida na fatura.
Instruções claras sobre como encontrar e inserir essa informação.
Registro da Leitura Atual:

Interface para inserção da leitura atual do hidrômetro pelo usuário.
Cálculo e Exibição do Consumo:

Função para calcular o consumo de água entre a leitura anterior e a atual.
Mostrar o consumo em m³ e em valores monetários aproximados, com base nos dados da Sanepar.
Histórico de Consumo:

Uma seção para exibir o histórico de consumo do usuário, detalhando leituras anteriores e atuais, juntamente com os valores correspondentes.
Detecção de Possíveis Vazamentos:

Um recurso simples que alerta ou sugere a possibilidade de vazamentos com base nas variações incomuns de consumo.
Tutorial e Orientações:

Seção dedicada a ensinar aos usuários como interpretar os números do hidrômetro, entender a fatura e como usar efetivamente o aplicativo.
Este MVP prioriza a funcionalidade básica de registrar leituras, calcular o consumo e fornecer informações úteis ao usuário, como histórico e possíveis alertas de vazamento. Além disso, enfatiza a importância do aspecto educativo, ajudando os usuários a compreenderem melhor seus hábitos de consumo de água e os dados apresentados na fatura.

# Protótipo
https://app.quant-ux.com/#/simulate.html?h=a2aa10al8Vfzdn5GZx77KjPMyXNpyc3aDzwkalsdYgIdaLSL4fyblX7vSShG&log=false&qr=true&live=true

# Gestão do smartflow
https://trello.com/invite/b/ReDOOJyF/ATTI154ff3f4630c43b4e196b1f7aab1543107D7CCED/gestao-do-app-smartflow

# Contexto da Aplicação da Entrevista:

A pesquisa de identificação e conscientização do problema foi aplicada através de formulário eletrônico (https://forms.gle/frWaNogetFp1rZSL8), distribuído através de grupos de contato no WhatsApp, no período entre 27 de novembro a 02 de dezembro de 2023 e foram coletadas 58 respostas.
As respostas foram obtidas de clientes da Sanepar e potenciais usuários do aplicativo SmartFlow. A coleta de dados foi realizada de forma online, possivelmente através de e-mails, redes sociais ou plataformas digitais, visando compreender as percepções, necessidades e disposição dos clientes em relação ao controle de consumo de água e a compreensão das faturas.

Ideias e Insights Evidenciados:

Necessidade de Compreensão da Fatura: Uma parcela significativa dos respondentes verifica sua fatura de água mensalmente, porém, uma parte considerável enfrenta dificuldades em compreendê-la.

Aceitação e Utilidade do SmartFlow: A maioria dos entrevistados expressou interesse e disposição em utilizar o aplicativo SmartFlow para monitorar seu consumo de água, compreender melhor suas faturas e identificar vazamentos ou picos anormais de consumo.

Potencial para Ampliação do Aplicativo: Algumas sugestões de melhoria foram oferecidas, como a expansão do aplicativo para auxiliar condomínios no rateio individualizado dos gastos de água e a inclusão de ferramentas educativas, como simulações de consumo.

Conscientização Ambiental e Sustentabilidade: A percepção de que o aplicativo poderia contribuir para a conscientização sobre o consumo consciente de água e práticas sustentáveis foi amplamente reconhecida pelos entrevistados.

Relacionamento com os Objetivos de Desenvolvimento Sustentável do Brasil:

O aplicativo SmartFlow está diretamente alinhado com diversos Objetivos de Desenvolvimento Sustentável (ODS) do Brasil, especialmente:

ODS 6: Água Potável e Saneamento: O aplicativo visa promover o uso consciente da água, ajudando os usuários a monitorar e reduzir o consumo, contribuindo para a gestão sustentável dos recursos hídricos.

ODS 11: Cidades e Comunidades Sustentáveis: Ao fornecer uma solução tecnológica que melhora a compreensão das faturas de água e incentiva práticas sustentáveis, o SmartFlow colabora para o desenvolvimento de comunidades mais sustentáveis.

Pontos Positivos Observados:

Alta Aceitação e Interesse: A grande maioria dos entrevistados mostrou interesse em utilizar o aplicativo, destacando sua utilidade para compreensão da fatura e monitoramento do consumo.

Contribuição para a Conscientização: Evidências sugerem que o aplicativo pode efetivamente aumentar a consciência sobre o consumo de água e suas implicações ambientais.

Pontos Negativos Observados:

Necessidade de Explicação Detalhada: Alguns respondentes expressaram a necessidade de uma explicação mais detalhada sobre o funcionamento do aplicativo, indicando possíveis pontos de confusão ou falta de clareza na proposta inicial.

Sugestões de Melhoria Variadas: As sugestões para melhorias do aplicativo foram diversas e podem demandar recursos extras de desenvolvimento e implementação.
# Persona 

![1](https://github.com/FdcDelCaro/Smartflow/assets/121201811/bc89c474-89d9-41f0-99fd-5e577e2da03c)


# Storybord
![storyboard](https://github.com/FdcDelCaro/Smartflow/assets/121201811/359378a9-7a3f-4eb4-97d7-686850d664b1)






