# Portfólio · Juliana Matias

Página estática em português, com HTML e CSS, preparada para o GitHub Pages. Sem instalação ou build.

## Visualizar no computador

Abra `index.html` no navegador. Mantenha `styles.css` e a pasta `assets` junto do arquivo.

## Publicar no GitHub Pages

1. Crie um repositório público chamado `juliana-matias-it.github.io`. Se ele já existir, revise seu conteúdo antes de substituir arquivos.
2. Extraia este ZIP e envie o CONTEÚDO da pasta `portfolio` para a raiz do repositório. O arquivo `index.html` deve ficar diretamente na raiz.
3. Faça o commit na branch `main`.
4. Abra Settings → Pages.
5. Em Build and deployment → Source, selecione Deploy from a branch.
6. Selecione a branch `main`, pasta `/ (root)`, e clique em Save.
7. Após a publicação, o endereço esperado é https://juliana-matias-it.github.io/ . Essa URL só ficará disponível depois da configuração e publicação no GitHub.

Este portfólio é separado do repositório `juliana-matias-it` que exibe o README do perfil. Não substitua esse README pelo site.

Documentação: https://docs.github.com/en/pages/quickstart

## Estrutura

- `index.html`: textos, seções e links.
- `styles.css`: cores, tipografia e layout responsivo.
- `assets/task-manager.png`: captura do projeto Task Manager.
- `assets/product-management.png`: captura do projeto Product Management.
- `.nojekyll`: indica publicação dos arquivos estáticos sem processamento Jekyll.

## Personalizar

Edite o HTML para alterar os textos e acrescentar projetos. As cores estão nas variáveis no início do CSS. As capturas foram obtidas dos repositórios públicos da autora. Clique nelas no site para abrir a imagem completa.

Os links dos projetos abrem os repositórios, não uma aplicação hospedada. Os backends .NET desses projetos precisam de hospedagem própria caso você queira adicionar demonstrações online; o portfólio funciona de forma independente.

## Validação

Conferidos os arquivos locais, destinos internos e a integridade das imagens. Incluídos layout responsivo, foco visível para teclado e suporte a movimento reduzido. A aparência ainda precisa de revisão no navegador.
