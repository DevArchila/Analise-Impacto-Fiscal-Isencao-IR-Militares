# Impacto fiscal da isenção do Imposto de Renda para militares das Forças Armadas

## Resumo

Este projeto analisa o impacto fiscal de uma proposta de isenção do Imposto de Renda para militares das Forças Armadas (PL 2.557/2026).
A ideia foi responder, com base em dados, se existe algum cenário de isenção que gere menor custo para os cofres públicos em comparação com uma proposta mais ampla.

A análise foi feita com dados públicos extraídos da API do Portal da Transparência do Governo Federal. A partir deles, foi feita a organização, limpeza e exploração da base
para estimar o impacto da isenção em diferentes cenários, considerando faixas salariais e situações funcionais distintas.

## Objetivo

A proposta de isenção do Imposto de Renda para militares é um tema com impacto direto nas contas públicas.
Em vez de olhar para isso apenas de forma intuitiva, este projeto buscou colocar os números no centro da discussão.

A pergunta principal foi:

Existe um cenário de isenção do Imposto de Renda para militares das Forças Armadas que tenha menor impacto fiscal para os cofres públicos?

## Metodologia

O projeto foi desenvolvido em algumas etapas:

1. Extração dos dados por meio da API do Portal da Transparência
2. Limpeza e tratamento da base
3. Identificação e remoção de registros inconsistentes
4. Análise da distribuição dos valores pagos
5. Simulação de cenários alternativos de isenção
6. Interpretação dos resultados com foco no impacto fiscal

Ao longo da análise, foram utilizadas informações como soldo bruto, soldo líquido, imposto de renda, pensão militar, situação funcional e cargo.

Também foi necessária uma limpeza cuidadosa dos dados, já que a base apresentava registros duplicados e alguns casos que poderiam distorcer os resultados finais.
Esses registros foram tratados com critérios objetivos, buscando preservar a coerência da análise.

## Resultados

A análise mostrou que a proposta de isenção tem um impacto fiscal relevante quando aplicada de forma ampla (abrangendo militares da ativa, reserva/reformados, e pensionistas).

Por outro lado, cenários mais restritos, especialmente aqueles limitados a faixas salariais menores ou apenas a militares da ativa, apresentam impacto significativamente menor.

Isso mostra que o desenho da política faz diferença no custo final para o Estado.

## O que este projeto mostra

Este projeto não foi feito apenas para aplicar código. A intenção foi desenvolver uma forma mais analítica de trabalhar com dados, desde a definição do problema até a interpretação dos resultados.

Ele mostra a aplicação de conceitos como:

- consumo de dados públicos
- tratamento e limpeza de base
- análise exploratória
- simulação de cenários
- comunicação de resultados

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- API do Portal da Transparência

## Limitações da análise

Este projeto foi construído com base nos dados disponíveis no Portal da Transparência no momento da coleta.

Por isso, os resultados representam uma estimativa baseada na base analisada e não devem ser interpretados como o valor final oficial da medida.

Além disso, a análise considera apenas os dados das Forças Armadas federais, sem incluir possíveis efeitos indiretos sobre consumo, arrecadação ou comportamento dos contribuintes.

## Como reproduzir

Para reproduzir este estudo, basta abrir o notebook, executar as células na ordem apresentada e verificar os resultados obtidos em cada etapa.

## Observação final

Este projeto faz parte do meu processo de transição para a área de dados e foi desenvolvido com foco em análise real, limpeza de dados e tomada de decisão baseada em evidências.

Linkedin: www.linkedin.com/in/samuelarchila
