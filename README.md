## GS-Python-Ocean

## Integrantes

Felipe Ferreira - RM-553680
Joseh Gabriel Trimboli Agra - RM-553094

## Sobre

Este sistema em Python foi desenvolvido para auxiliar no monitoramento da qualidade da água oceânica, coletando, analisando e armazenando dados de diferentes locais. 
    
*Ele serve como uma ferramenta para:*
        
 - Pesquisadores e Cientistas: Coletar dados precisos e organizados sobre a temperatura, salinidade, pH e níveis de poluição em 
        diferentes áreas, permitindo a análise de tendências, o estudo de impactos ambientais e a identificação de áreas críticas.
        
- Organizações de Monitoramento Ambiental: Registrar dados de qualidade da água de forma eficiente e organizada, facilitando o 
        acompanhamento da saúde dos oceanos e a detecção de alterações significativas.
        
- Grupos de Conservação Marinha: Obter dados para avaliar o impacto da poluição e atividades humanas no ecossistema marinho, 
        contribuindo para ações de conservação e políticas de proteção ambiental.
        
- Educadores: Demonstrar a importância da qualidade da água oceânica e promover o interesse em estudos e ações de 
        monitoramento, utilizando um sistema simples e interativo.
        
- Este código, apesar de ser um sistema básico, demonstra o potencial de softwares e ferramentas de código aberto 
        para a pesquisa, o monitoramento e a proteção do meio ambiente. 
        Ele pode ser adaptado e expandido para atender a necessidades específicas de diferentes usuários e projetos.


## Uso do Codigo

O código que criamos é um sistema simples em Python para monitorar a saúde dos oceanos. 
    Ele permite que você colete dados sobre a temperatura, salinidade, pH e nível de poluição 
    da água em diferentes locais, analise esses dados (calculando médias e exibindo um gráfico), 
    e salve os dados em um arquivo CSV para análise posterior.


*Instruções de uso:*

      - 1. Executar o Código:
      
      Salve o código: Abra o codigo no Visual Studio code com Jupyter Notebook.
      Execute o código: Inicie o codigo.
    
      - 2. Fornecer os Dados:
      
      O sistema irá exibir a mensagem: "Digite o nome do local (ou 'sair' para finalizar):".
      Digite o nome do local onde você está coletando os dados (ex: "Baía de Guanabara") e pressione Enter.
      O sistema solicitará a temperatura da água (°C): Digite o valor e pressione Enter.
      Siga o mesmo procedimento para a salinidade (ppm), pH e nível de poluição (ppm).
      Para finalizar a coleta de dados, digite "sair" (em minúsculas) e pressione Enter.
    
       - 3. Visualizar a Análise:
       
      O sistema irá exibir a análise dos dados coletados:
      Local
      Temperatura média (°C)
      Salinidade média (ppm)
      pH médio
      Nível de poluição médio (ppm)
      Em seguida, o sistema mostrará um gráfico de linha com a evolução dos dados coletados.
    
      - 4. Salvar os Dados:
      
      O sistema solicitará: "Digite o nome do arquivo para salvar (ex: dados_oceanos.csv):".
      Digite o nome do arquivo que você deseja usar (ex: dados_oceanos.csv) e pressione Enter.
      O sistema irá salvar os dados em um arquivo CSV na mesma pasta onde o script Python está localizado.
    
      - 5. Visualizar o Arquivo CSV:
      
      Abra o arquivo CSV que você acabou de criar.
      Você encontrará os dados organizados por colunas (Local, Temperatura, Salinidade, pH, Poluição) em linhas separadas.
    
*Exemplo de Interação:*

      Entrada de dados:
      
      Digite o nome do local (ou 'sair' para finalizar): Baía de Guanabara
      Digite a temperatura da água (°C): 25.5
      Digite a salinidade (ppm): 35.2
      Digite o pH: 8.1
      Digite o nível de poluição (ppm): 0.2
      Digite o nome do local (ou 'sair' para finalizar): Praia de Copacabana
      Digite a temperatura da água (°C): 26.1
      Digite a salinidade (ppm): 34.9
      Digite o pH: 8.0
      Digite o nível de poluição (ppm): 0.1
      Digite o nome do local (ou 'sair' para finalizar): sair
    
      - Análise dos Dados:
      - Temperatura média: 25.80 °C
      - Salinidade média: 35.05 ppm
      - pH médio: 8.05
      - Nível de poluição médio: 0.15 ppm
      
      [Gráfico de linha com os dados]
      
Agora salve os dados obtidos em csv:*
Digite o nome do arquivo para salvar (ex: dados_oceanos.csv): dados_oceanos.csv
Dados salvos em dados_oceanos.csv

# Explicaçao do código:
      Pandas para manipulação de DataFrames e matplotlib.pyplot para visualização.
      
      Funções:
      
      coletar_dados(): Coleta os dados do usuário através de input(), valida se a entrada é numérica e organiza os dados em um DataFrame.
      
      analisar_dados(): Realiza cálculos de média e exibe as informações em texto e um gráfico de linha com todas as variáveis.
      
      salvar_dados(): Permite que o usuário escolha o nome do arquivo e salva os dados em formato CSV.
      
      main(): Função principal que chama as outras funções em sequência.

# Funcionalidades do código:

    Variáveis: temp, salinidade, ph, poluicao, dados, df, etc.
    
    Tipos de Dados: float para números decimais, str para texto, list para listas de dados, DataFrame para tabelas de dados.
    
    Condicionais (if, elif, else): Dentro da função coletar_dados() para verificar se o usuário digitou sair.
    
    Loops (while, for): while True na função coletar_dados() para coletar dados até que o usuário digite sair.
    
    Manipulação de Listas e Strings: append() para adicionar elementos à lista dados, input() para ler dados do
    usuário (strings), float() para converter strings para números decimais.
    
    Funções: coletar_dados(), analisar_dados(), salvar_dados(), main().
    
    Listas: dados para armazenar os dados coletados. 
    
    Arquivos: to_csv() para salvar os dados em um arquivo CSV.

# Video Explicativo
Link Youtube:https://youtu.be/xZugvXmOcWo
