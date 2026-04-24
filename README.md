# Processamento_Sinais_I - Prática 1
Durante a realização desta prática de Processamento de Sinais, foram desenvolvidos scripts em Python, executados no ambiente Google Colab, com o objetivo de gerar, analisar e reproduzir diferentes tipos de sinais no domínio do tempo, bem como simular a resposta de sistemas reais a esses sinais.

Inicialmente, foram implementados códigos para geração de sinais senoidais com diferentes frequências. Esses sinais foram representados graficamente e reproduzidos em áudio, permitindo observar tanto sua estrutura temporal quanto sua percepção auditiva. Em seguida, foram gerados sinais do tipo chirp com diferentes perfis de varredura de frequência, possibilitando a análise de como a frequência evolui ao longo do tempo e como isso afeta o som percebido.

Na etapa seguinte, foi realizado o carregamento de arquivos de áudio reais (.wav), utilizando o recurso de upload do Google Colab. Esses sinais foram analisados no domínio do tempo e reproduzidos em diferentes frequências de amostragem, evidenciando os efeitos da alteração da taxa de reprodução sobre a velocidade e a tonalidade do áudio.

Posteriormente, foram carregados dois arquivos adicionais: a resposta ao impulso de um ambiente (banheiro) e o sinal de excitação (som de uma taça). Ambos foram analisados graficamente e reproduzidos. Por fim, foi realizada a convolução entre esses sinais, simulando a propagação do som da taça dentro do ambiente representado pela resposta ao impulso.

Ao abrir e executar o arquivo contendo os códigos no Google Colab, espera-se o seguinte comportamento:

1 - O ambiente solicitará o upload de arquivos de áudio nos momentos apropriados (como handel.wav, h_banheiro.wav e sinal_taca.wav).

2 - Serão exibidos gráficos no domínio do tempo para todos os sinais gerados ou carregados, permitindo a visualização de suas características.

3 - O sistema reproduzirá os sinais de áudio diretamente no navegador, possibilitando a análise auditiva dos resultados.

4 - Nos experimentos com variação da frequência de amostragem, será perceptível a alteração na velocidade e na altura tonal dos sinais.

5 - Na etapa de convolução, será gerado um novo sinal que incorpora as características do ambiente, apresentando reverberação perceptível tanto no gráfico quanto na reprodução sonora.

De forma geral, espera-se que o usuário consiga correlacionar os resultados visuais (gráficos) com os auditivos (reprodução sonora), consolidando a compreensão dos conceitos teóricos abordados, como frequência, amostragem, resposta ao impulso e convolução.
