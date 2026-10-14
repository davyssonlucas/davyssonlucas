# Davysson Lucas

Desenvolvedor backend Python e criador do **[Planeja AI Prof](https://planeja.prof)**, plataforma web que ajuda
professores a planejar aulas com inteligência artificial e a acompanhar suas turmas.

Trabalho do modelo de dados ao deploy: arquitetura em Django, integrações de pagamento, processamento assíncrono,
uso de IA generativa em produção e operação do servidor.

---

## Planeja AI Prof

[planeja.prof](https://planeja.prof) · produto próprio, em produção

Com o Planeja, o professor cria unidades curriculares, planos de aula, avaliações, situações de aprendizagem,
apresentações e apostilas com apoio da IA, e leva esse material para uma sala de aula virtual com alunos, atividades
e entregas. Escolas assinam um plano institucional e gerenciam seus professores.

Concebi, desenvolvi e opero a plataforma. Alguns pontos do projeto:

- **Arquitetura**: monólito Django modular, com mais de uma dezena de apps e regras de negócio concentradas em
  camada de serviços.
- **Assinaturas e pagamentos**: integração com a Stripe por webhooks, com um único caminho de ativação por evento
  de domínio, upgrade proporcional, reembolsos, cupons e conciliação; Pix como alternativa.
- **Créditos de IA**: créditos semanais por plano e pacotes avulsos, com reserva, confirmação e estorno registrados
  em livro-razão.
- **IA generativa**: geração de conteúdo com Google Gemini, rotação de chaves e modelos configuráveis pelo admin;
  geração de imagens com Cloudflare Workers AI e Runware.
- **Contexto individual e institucional**: o mesmo usuário atua como professor autônomo ou dentro de uma escola,
  com funções cumulativas e permissões por local.
- **Documentos**: exportação em PDF, PowerPoint, Word e Excel; editor de slides próprio no navegador.
- **Operação**: Celery com RabbitMQ e Redis, deploy em Docker com Coolify, Cloudflare na frente, armazenamento na
  Oracle Cloud, admin com perfis para financeiro, vendas e suporte.
- **Qualidade**: testes com pytest no backend e Vitest no JavaScript das telas, changelog e documentação técnica
  versionados.

---

## O que eu faço

- **Backend em Python**: Django, Django REST Framework e FastAPI, com foco em código testável e de fácil manutenção.
- **Integrações**: APIs REST, webhooks, gateways de pagamento, mensageria e APIs de IA.
- **Infraestrutura**: Docker, PostgreSQL, filas, servidores Linux e deploy contínuo em ambiente self-hosted.
- **Automação**: scripts e serviços que eliminam trabalho manual em fluxos de dados e relatórios.

## Tecnologias

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0db7ed?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/davyssonlucas)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=flat-square&logo=telegram&logoColor=white)](https://t.me/davyssonsantana)
[![Planeja AI Prof](https://img.shields.io/badge/planeja.prof-1F6FEB?style=flat-square&logoColor=white)](https://planeja.prof)
