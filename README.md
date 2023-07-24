
# Exemplo de estrutura de projeto para scripts de Engenharia de Dados

## Introdução

Este repositório tem como finalidade apresentar um exemplo de estrutura para projetos de engenharia de dados, no que diz respeito a projetos de ETL e ingestao de dados. Teve como principal base a postagem do engenheiro de dados [Brij kishore Pandey](https://www.linkedin.com/posts/brijpandeyji_data-dataengineering-activity-7056846859377467392-GtB2/)

## Tecnologias Utilizadas

Todo o repositório foi construido para suporte da linguagem Python

## Arquivos do projeto 
Nessa seção vamos ter uma visão geral de como foi construido o repositório e como podemos entender sua organização:

+ **``𝗰𝗼𝗻𝗳𝗶𝗴/``**: Contém arquivos de configuração para o seu projeto, como detalhes de conexão com o banco de dados, chaves de API ou outras configurações específicas do projeto. Mantém as configurações separadas do código para facilitar as atualizações.

+ **``𝗱𝗮𝘁𝗮/``**: Armazena arquivos de dados brutos e processados. Possui duas subpastas:  **``raw/``** para dados não processados e  **``processed/``** para dados transformados. Garante acesso aos arquivos de dados originais e rastreia as alterações feitas durante o processamento.

+ **``𝗱𝗼𝗰𝘀/``**: Contém a documentação do projeto, como arquivos README, guias do usuário e documentação técnica. Mantém uma documentação detalhada para facilitar a compreensão e a manutenção do projeto.

+ **``𝗲𝘁𝗹/``**: Contém scripts de Extração, Transformação e Carregamento (ETL). Possui três subpastas: **``𝗲𝘅𝘁𝗿𝗮𝗰𝘁/``**,  **``𝘁𝗿𝗮𝗻𝘀𝗳𝗼𝗿𝗺/``** e  **``𝗹𝗼𝗮𝗱/``**, cada uma com scripts correspondentes para extração, transformação e carregamento de dados.

+ **``𝗽𝗶𝗽𝗲𝗹𝗶𝗻𝗲𝘀/``**: Contém scripts de orquestração do pipeline de dados. Esses scripts definem a ordem em que diferentes processos de ETL ou outras etapas de processamento de dados devem ser executados.

+ **``𝘀𝗿𝗰/``** : Armazena o código-fonte do projeto, incluindo scripts de processamento e transformação de dados, funções de utilidade e scripts de validação de dados. Organizado em subpastas: **``𝗱𝗮𝘁𝗮/``**, **``𝘂𝘁𝗶𝗹𝘀/``** e **``𝘃𝗮𝗹𝗶𝗱𝗮𝘁𝗶𝗼𝗻/``**.

+ **``𝘁𝗲𝘀𝘁𝘀/``**: Contém testes unitários e de integração para o projeto. Escrever testes garante que o código funcione como esperado e ajuda a identificar problemas potenciais antes que se tornem problemas importantes.

+ **``.𝗴𝗶𝘁𝗶𝗴𝗻𝗼𝗿𝗲``**: Especifica arquivos e pastas ignorados pelo controle de versão do Git. Evita commits acidentais de determinados arquivos, como arquivos de dados ou arquivos de configuração que contenham informações sensíveis.

+ **``𝗲𝗻𝘃𝗶𝗿𝗼𝗻𝗺𝗲𝗻𝘁.𝘆𝗺𝗹``**: Define as variaveis de ambiente para o projeto, listando os pacotes necessários e suas versões. Gerencia dependências para facilitar a configuração e garantir versões consistentes de pacotes entre os membros da equipe.

+ **``𝗥𝗘𝗔𝗗𝗠𝗘.𝗺𝗱``**: Fornece uma visão geral do projeto, incluindo seu propósito, instruções para configuração e informações de uso. Um arquivo README bem escrito ajuda os membros da equipe e os usuários a entender e utilizar o projeto de forma eficaz.

## Fonte

Este repositório foi todo construido baseado na postagem do engenheiro de dados [Brij kishore Pandey](https://www.linkedin.com/posts/brijpandeyji_data-dataengineering-activity-7056846859377467392-GtB2/), todo crédito deve ser referenciado à Brij kishore Pandey

## Considerações

Baseado nesta postagem foi possivel aprender mais sobre como arquitetar os codigos que são utilizados nos projetos de engenharia de dados, bem como sua organização e clareza na hora de construir pipelines. Próxima etapa seria incluir o projeto na biblioteca cookiecutter para que a criação de templates seja feita de forma automática 
