---
description: Um checklist para apoiar os cientistas de dados em suas análises 
tags: ciência_de_dados análise_exploratória
author: Henrique Arutin Cavalcanti de Albuquerque
title: Checklist para Análise Exploratória de Dados
---

Work in progress...

A partir de cursos, de experiência em análises exploratórias de dados e da gestão de equipes de cientistas de dados, criei este checklist para que você possa evitar erros básicos ao iniciar uma análise exploratória de dados. Espero que possa ajudá-lo(a) nessa tarefa e contribuir para perdermos menos tempo, em geral :). Caso tenha sugestões de modificações para este checklist, por favor envie-me uma mensagem no twitter (@HenriqueArutin).

- Passo 1: Comece toda análise com uma pergunta mensurável, que parece poder ser respondida com a análise e que possa gerar uma ação quando você tiver a resposta.

- Passo 2: Procure o primeiro conjunto de dados para responder sua pergunta.

- Passo 2.1: Ao receber os dados, verifique se tem as características que você esperava que ele tivesse ANTES de iniciar sua análise exploratória. Alguns itens comuns para verificar são:
- Passo 2.1.1: As varíaveis que você esperava encontrar no dataset estão presentes quando você olha nos metadados ou nos nomes da colunas?
- Passo 2.1.2: O período (datas de início e fim) do dataset está de acordo com o que você precisa para responder sua pergunta?
- Passo 2.1.3: Existe algum problema no arquivo de dados, como: colunas ou linhas desalinhadas, fora de ordem, comentários ou texto no início ou no fim do arquivo que vão dificultar o uso de uma ferramenta analítica?
- Passo 2.1.4: Existe algum problema de sigilo ou segurança da informação com a qual você está lidando para que precise controlar os acessos, ocultar ou remover dados sensíveis do dataset (ex.: números de cartão de crédito, informações de saúde, PII - Personal Identifiable Information, etc.)?
- Passo 3: Faça alguns gráficos para ter uma noção geral do comportamento dos seus dados. Você decide qual tipo de gráfico faz mais sentido para o dado que está analisando: histogramas, boxplots, mapas, scatter plots, etc. O importante é analisar o gráfico para verificar que os dados estão de acordo com o comportamento que você esperava, para identificar algo que você não tinha previsto antes ou para identificar que a base está com problemas ou que faltam mais bases para ter uma visão completa.
- Passo 4: Tente criar a primeira resposta simples para a pergunta que você tinha quando iniciou. Neste ponto você pode criar um primeiro modelo básico que já traga uma resposta ou descobrir que a pergunta precisa ser modificada.
