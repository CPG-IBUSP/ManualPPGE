# Manual de orientação a estudantes do Programa de Pós-Graduação em Ecologia da USP

## Estrutura
### Arquivos com conteúdo do manual:
 * `conteudo.tex` : texto do manual. 
 * `ficha_tecnica.tex` : capa e ficha técnica
 * `contato.tex` : informações para contato, para a contracapa
### Arquivos de configuração e layout:
 * `manual.tex` : fonte para gerar o manual em formato apostila
 * `manual_booklet.tex` : fonte para gerar o manual em formato livreto
 * `manual_html.tex` : fonte para gerar o manual em formato html
 * `meta.tex` , `meta_html.tex` : cabeçalhos para configuração das fontes acima
## Para gerar os manuais
1. Execute `pdflatex manual.tex`
2. Execute `pdflatex manual_booklet.tex`
3. Execute `latex2html -nofootnode -contents index.html -dir docs/ manual_html.tex`
## Para sugerir alterações
### Como um issue
Use a seção de *issues* destes repositório para fazer sugestões.
### Por um pull request
1. Faça um fork deste repositório
2. Faça as alteraçõe em seu fork
3. Envie um *Pull request* para este repositório
## Para publicar os manuais no site do PPGE-USP
As versões html e livreto para impressão do manual são servidas diretamente no site, não é preciso fazer nada mais.
Para atualizar a versão livreto eletrônico pelo serviço FLIPHTML5 cirie uma conta em https://fliphtml5.com/, faça upload do livreto, e copie o link de compartilhamento para o itemd e menu do site Orientações > Manual des Estudantes > Livreto digital. Para isso é preciso ser administrador do site do PPGE-USP 