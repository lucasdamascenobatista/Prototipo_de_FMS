procedimentos para abrir os arquivos:
1) baixar todos os arquivos e colocá-los em uma pasta;
2) extrair os arquivos da pasta "transdutor_laser.rar" e colocá-los em uma subpasta na pasta criada no passo 1;
3) conectar o MyRIO 1900 no computador e conectar os fios do circuito e do transdutor a laser conforme está escrito na dissertação;
4) ir na pasta criada no passo 1 e abrir o arquivo intitulado "FMS. lvproj". Esse é o projeto no qual estão as rotinas computacionais. Vale salientar que todas as rotinas estão na pasta criada no passo 1, mas de maneira isolada. Quando essas rotinas são executas através do projeto "FMS. lvproj", elas funcionam de maneira integrada;
5) com a janela do projeto "FMS. lvproj" aberta, selecionar os arquivos "0805_Visão_de_máquina.vi" e "movimentacao_cin_inv_bezier_2_com_sensor.vi". O primeiro é a rotina de visão computacional; e o segundo é o arquivo de movimentação, em conjunto com o do transdutor a laser. Esses dois arquivos devem ser executados simultaneamente.
