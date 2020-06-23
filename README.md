# kabug-rb
Repositório para estudo da automação rodar no jenkins

## Como executar o projeto

*importante ter o Ruby instalado (versão 2.5 ou superior)

### Instalar o Bundler

gem install bundler

### Executar as dependências do Ruby (projeto)

bundle install

### Executar localmente (minha maquina)

bundle exec cucumber

### Executar no servidor de CI (gerando reposts JSON)

bundle exec cucumber -p ci
