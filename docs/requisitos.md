# Requisitos iniciais do AprovaLex

Este documento descreve os requisitos iniciais do AprovaLex, uma ferramenta open source para apoiar arquitetos, engenheiros e profissionais da construção civil na interpretação preliminar de leis urbanísticas e exigências para aprovação de projetos.

## 1. Objetivo do sistema

O AprovaLex deve ajudar o usuário a organizar informações legais e técnicas relacionadas à aprovação de projetos arquitetônicos.

O sistema deve transformar dados do terreno, informações do projeto e trechos da legislação em um checklist preliminar de análise.

## 2. Público-alvo

O sistema é pensado para:

- arquitetos;
- engenheiros;
- estudantes de arquitetura;
- escritórios de projeto;
- consultores de aprovação;
- profissionais de regularização de imóveis;
- profissionais que precisam interpretar leis municipais.

## 3. Dados do município

O sistema deve permitir registrar informações básicas do município analisado.

Campos necessários:

- nome do município;
- estado;
- tipo de legislação analisada;
- nome da lei;
- número da lei;
- ano da lei;
- link oficial da legislação;
- observações sobre a fonte da informação.

## 4. Dados do terreno

O sistema deve permitir registrar informações do lote ou terreno.

Campos necessários:

- área total do terreno;
- testada do terreno;
- profundidade aproximada;
- endereço ou referência;
- zona urbana;
- zoneamento;
- uso permitido;
- uso pretendido;
- existência de esquina;
- existência de aclive ou declive;
- observações relevantes.

## 5. Dados do projeto

O sistema deve permitir registrar informações básicas do projeto arquitetônico.

Campos necessários:

- tipo de projeto;
- uso da edificação;
- área construída prevista;
- número de pavimentos;
- altura aproximada da edificação;
- área permeável prevista;
- área ocupada no terreno;
- número de unidades;
- número de vagas de garagem;
- observações do projeto.

## 6. Dados urbanísticos analisados

O sistema deve ajudar a organizar os principais critérios urbanísticos.

Itens analisados:

- recuo frontal;
- recuo lateral;
- recuo de fundos;
- taxa de ocupação;
- coeficiente de aproveitamento;
- taxa de permeabilidade;
- altura máxima;
- número mínimo de vagas;
- afastamentos obrigatórios;
- uso permitido;
- documentação exigida;
- restrições específicas por zona.

## 7. Checklist preliminar

O sistema deve gerar um checklist com a situação de cada item.

Situações possíveis:

- atende;
- não atende;
- precisa verificar;
- não informado;
- não se aplica.

Cada item do checklist deve conter:

- nome do item;
- regra encontrada;
- dado informado pelo usuário;
- situação;
- observação;
- fonte da regra.

## 8. Relatório preliminar

O sistema deve gerar um relatório com:

- resumo do município;
- dados do terreno;
- dados do projeto;
- principais regras identificadas;
- checklist de conformidade;
- pontos de atenção;
- pendências;
- recomendações de verificação;
- aviso de que a análise não substitui aprovação oficial.

## 9. Avisos obrigatórios

O sistema deve deixar claro que:

- não substitui o profissional responsável técnico;
- não substitui parecer jurídico;
- não garante aprovação na prefeitura;
- depende da qualidade das informações fornecidas;
- deve sempre ser validado com a legislação oficial e órgão competente.

## 10. Funcionalidades futuras

Funcionalidades planejadas para versões futuras:

- upload de leis em PDF;
- organização automática de artigos por tema;
- busca por regras dentro da legislação;
- geração de relatório em PDF;
- histórico de análises;
- base colaborativa por município;
- exportação de checklist;
- interface web;
- painel para comparação entre municípios.
