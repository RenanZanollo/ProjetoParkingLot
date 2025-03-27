# **Sistema e API de Estacionamento com Python e Django do Zero (parte 1)**

### Requisitos do projeto **Parking Service**:

Sistema de gestão de estacionamento de veículos que deve atender os seguintes requisitos:

https://whimsical.com/parking-service-SSoifu29a1MVLAmLAPMk2a

### Funcionais

- Sistema de administração interno
    - Controle de usuários, acessos e permissões
    - Cadastros:
        - Clientes
        - Veículos
        - Vagas
        - Entradas e saídas de veículos
    - Status de vagas automático (ocupado / livre)
- API para futuras integrações
    - Cadastros completos das entidades
        - Clientes
        - Veículos
        - Vagas
        - Entradas e saídas de veículos
    - Autenticação
    - Filtros
    - Possibilidade de acesso dos clientes
        - Ver apenas seus veículos e registros
    - Auto completar dados dos veículos quando informado apenas a placa
        - Verificar API de consulta
        - Rodar em paralelo
    - Notificar proprietário nas entradas e saídas dos veículos
        - WhatsApp
            - EvolutionApi
        - E-mail
            - SMTP

    ### Não funcionais

    - Dashboard do Jazzmin
    - API Restfull
    - Linter e pep08
    - JWT token para API
    - RQL para filtros
    - Testes
    - Serviços em containers
    - EvolutionApi (serviço e integração)
    - E-mail SMTP (integração e envio)
    - PostgreSQL
    - Celery e RabbitMQ
        - Rodar tasks de buscas de auto completar dados de veículos
    - Documentação da API (swagger)

    ### Entregas:

    - Modelagem
    - Admin
    - Signals (status de vagas)
    - RestAPI das entidades básicas
    - Requirements
    - Linter (flake8)
