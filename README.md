# Bem-Vindos ao LTM!

Esse é o [repositório](https://github.com/LTM-Unicamp/ltm-unicamp.github.io) do site do Laboratório de Otimização Topológica e Análises Multifísicas, coordenado pelo professor [Renato Pavanello](http://lattes.cnpq.br/1014571239084005). Todos os alunos/pesquisadores são bem-vindos a colaborar com a melhoria e atualização deste repositório. Vale salientar que este site foi gerado utilizando [Jekyll](https://jekyllrb.com), mas também contém algumas partes em [Bootstrap](http://www.getbootstrap.com) e [Bootswatch](http://www.bootswatch.com) que vieram do template fornecido pelo grupo [Allan Lab](https://www.allanlab.org/). No entanto, a maioria dos arquivos que deverão ser alterados são escritos em [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) ou `.yml`.

## Arquivos de dados
Uma das pastas mais importantes deste repositório é a pasta [_data](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_data), na qual são encontrados os arquivos:

- [staff_members.yml](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_data/staff_members.yml): Dados dos membros atuais do grupo
- [alumni_members.yml](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_data/alumni_members.yml): Dados dos membros antigos do grupo (os veio)
- [partime_members.yml](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_data/partime_members.yml): Dados dos alunos especiais ou visitantes
- [publist.yml](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_data/publist.yml): Dados das publicações do grupo
- [news.yml](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_data/news.yml): Dados de notícias

Em todos esses arquivos existem exemplos de dados [meus](http://lattes.cnpq.br/8648415987292827), de maneira a exemplificar como deve ser feita a atualização. Basta copiar o padrão e introduzir os seus próprios dados. Fiquem a vontade para atualizar sempre que necessário.

## Pasta de páginas
Outra pasta importante é a [_pages](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_pages/), na qual são encontrados os arquivos:

**Não modificáveis**:
- [404.md](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_pages/404.md): Código que relata erro de navegação
- [allnews.md](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_pages/allnews.md): Códigos para as notícias -- modificar em: [news.yml](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_data/news.yml)
- [publications.md](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_pages/publications.md): Códigos para as publicações -- modificar em: [publist.yml](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_data_/publist.yml)
- [team.md](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_pages/team.md): Códigos para os membros do grupo -- modificar em: [staff_members.yml](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_data_/staff_members.yml), [alumni_members.yml](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_data_/alumni_members.yml) ou [partime_members.yml](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_data_/partime_members.yml).

**Modificáveis**:
- [codes.md](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_pages/codes.md): Dados da página de códigos e tutoriais
- [home.md](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_pages/home.md): Dados da página inicial
- [research.md](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_pages/research.md): Dados da página de pesquisas

Aqui também existem exemplos com [meus](http://lattes.cnpq.br/8648415987292827) dados. Fiquem a vontade para copiar o padrão e preencher com os seus próprios (*somente dos arquivos modificáveis!*).

## Pasta de imagens
A pasta [images](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/images/) guarda as fotos, vídeos e gifs do grupo. É divida em subpastas:

- [ltm_carousel](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/images/ltm_carousel): Guarda as imagens do carrossel da página inicial
- [ltm_logos](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/images/ltm_logos): Guarda as logos do lab e de empresas parceiras
- [ltm_news](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/images/ltm_news): Guarda as imagens das notícias
- [ltm_publication](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/images/ltm_publication): Guarda as imagens da página de publicações
- [ltm_research](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/images/ltm_research): Guarda as imagens e gifs da página de pesquisa
- [ltm_team](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/images/ltm_team): Guarda as fotos dos maravilhosos membros do grupo!


##  Demais pastas e arquivos 
As pastas de [_includes](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_includes/) e [_layouts](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_layouts/) são repletas de arquivos em `.htlm`, contendo o código que descreve o template. O arquivo [carousel](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_includes/carousel.html), dentro da pasta [_includes](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_includes/), deve ser modificado ao surgirem novas fotos para o carrosel que compõe a página inicial do site. Os demais arquivos em `.html` não necessitam de alteração constante.

As demais pastas, sendo elas [plugins](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_plugins/), [sass](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_sass/), [_site](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_site), [.jekyll-cache](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/.jekyll-cache/), [css](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/css/), [fonts](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/fonts/), [js](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/js/), [vendor](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/vendor/) e os arquivos [_config.yml](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_config.yml), [.gitignore](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/.gitignore), [CNAME](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/CNAME) e [Gemfile](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/Gemfile) não precisam (*ou não devem*) ser alterados.

**A pasta [_site](https://github.com/LTM-Unicamp/ltm-unicamp.github.io/tree/gh-pages/_site/) contém os arquivos convertidos para a montagem do site, sendo gerada automaticamente pelo jekyll, e não deve ser modificada!**





Abraços e boas pesquisas!