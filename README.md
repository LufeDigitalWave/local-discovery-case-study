# Diretório e descoberta conversacional

Case técnico anonimizado sobre busca de serviços em diretório, atendimento conversacional e gestão de conteúdo publicado.

> Publicação documental. Não contém diretório real, registros comerciais, conversas, arquivos de mídia, workflows importáveis ou integrações ativas.

## Problema

Uma busca em linguagem natural precisa produzir resultados relacionados à necessidade da pessoa, sem inventar informações do diretório. Ao mesmo tempo, registros publicados precisam de processos para atualização, reivindicação, moderação e remoção.

## Escopo representado

Fluxos de busca, sessão conversacional, entrada de cadastros, reivindicação de registros e publicação de mídia. A organização do projeto de origem contém workflows, migrations e componentes web; o conteúdo desses artefatos não é copiado aqui.

## Stack identificada

n8n para orquestração, PostgreSQL com extensão pgvector, componentes de backend em Python e interface web. A presença desses elementos foi identificada na estrutura e nos arquivos de configuração, sem validar integrações ou desempenho.

## O que discutir numa entrevista

- Como manter respostas vinculadas ao conteúdo consultado.
- Como distinguir um cadastro informado de um registro verificado.
- Como controlar publicação, moderação e remoção de mídia.
- Como evitar que dados recuperados se tornem instruções para o agente.

Consulte a [arquitetura e o roteiro de validação](ARCHITECTURE.md).

## Limites

Não há nomes de estabelecimentos, localidades, contatos, pessoas, documentos, prompts privados, conversas ou métricas. O diagrama é ilustrativo e não demonstra eficácia de busca ou resistência comprovada a ataques.
