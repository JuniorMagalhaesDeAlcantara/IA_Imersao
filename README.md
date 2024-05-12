Sistema de Estimativa de Probabilidade de Dengue com Google Generative AI

Este projeto utiliza a API do Google Generative AI para estimar a probabilidade de um usuário ter dengue com base nos sintomas relatados. Observação: Este sistema é apenas para fins informativos e educacionais. Ele não substitui o diagnóstico médico profissional.

Como Funciona

Coleta de Sintomas: O sistema faz uma série de perguntas ao usuário sobre sintomas comuns da dengue. Geração de Prompt: Com base nas respostas do usuário, o sistema gera um prompt em inglês para a API do Google Generative AI. Chamada à API: O sistema envia o prompt para o modelo text-bison-001 da API do Google Generative AI. Interpretação da Resposta: O sistema interpreta a resposta da API e tenta extrair um valor numérico que represente a probabilidade de dengue. Exibição da Probabilidade: O sistema exibe a probabilidade estimada para o usuário.

Limitações

Precisão Limitada: O modelo text-bison-001 não foi treinado especificamente para diagnósticos médicos. Sua precisão para estimar a probabilidade de dengue é limitada. Idioma: O modelo funciona melhor com prompts em inglês. A precisão em português pode ser menor. Natureza Informativa: Este sistema é apenas para fins informativos e educacionais. Ele não substitui o diagnóstico médico profissional.

Como Usar

Instale a biblioteca google-generativeai: pip install google-generativeai Use code with caution. Bash

Obtenha uma chave de API do Google Cloud: Acesse https://cloud.google.com/ e crie um projeto. Ative a API do Google Generative AI. Crie uma chave de API e copie-a. Substitua 'SUA_API_KEY' no código pela sua chave de API.

Execute o código: python dengue_estimator.py Use code with caution. Bash

Próximos Passos

Aprimorar o prompt: Criar prompts mais específicos e direcionados para melhorar a precisão da resposta da API. Explorar outros modelos: Pesquisar modelos da API do Google Generative AI ou APIs de IA especializadas em saúde que possam fornecer resultados mais precisos. Treinar um modelo especializado: Treinar um modelo de aprendizado de máquina com dados médicos reais em português para obter resultados mais confiáveis para o público brasileiro.

Aviso: Este sistema não deve ser utilizado para autodiagnóstico ou automedicação. Consulte um profissional de saúde para qualquer problema de saúde.
