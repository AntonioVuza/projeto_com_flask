Instalação uv 
- Pesquise o site uv astral e dentro do site clique em installation.
- entre no terminal powershell e copie o comando que fica disponivel na aba windows da pagina de installation do uv astral.

Criação da pasta
- Criar a pasta projeto_com_fleak
- Abra a pasta no terminal e crie um documento dentro da pasta chamado app.py
- Abra o terminal e digite os comandos:
● uv init (inici o projeto diretamente no próprio diretorio atual.)
● uv venv (Cria um ambiente virtual isolado em Python.)
● uv python install 3.15.0 (Para instalar uma versão mais atualizada do Python.)
● uv sync (Atualiza o ambiente virtual.)
● python -v e logo após saia como o comando informar
● python -V (mostra a versão atual baicadafa no Python.)
● uv add Flask (instala a biblioteca Flask como dependencia de um projeto Python.)

Resumo app.py:
- Flask: Classe usada para cirar instâncias da sua aplicação na web
- render_template: Função utilizada para carregar e renderizar arquivos HTML (geralmente localizados numa pasta chamada "templates").
- request: Objeto global que gerencia os dados das aquisições do HTTP enviadas pelo usuário, como parâmetros do URL.
- escape: É uma ferramenta de segurança do pacote markupsafe que converte caracteres especiais como: "<" e ">" em entidades seguras.
rom ... import ...: Serve para importar ferramentas externas.
- app = Flask(...): Inicia a instância principal da aplicação.
- @app.route(...): Define os endereços URL do site.
- def ...: Cria uma função que faz o trabalho daquela página.
- request.args.get(...): Pega em dados que a pessoa escreveu no link.
- render_template(...): Junta os dados a um ficheiro HTML para mostrar no ecrã.
- if __name__ == "__main__":: Garante que o programa só liga se for aberto diretamente.
- app.run(...): Liga o servidor para poderes testar o site no teu computador.

