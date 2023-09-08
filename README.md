# ifba-abntex2

Customizações aplicadas à classe [abnTeX2](https://www.abntex.net.br/) para adequar ao IFBA Jacobina.

## Lista dos arquivos

- **[abntex2-ifba-jacobina.sty](abntex2-ifba-jacobina.sty)**: Arquivo contendo configurações adicionais ao abnTeX2.
- **[abntex2-modelo-include-comandos.tex](abntex2-modelo-include-comandos.tex)**: Arquivo original do pacote de distribuição abnTeX2 contendo os comandos para formatação do texto.
- **[abntex2-modelo-references.bib](abntex2-modelo-references.bib)**: Arquivo original do pacote de distribuição abnTeX2 contendo referências bibliográficas para serem usadas no modelo canônico.
- **[abntex2-modelo-trabalho-academico.tex](abntex2-modelo-trabalho-academico.tex)**: Modelo canônico adaptado que apresenta a estrutura dos trabalhos acadêmicos do IFBA Campus Jacobina.
- **[abntex2-modelo-img-grafico.pdf](abntex2-modelo-img-grafico.pdf)**: Arquivo original do pacote de distribuição abnTeX2 contendo um gráfico.
- **[abntex2-modelo-img-marca.pdf](abntex2-modelo-img-marca.pdf)**: Arquivo original do pacote de distribuição abnTeX2 contendo uma imagem.
- **[abntex2-modelo-trabalho-academico.pdf](abntex2-modelo-trabalho-academico.pdf)**: Arquivo gerado pelo compilador a partir do modelo canônico.

## Como usar

Caso nunca tenha usado a classe abnTeX2 sugiro que comece pelo [como começar](https://github.com/abntex/abntex2/wiki/PorOndeComecar) do próprio projeto abnTeX2.

Uma vez que a classe abnTeX2 esteja disponível no sistema, basta baixar os arquivos deste projeto e compilar o arquivo *[abntex2-modelo-trabalho-academico.tex](abntex2-modelo-trabalho-academico.tex)*. Os arquivos .pdf, .bib, *[abntex2-modelo-include-comandos.tex](abntex2-modelo-include-comandos.tex)* podem ser excluídos, desde que não sejam utilizados no arquivo principal.

As alterações necessárias deverão ser realizadas no arquivo *[abntex2-modelo-trabalho-academico.tex](abntex2-modelo-trabalho-academico.tex)*, que também, pode ter seu nome alterado, caso queira.

## Novos comandos

Os comandos a seguir foram incluídos no arquivo *[abntex2-ifba-jacobina.sty](abntex2-ifba-jacobina.sty)* para padronizar o documento.

```TeX
\campus
\curso
\grau
\orientadora
\coorientadora
\coordenador
\coordenadora
\reitor
\reitora
\diretorgeral
\diretorageral
\diretorensino
\diretoraensino
\diretorensinoPronome
\datadefesa
\imprimirlistadedirigentes
```

Exceto para o comando `\imprimirlistadedirigentes`, cujo objetivo é expresso no nome, cada um desses comandos serve para alterar os parâmetros especificados pelo seu nome. Alguns desses campos já vem com valores pré-definidos, desse modo só devem ser usados caso necessário.