# VagaFlash ⚡

MVP acadêmico criado como projeto de conclusão de curso para validar uma tese de negócio simples:

> **Horários vagos de última hora em beleza podem virar oportunidades quando profissionais conseguem publicá-los rapidamente e consumidores conseguem descobri-los sem fricção.**

## 1. A dor escolhida

Salões, barbearias e profissionais de beleza vendem principalmente **tempo disponível**. Quando um cliente cancela ou existe uma lacuna na agenda, aquele horário funciona como um estoque perecível: depois que passa, não pode ser vendido novamente.

Na prática, muitos profissionais tentam recuperar a vaga usando Status do WhatsApp, Stories, grupos ou mensagens para clientes antigos. O processo é fragmentado e depende da pessoa certa ver a mensagem no momento certo.

## 2. Evidência do problema

O Observatório do Sebrae registra mais de **211 mil empresas ativas no segmento de Beleza**, com São Paulo liderando em número de estabelecimentos. Fonte:
https://observatorio.sebrae.com.br/profile/industry/beleza

Como evidência internacional da dor de cancelamentos, uma pesquisa da Fresha publicada em 2026, feita com mais de 200 negócios de beleza e bem-estar no Reino Unido, apontou que **56% dos negócios pesquisados afirmaram perder renda significativa com cancelamentos**. Esse dado não representa o mercado brasileiro; ele é usado apenas para validar que a dor econômica existe no setor. Fonte:
https://www.fresha.com/blog/cancellations-cost-study

## 3. TAM, SAM e SOM

Para o exercício acadêmico, adotamos uma estimativa simples e conservadora:

- **TAM:** aproximadamente 211 mil estabelecimentos ativos no segmento brasileiro de Beleza monitorado pelo Sebrae.
- **SAM inicial:** estabelecimentos do segmento em São Paulo, mercado escolhido para o piloto.
- **SOM do experimento:** primeiros 50 estabelecimentos participantes do piloto.

O objetivo do MVP não é provar participação de mercado; é provar o comportamento principal antes de investir em uma plataforma completa.

## 4. Tese do MVP

> Profissionais de beleza publicarão horários vagos de última hora se isso for rápido, e consumidores demonstrarão interesse em ocupá-los quando encontrarem serviço, horário, região e preço de forma simples.

## 5. Business Model Canvas resumido

| Bloco | VagaFlash |
| --- | --- |
| Segmentos | Salões, barbearias, studios, autônomos e consumidores que buscam serviços de última hora |
| Proposta de valor | Transformar horários ociosos em oportunidades visíveis e fáceis de reservar |
| Canais | Web, WhatsApp e redes sociais |
| Relacionamento | Autoatendimento simples e fechamento pelo WhatsApp |
| Receita futura | Assinatura profissional, destaque de vagas ou taxa por conversão |
| Recursos principais | Marketplace, base de vagas, fluxo de interesse e painel |
| Atividades | Publicação, descoberta, geração de interesse e medição de conversão |
| Parceiros futuros | Plataformas de pagamento, WhatsApp e ferramentas de agenda |
| Custos | Hospedagem, domínio, manutenção e aquisição de usuários |

## 6. O que o MVP testa

- descoberta de vagas de última hora;
- interesse do consumidor;
- publicação rápida de uma vaga;
- passagem para WhatsApp;
- acompanhamento de solicitações;
- marcação da vaga como preenchida.

Métrica norte: **Vagas preenchidas.**

## 7. O que ficou manual de propósito

- confirmação final da reserva;
- negociação com o cliente;
- pagamento;
- agenda completa;
- validação do estabelecimento;
- contato e fechamento pelo WhatsApp.

Essas funções não são necessárias para validar a hipótese inicial.

## 8. Funcionalidades implementadas

### Consumidor

- landing page pública;
- listagem de vagas;
- filtros por dia, categoria e bairro;
- detalhe da vaga;
- fluxo "Quero essa vaga";
- registro da solicitação;
- mensagem pronta para WhatsApp.

### Profissional

- painel demonstrativo;
- métricas básicas;
- publicação de nova vaga;
- listagem das vagas;
- marcação como preenchida;
- visualização de solicitações.

## 9. Tecnologia

A implementação foi propositalmente simples para um MVP de curso:

- HTML5;
- CSS3;
- JavaScript puro;
- LocalStorage para persistência demonstrativa;
- sem dependências;
- sem processo de build;
- pronto para hospedagem estática.

## 10. Como executar

Abra o arquivo index.html em um navegador moderno.

Ou rode um servidor local:

    python -m http.server 8080

Depois acesse:

    http://localhost:8080

## 11. Estrutura

    VagaFlash-Curso-DIO/
    ├── index.html
    └── README.md

## 12. Segurança e privacidade

Este é um protótipo acadêmico e não deve receber dados pessoais reais em produção.

Os dados inseridos na demonstração ficam apenas no LocalStorage do navegador. Não existe senha, token, chave de API ou segredo no repositório.

Os estabelecimentos e as vagas exibidos inicialmente são fictícios.

## 13. Correções e decisões após o planejamento

Durante a construção, o escopo foi deliberadamente reduzido para evitar que o projeto virasse um ERP de salão.

Decisões:

- cliente não precisa criar conta;
- reserva final permanece no WhatsApp;
- não há pagamento integrado;
- não há mapa/GPS;
- não há sistema de avaliações;
- não há IA generativa;
- não há agenda completa;
- o painel profissional é suficiente para demonstrar publicação, interesse e preenchimento.

## 14. Próximos passos após validação

Somente após provar a tese:

- backend real;
- autenticação;
- banco de dados;
- painel administrativo;
- moderação;
- métricas de conversão;
- geolocalização;
- notificações;
- integração oficial com WhatsApp;
- integração com pagamento.

## 15. Evidências recomendadas para a entrega

Capturar prints de:

1. Home;
2. marketplace com vagas;
3. detalhe de uma vaga;
4. modal de reserva;
5. painel profissional;
6. publicação de nova vaga;
7. solicitações registradas.

## 16. Fluxo principal

**VAGOU → PUBLICOU → DESCOBRIU → CHAMOU → PREENCHEU**

---

Projeto acadêmico demonstrativo. Não representa um serviço comercial em produção.
