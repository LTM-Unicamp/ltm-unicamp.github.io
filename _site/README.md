# Bem-Vindos ao LTM!

Esse é o [repositório](https://github.com/LTM-Unicamp/ltm-unicamp.github.io) do site do Laboratório de Otimização Topológica e Análises Multifísicas, coordenado pelo professor [Renato Pavanello](http://lattes.cnpq.br/1014571239084005). Todos os alunos/pesquisadores são bem-vindos a colaborar com a melhoria e atualização deste repositório. Vale salientar que este site foi gerado utilizando [Jekyll](https://jekyllrb.com), mas também contém algumas partes em [Bootstrap](http://www.getbootstrap.com) e [Bootswatch](http://www.bootswatch.com) que vieram do template fornecido pelo grupo [Allan Lab](https://www.allanlab.org/). No entanto, a maioria dos arquivos que deverão ser alterados são escritos em [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) ou `.yml`.

## Arquivos de dados
Uma das pastas mais importantes deste repositório é a pasta [_data](../ltm-unicamp.github.io/_data/), na qual são encontrados os arquivos:

- [staff_members.yml](../ltm-unicamp.github.io/_data/staff_members.yml): Dados dos membros atuais do grupo
- [alumni_members.yml](../ltm-unicamp.github.io/_data/alumni_members.yml): Dados dos membros antigos do grupo (os veio)
- [partime_members.yml](../ltm-unicamp.github.io/_data/partime_members.yml): Dados dos alunos especiais ou visitantes
- [publist.yml](../ltm-unicamp.github.io/_data/publist.yml): Dados das publicações do grupo
- [news.yml](../ltm-unicamp.github.io/_data/news.yml): Dados de notícias

Em todos esses arquivos existem exemplos de dados [meus](http://lattes.cnpq.br/8648415987292827), de maneira a exemplificar como deve ser feita a atualização. Basta copiar o padrão e introduzir os seus próprios dados. Fiquem a vontade para atualizar sempre que necessário.

## Pasta de páginas
Outra pasta importante é a [_pages](../ltm-unicamp.github.io/_pages/), na qual são encontrados os arquivos:

**Não modificáveis**:
- [404.md](../ltm-unicamp.github.io/_pages/404.md): Código que relata erro de navegação
- [allnews.md](../ltm-unicamp.github.io/_pages/allnews.md): Códigos para as notícias -- modificar em: [news.yml](../ltm-unicamp.github.io/_data/news.yml)
- [publications.md](../ltm-unicamp.github.io/_pages/publications.md): Códigos para as publicações -- modificar em: [publist.yml](../ltm-unicamp.github.io/_data/publist.yml)
- [team.md](../ltm-unicamp.github.io/_pages/team.md): Códigos para os membros do grupo -- modificar em: [staff_members.yml](../ltm-unicamp.github.io/_data/staff_members.yml), [alumni_members.yml](../ltm-unicamp.github.io/_data/alumni_members.yml) ou [partime_members.yml](../ltm-unicamp.github.io/_data/partime_members.yml).

**Modificáveis**:
- [codes.md](../ltm-unicamp.github.io/_pages/codes.md): Dados da página de códigos e tutoriais
- [home.md](../ltm-unicamp.github.io/_pages/home.md): Dados da página inicial
- [research.md](../ltm-unicamp.github.io/_pages/research.md): Dados da página de pesquisas

Aqui também existem exemplos com [meus](http://lattes.cnpq.br/8648415987292827) dados. Fiquem a vontade para copiar o padrão e preencher com os seus próprios (*somente dos arquivos modificáveis!*).

## Pasta de imagens
A pasta [images](../ltm-unicamp.github.io/images/) guarda as fotos, vídeos e gifs do grupo. É divida em subpastas:

- [ltm_carousel](../ltm-unicamp.github.io/images/ltm_carousel): Guarda as imagens do carrossel da página inicial
- [ltm_logos](../ltm-unicamp.github.io/images/ltm_logos): Guarda as logos do lab e de empresas parceiras
- [ltm_news](../ltm-unicamp.github.io/images/ltm_news): Guarda as imagens das notícias
- [ltm_publication](../ltm-unicamp.github.io/images/ltm_publication): Guarda as imagens da página de publicações
- [ltm_research](../ltm-unicamp.github.io/images/ltm_research): Guarda as imagens e gifs da página de pesquisa
- [ltm_team](../ltm-unicamp.github.io/images/ltm_team): Guarda as fotos dos maravilhosos membros do grupo!


##  Demais pastas e arquivos 
As pastas de [_includes](../ltm-unicamp.github.io/_includes/) e [_layouts](../ltm-unicamp.github.io/_layouts/) são repletas de arquivos em `.htlm`, contendo o código que descreve o template. O arquivo [carousel](../ltm-unicamp.github.io/_includes/carousel.html), dentro da pasta [_includes](../ltm-unicamp.github.io/_includes/), deve ser modificado ao surgirem novas fotos para o carrosel que compõe a página inicial do site. Os demais arquivos em `.html` não necessitam de alteração constante.

As demais pastas, sendo elas [plugins](../ltm-unicamp.github.io/_plugins/), [sass](../ltm-unicamp.github.io/_sass/), [_site](../ltm-unicamp.github.io/_site/), [.jekyll-cache](../ltm-unicamp.github.io/.jekyll-cache/), [css](../ltm-unicamp.github.io/css/), [fonts](../ltm-unicamp.github.io/fonts/), [js](../ltm-unicamp.github.io/js/), [vendor](../ltm-unicamp.github.io/vendor/) e os arquivos [_config.yml](../ltm-unicamp.github.io/_config.yml), [.gitignore](../ltm-unicamp.github.io/.gitignore), [CNAME](../ltm-unicamp.github.io/CNAME) e [Gemfile](../ltm-unicamp.github.io/Gemfile) não precisam (*ou não devem*) ser alterados.

**A pasta [_site](../ltm-unicamp.github.io/_site/) contém os arquivos convertidos para a montagem do site, sendo gerada automaticamente pelo jekyll, e não deve ser modificada!**





Abraços e boas pesquisas!