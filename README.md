# Operacao-farmaceutica
Otimização de custos de uma insdustria farmaceutica com cloud - DIO


RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 30/01/2026
Empresa: Abstergo Industries
Responsável: Lauro Pin

Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado pela equipe de consultoria em Cloud Computing.
O objetivo do projeto foi elencar e propor 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos, considerando que a empresa não possuía nenhuma solução em nuvem previamente implementada.

A Abstergo Industries atua como um hub de distribuição farmacêutico, se comunicando com diversos parceiros e sistemas externos, o que exige alta disponibilidade, controle financeiro rigoroso e uso eficiente de recursos computacionais.

Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma focada diretamente na redução de custos operacionais, evitando desperdícios e melhorando o controle financeiro desde o início da adoção da nuvem.

Etapa 1:
Nome da ferramenta: AWS Budgets
Foco da ferramenta: Controle e previsibilidade de custos
Descrição de caso de uso:
O AWS Budgets será utilizado para definir limites de gastos mensais da conta AWS da Abstergo Industries. Alertas automáticos serão configurados para notificar a equipe financeira e técnica sempre que os custos atingirem percentuais pré-definidos (ex.: 70%, 90% e 100% do orçamento).
Essa abordagem evita gastos inesperados, muito comuns em ambientes cloud recém-implantados, garantindo controle financeiro imediato.

Etapa 2:
Nome da ferramenta: AWS Trusted Advisor
Foco da ferramenta: Otimização de custos e boas práticas
Descrição de caso de uso:
O AWS Trusted Advisor será utilizado para identificar recursos subutilizados ou ociosos, como instâncias EC2 superdimensionadas, volumes EBS não utilizados e serviços ativos sem necessidade.
A ferramenta fornece recomendações práticas que permitem reduzir custos rapidamente, sem impacto negativo na operação, além de orientar boas práticas desde o início da arquitetura em nuvem.

Etapa 3:
Nome da ferramenta: Amazon S3 Intelligent-Tiering
Foco da ferramenta: Otimização automática de custos de armazenamento
Descrição de caso de uso:
A Abstergo Industries lida com grande volume de arquivos, como relatórios, documentos regulatórios e dados de integração com parceiros.
O S3 Intelligent-Tiering será utilizado para armazenar esses arquivos sem a necessidade de conhecer previamente o padrão de acesso, movendo automaticamente os dados entre camadas de custo conforme o uso.
Isso elimina a necessidade de decisões manuais e garante redução contínua de custos de armazenamento.

Conclusão

A implementação das ferramentas na empresa Abstergo Industries tem como resultado esperado a redução imediata de custos, maior controle financeiro, eliminação de desperdícios e adoção de boas práticas desde o início da jornada em nuvem.

Com o uso de AWS Budgets, AWS Trusted Advisor e Amazon S3 Intelligent-Tiering, a empresa passa a operar em um ambiente mais previsível, escalável e financeiramente sustentável, aumentando a eficiência operacional e a produtividade.

Recomenda-se a continuidade da utilização das ferramentas implementadas e a avaliação futura de novos serviços AWS que possam ampliar ainda mais a otimização de custos e a maturidade da arquitetura cloud da empresa.

Anexos

Guia de configuração do AWS Budgets

Relatório de recomendações do AWS Trusted Advisor

Documentação do Amazon S3 Intelligent-Tiering

Assinatura do Responsável pelo Projeto: Lauro Pin
