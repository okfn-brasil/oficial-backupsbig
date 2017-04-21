# videos
Repositório de backup de *large files* da produção da OKBR, principalmente versões originais de *videos oficiais* que precisaram ser "cortados" ou editados para ficarem mais atrativos para o público.  Repositório baseado em *git LFS* ([Large Files Storage](https://git-lfs.github.com/)). 

A maior parte dos vídeos e áudios podem ser vistos por streamming via [canal OKBr no youtube](https://www.youtube.com/user/okfnbr), o presente repositório não tem finalidade de distribuição, apenas de tutela do material e [garantia da sua preservação e integridade](https://en.wikipedia.org/wiki/Digital_preservation), principalmente em vídeos relativos a [reuniões oficiais da OKBr](https://discuss.okfn.org/tags/okbr-oficial).

Este repositório é um complemento de [okfn-brasil/discussOKBr-assets](https://github.com/okfn-brasil/discussOKBr-assets/blob/master/README.md): os [metadados do material mantido por este repositório](data/largefiles-metadata.csv) deve seguir os mesmos critérios e padrões de descrição. 

## Preparo
 
Seguir as instruções de [installing-git-large-file-storage](https://help.github.com/articles/installing-git-large-file-storage/), lembrando de usar sudo em `sudo ./install.sh`.

Vídeos Youtube trazidos com *youtube-dl* (`sudo apt-get install youtube-dl`). <br/>Exemplo: `youtube-dl --add-metadata --audio-quality 9 https://www.youtube.com/watch?v=SaVQKVuUBU4`

## Procedimento

Antes de incorporar o vídeo no repositório, confira e atualize a tabela de tags e de vídeos [na planilha de edição colaborativa](https://docs.google.com/spreadsheets/d/1AK_GYMqoAl84nbrjbzSJXALOGKjfHlby_VOTS8tlnIM/edit#gid=298639303). 

Vídeos não-oficiais (sem [*tag* `okbr-oficial`](https://github.com/okfn-brasil/discussOKBr-assets/blob/master/data/tag.csv)) precisam ter sido submetidos ao crivo do público e membros da OKBr antes de ser permanentemente registrado neste repositório.

...
