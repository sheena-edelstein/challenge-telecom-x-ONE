📡 Telecom X - Retenção de Clientes | Inteligência em Churn
Este projeto foi desenvolvido como parte do Desafio de Análise de Dados da Telecom X. O objetivo principal é transformar dados brutos de clientes em insights estratégicos para combater a evasão (Churn), um dos indicadores mais críticos para a saúde financeira de empresas de telecomunicações.

🎯 O Desafio de Negócio
A diretoria da Telecom X notou um aumento nos cancelamentos e precisa de uma resposta rápida: quais comportamentos indicam que um cliente está prestes a sair? Minha missão foi atuar como Assistente de Dados para realizar uma Análise Exploratória (EDA) profunda, identificando os gatilhos de evasão e fornecendo recomendações Data-Driven para o time de Sucesso do Cliente.

🔍 O Que Foi Analisado?
O notebook realiza todo o processo de ETL (Extração, Transformação e Carga) consumindo dados diretamente via API. As principais frentes de investigação foram:

📊 Perfil Financeiro: Análise de faturas mensais e criação da métrica de Custo Diário.

🛠️ Ciclo de Vida: Estudo do tenure (tempo de contrato) para identificar quando a evasão é mais comum.

📡 Ecossistema de Serviços: Avaliação de como a contratação de múltiplos serviços (Internet, Streaming, Suporte) influencia a fidelidade.

💳 Métodos de Pagamento: Relação entre a forma de cobrança e a taxa de rotatividade.

💡 Principais Descobertas e Insights
Após cruzar as variáveis e analisar as distribuições, chegamos aos seguintes diagnósticos:

🛡️ Fator de Retenção (Multi-serviços): Clientes que utilizam 5 ou mais serviços integrados apresentam uma taxa de churn significativamente menor. O efeito de "ecossistema" atua como uma barreira natural à saída, aumentando o valor percebido.

🚨 Zona de Risco (Primeiro Semestre): Identificamos que a maioria dos cancelamentos ocorre nos primeiros 6 meses de contrato, especialmente em planos "Mês a mês" e cobranças via Cheque Eletrônico. O custo elevado da fatura mensal é o principal motivo alegado para a interrupção do serviço.

Veredito: A recomendação estratégica enviada à gestão foi focar em campanhas de migração para planos anuais e oferecer benefícios para a adesão ao débito automático, reduzindo a fricção e aumentando a previsibilidade da receita.

📊 Visualizações
<img width="1114" height="490" alt="image" src="https://github.com/user-attachments/assets/5558269c-7934-40b9-8347-1b3f12b38cbc" />
<img width="1489" height="1190" alt="image" src="https://github.com/user-attachments/assets/ea14af99-bd6e-4c0b-8540-e83d2b4d1ee0" />
<img width="1790" height="490" alt="image" src="https://github.com/user-attachments/assets/8ec2f4e3-2adc-43ff-bb53-e3aab0ab990c" />
<img width="873" height="779" alt="image" src="https://github.com/user-attachments/assets/9ccf1dd0-28ce-4cec-a4c4-59939e9c325c" />
<img width="846" height="547" alt="image" src="https://github.com/user-attachments/assets/bfc3e77d-090f-4b91-ac45-84dbd3905b6e" />


💻 Como Executar o Projeto
Faça o download do arquivo TelecomX_Churn_Analysis.ipynb.

Acesse o Google Colab ou abra em seu Jupyter Notebook local.

Importe o notebook para o ambiente.

Execute todas as células.
Nota: O código já está configurado para buscar os dados diretamente da API oficial no GitHub via requests e json_normalize.

🚀 Minha Experiência
Trabalhar neste projeto da Telecom X foi um divisor de águas. Se no desafio anterior eu aprendi a organizar vendas, neste eu aprendi a decifrar o comportamento humano através dos números.

Consegui dominar a manipulação de arquivos JSON aninhados e, pela primeira vez, utilizei matrizes de correlação para provar hipóteses de negócio. Ver que uma métrica criada por mim — como a conta diária — pode ajudar uma empresa a não perder dinheiro me deu a confiança que eu precisava para seguir firme na trilha de Ciência de Dados!
