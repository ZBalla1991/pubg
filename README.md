# pubg
Bot de estatisticas de pubg
# PUBG Bot de Relatórios de Partidas

Este é um bot para gerar relatórios de partidas de PUBG (PlayerUnknown's Battlegrounds). O bot busca dados de partidas, armazena esses dados em um banco de dados SQLite, realiza análises detalhadas e envia as estatísticas para um canal do Discord ao fim de cada partida.

## Estrutura do Projeto

- `main.py`: Ponto de entrada do bot.
- `config.py`: Arquivo de configuração.
- `database.py`: Módulo para gerenciar operações de banco de dados.
- `api_client.py`: Módulo para interagir com a API do PUBG.
- `data_analysis.py`: Módulo para realizar análises de dados.
- `discord_bot.py`: Módulo para interagir com a API do Discord.
- `requirements.txt`: Dependências do projeto.
- `README.md`: Documentação do projeto.

## Como Usar

1. Instale as dependências:
   ```sh
   pip install -r requirements.txt

Comandos do Discord:
/estatisticas: Envia as estatísticas das partidas para o canal do Discord.
/rastrear <nome_do_jogador>: Adiciona um jogador ao rastreamento.
/parar_rastreamento <nome_do_jogador>: Remove um jogador do rastreamento.
/listar_rastreados: Lista todos os jogadores que estão sendo rastreados.

# Dev: Balla
