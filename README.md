# Monitor de Dados do Youtube

![Travis_Build](https://travis-ci.org/unb-cic-esw/youtube-data-monitor.svg?branch=master)

Este repositório compõe projeto de pesquisa com foco empírico nas eleições
brasileiras de 2018 do grupo de pesquisa [Resocie](http://resocie.org) do
[Instituto de Ciência Política - IPOL](http://ipol.unb.br/) com o apoio técnico
do [Departamento de Computação - CIC](http://www.cic.unb.br/) da
[Universidade de Brasília - UnB](http://unb.br).

O projeto consiste na coleta sistemática de informações quantitativas da
plataforma Youtube com o objetivo de subsidiar a análise do comportamento
político de alguns atores da cena eleitoral durante o período de campanha.
Além de seu objetivo finalístico para a coleta de dados, o projeto tem também
por intuito servir de material de estudo dos alunos da disciplina Engenharia
de Software do Departamento de Ciência da Computação da UnB no 1º semestre de
2018.


Os dados estão sendo coletados periodicamente, dispostos nos seguintes links

- [Atores Políticos](https://youtube-data-monitor.herokuapp.com/actors)

- [Datas de coletas](https://youtube-data-monitor.herokuapp.com/dates)

- Para informações do canal (<actor>) na data (<date>) específica:

```
https://youtube-data-monitor.herokuapp.com/<date>/canal/<actor>
```

- Para informações de todos os vídeos de um canal (<actor>) em uma data (<date>) específica:

```
https://youtube-data-monitor.herokuapp.com/<date>/canal/<actor>/videos
```

Para contribuir com o repositório, favor leia o arquivo
[CONTRIBUTING to resocie youtube-data-monitor](CONTRIBUTING.md) antes.

Para informações sobre a estrutura do código, favor leia o arquivo
[STRUCTURE of resocie youtube-data-monitor](STRUCTURE.md).
