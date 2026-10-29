 API de Pokémons

Desenvolvi esta API durante o curso da EBAC para organizar registros de Pokémons, com cadastro, consulta, atualização e exclusão.

Utilizei Python, FastAPI, PostgreSQL e SQLAlchemy, com Redis para cache, Pytest para testes automatizados e Docker para execução em containers.

Para testar localmente, clone o repositório:

```bash
git clone https://github.com/GuilhermeAZampar/TarefaEbacFinal.git
cd TarefaEbacFinal
```

Configure as variáveis de ambiente do projeto e inicie os serviços:

```bash
docker compose up --build
```

O endereço local e a porta da API dependem da configuração do Compose. A documentação interativa fica na rota `/docs`.

Desenvolvido por [Guilherme Zampar](https://github.com/GuilhermeAZampar).
