# Finandobra
A FinanDobra é uma aplicação web de contabilidade para pequenas e médias empresas, contabilistas e estudantes. As operações do dia a dia são escritas em linguagem simples e transformadas em lançamentos de partidas dobradas. A partir deles, a aplicação prepara automaticamente o diário, o razão, o balancete, o balanço e a demonstração de resultados.

Países e normativos

Funciona com os planos de contas de Angola (PGC), Portugal (SNC), Moçambique (PGC-NIRF) e Brasil (Simples Nacional), com as taxas de IVA, os impostos e as moedas de cada país.

Principais funcionalidades
Registo por modelos (vendas, compras, salários, pagamentos) ou por frase livre
Diário, razão, balancete, balanço e demonstração de resultados
Fecho do mês: amortizações, apuramento do IVA ou do DAS, reconciliação bancária e de caixa
Fecho do exercício: imposto sobre o rendimento, apuramento e aplicação do resultado
Exportação do SAF-T de contabilidade (Angola e Portugal)
Importação do SAF-T de faturação (Primavera, PHC, Vendus e outros)
Estornos, bloqueio de meses fechados e registo de alterações para auditoria
Várias empresas por utilizador e equipas com papéis: dono, contabilista, lançador, aprovador e consulta
Modo Professor, que explica cada lançamento e é ideal para aulas
Planos Formação, Essencial, Profissional e Gabinete
Funciona no computador e no telemóvel, e pode ser instalada como aplicação
Tecnologia

A aplicação é um site estático em HTML e JavaScript, sem passos de compilação, publicado com o GitHub Pages. As contas, os dados e as permissões ficam no Supabase, com regras de segurança por registo aplicadas no servidor. Os dados de cada empresa só são visíveis para os membros da sua equipa.

Este repositório contém apenas os ficheiros da aplicação. Não contém dados de clientes nem chaves secretas: o ficheiro config.js tem apenas a chave pública do Supabase, que é feita para estar no navegador.

Estado do projeto

Versão 0.9, em fase piloto. O SAF-T ainda não foi validado nos validadores oficiais da AGT e da AT. A FinanDobra não substitui o software de faturação certificado nem o acompanhamento de um contabilista certificado.

Autor

Criada por Cândido Joaquim, contabilista com 17 anos de experiência como chefe de contabilidade numa instituição pública e 11 anos de experiência no ensino da contabilidade.

Contacto: [o seu email ou site]
