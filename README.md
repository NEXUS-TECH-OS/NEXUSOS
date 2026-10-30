# NEXUS TECH OS

Sistema operacional empresarial para assistência técnica, com foco em ordens de serviço, evidências fotográficas, estoque e financeiro operacional.

> **Estado:** preparação técnica. Ainda não há implementação de produto.

## Identidade e escopo

- O NEXUS é totalmente independente do NERO. Não existe ligação entre os produtos.
- O primeiro MVP é para uso interno, em uma operação no Brasil.
- Idioma: pt-BR. Moeda: BRL. Fuso de exibição: America/Sao_Paulo.
- As decisões jurídicas, de privacidade e contábeis aplicáveis ao produto serão validadas antes do go-live.

## Documentação

- [Especificação técnica e decisões confirmadas](docs/NEXUS_ESPECIFICACAO_TECNICA.md)
- [Backlog por fases e critérios de aceite](docs/NEXUS_BACKLOG.md)
- [Matriz regulatória preliminar — Brasil](docs/NEXUS_REGULATORIO_BRASIL.md)
- [Registro de avaliação open source](docs/OPEN_SOURCE_REGISTER.md)

## Princípios de engenharia

- Segurança e autorização validadas no servidor; isolamento por tenant preparado desde o início.
- Dados financeiros e eventos de auditoria preservados por registros compensatórios, sem apagamento silencioso.
- Evidências fotográficas privadas por padrão, minimizadas, auditáveis e regidas por política de retenção documentada.
- Nenhuma credencial, dado real de cliente ou segredo deve ser incluído neste repositório.
- Nenhuma dependência deve ser adotada sem avaliar licença, manutenção e avisos de segurança.
- Não publicar release nem conectar serviços pagos sem revisão e autorização do responsável.

## Como começar

Leia a especificação técnica e o backlog antes de iniciar implementação. A fundação de produto ainda depende de revisão do MVP, definição dos acessos administrativos e provisionamento aprovado dos serviços necessários.

Este repositório público não implica concessão de licença open source. Licença de distribuição ainda não foi definida.
