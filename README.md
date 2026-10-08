Integrantes
| Nome | GitHub |

Ryan Filipe de Oliveira | Ryan7Filipe

Ricardo Ferreira | ferreirascdb

Emerson José Souza Vieira | emersonjosedev

Ystefani Mariana Gomes |

Alexsandro Souza | Alexsandro83

# PRODART Recife — protótipo de plataforma

Protótipo estático de duas experiências conectadas: guia público de feiras e portal demonstrativo do artesão. Inclui um [plano de dados e implantação](documento/plano-prodart.html) que descreve governança, qualidade, seleção, privacidade, indicadores e etapas de implantação.

## Abrir

Abra `index.html` no navegador. Não há dependências, compilação nem servidor obrigatório. A fonte web depende de conexão; sem ela, o site usa fontes locais de fallback.

## O que funciona

- Busca de feiras por nome ou bairro e filtro por categoria.
- Mapa ilustrativo interativo e detalhes de data, local, artesãos previstos e atualização.
- Perfis de exemplo dos artesãos.
- Painel de exemplo para cadastro local com consentimento de publicação, troca de perfil, candidaturas com protocolo, histórico local e simulação de rodízio.
- Documento independente, com botão para imprimir ou salvar em PDF.

## Limites do protótipo

Todos os nomes, eventos, vagas e resultados são **fictícios**. As candidaturas ficam somente no `localStorage` do navegador e não são enviadas ao PRODART. Não há autenticação, banco de dados, submissão oficial, seleção real nem mapa geográfico preciso. A pontuação mostrada é apenas uma hipótese de discussão; nenhum critério deve ser aplicado sem aprovação e publicação prévia.

## Caminho para produção

O próximo passo é validar o fluxo e as regras com artesãos e equipe gestora. A implementação real precisará de backend, banco de dados relacional, autenticação com perfis, trilha de auditoria, versionamento dos editais, rotinas de atualização de presença e barracas, consentimento para perfis públicos, atendimento assistido e monitoramento dos indicadores. O documento detalha os responsáveis e os critérios de avanço de cada etapa.
