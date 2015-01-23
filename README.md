# uxbkp
==== Antigo script de Backup para Servidores Linux ===
Por: isca0 (igorsca(em)gmail.com)
Curitiba 24/01/2015
------

Este script pode ser usado para facilitar backup dos arquivos que sao modificados por administradores de sistema unix'ses

O funcionamento do script e feito pelas modificoes de variaveis globais que podem ser usadas para criar pesquisas no sistema verificando uma assinatura que deve ser feita em pelo Sys-Admin em cada arquivo que foi sendo modificado.

Os arquivos modificas devem ter a string ##STRBKP## em algum lugar do arquivo para que o uxbkp inclua este arquivo em sua lista de arquivos a serem salvos.

O uxbkp funciona com varios argumentos que podem criar varios formatos diferentes de pacotes em 7z ou tarball's. Ele tambem pode gravar DVD's com os arquivos de backup. Gravacoes em fitas DDS ainda esta sendo implementado.


