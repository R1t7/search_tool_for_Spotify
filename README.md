Web App Spotify
-
Este projeto é um Web App interativo em Python que consome a API do Spotify para buscar informações de artistas e listar suas músicas mais populares.
A interface foi desenvolvida com Streamlit.

Funcionalidades:
- Autenticação na API do Spotify via Client Credentials Flow
- Busca de artistas pelo nome
- Exibição de popularidade do artista
- Listagem das faixas mais populares com links diretos para o Spotify

Tecnologias(imports) usadas:
- Python 3.10+
- Streamlit
- Requests
- python-dotenv

Pré-requisitos
-
Antes de rodar o projeto, você precisa:
- 1- Ter uma conta no Spotify for Developers.
- 2- Criar um App no painel do Spotify Developer.
- 3- Copiar as credenciais Client ID e Client Secret.

Configuração do ambiente
-
Crie um arquivo .env na raiz do projeto com o seguinte conteúdo:

- SPOTIFY_CLIENT_ID=seu_client_id_aqui
- SPOTIFY_CLIENT_SECRET=seu_client_secret_aqui

Como rodar o projeto
-
Clone o repositório:

- Crie e ative um ambiente virtual (opcional, mas recomendado):

python -m venv venv
- source venv/bin/activate   # Linux/Mac
- venv\Scripts\activate      # Windows

Instale as dependências:

- pip install -r requirements.txt

Execute a aplicação com o Streamlit:

- streamlit run yournamefile.py

Exemplo de uso
-
- Digite o nome de um artista no campo de busca.

- Veja as informações de popularidade.

- Clique nos links para ouvir as músicas diretamente no Spotify.

📄 Licença
-
Este projeto é apenas para fins educacionais e de aprendizado.