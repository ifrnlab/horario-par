# horario-par
Horário do IFRN campus Parnamirim

## Dicas para geração do calendário

1. Abrir o shell zsh e executar:

   ```zsh
   for m ({01..12})
      cp calendario-2022.svg calendario-2022-$m.svg
   ```
   
2. Editar as imagens geradas no Inkscape:

   1. `Ctrl`+`A`: Selecionar tudo
   2. Clicar com botão direito do mouse e escolher opção *Desagrupar*
   3. Selecionar somente o mês desejado
   4. Pressionar, na sequência:
   
      1. `!`: Inverter a seleção
      2. `Delete`: Apagar os outros meses
      3. `Ctrl`+`Shift`+`R`: Encaixar página (ou canvas) à seleção [^1]
      4. `Ctrl`+`S`: Salvar

[^1]: <https://stackoverflow.com/questions/46195427/inkscape-fit-page-to-selection-shortcut>
