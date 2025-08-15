# stock-track
Backend de microsserviços para registro, monitoramento e previsão de demanda de estoque, com alertas automáticos e integração com IA para previsão.

## Estrutura
- `infra/` → Configurações e serviços de suporte (Mongo, RabbitMQ, ELK).
- `platform/` → Serviços de plataforma (gateway, config, discovery).
- `services/` → Microsserviços de domínio (auth, catálogo, estoque, previsão, notificações).
- `shared/` → Módulos compartilhados (logging, segurança, mensagens).

## Licença
[MIT](LICENSE)