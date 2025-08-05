Plataforma de desenvolvimento do servidor de impressão CUPS no GitHub:

https://github.com/OpenPrinting/cups/blob/master/locale/cups_pt_BR.po


Plataforma de tradução do CUPS no Weblate do idioma português do Brasil

https://hosted.weblate.org/projects/cups/cups/pt_BR/


Tradução revisada por marcelocripe:

https://github.com/marcelocripe/CUPS_pt_BR/blob/main/cups_pt_BR.po



Para utilizar o arquivo "cups_pt_BR.po" da tradução do CUPS da versão 2.5, inicie o Emulador de Terminal na pasta onde está o arquivo que foi baixado.

Utilize o comando abaixo para renomear o arquivo antigo da tradução "cups_pt_BR.po" que está na pasta do idioma "pt_BR".

Digite o comando abaixo, pressione a tecla "Enter", insira a sua senha se for solicitada e pressione a tecla "Enter".

$ sudo mv /usr/share/cups/locale/pt_BR/cups_pt_BR.po /usr/share/cups/locale/pt_BR/cups_pt_BR_antigo.po


Utilize o comando abaixo para copiar o arquivo da tradução "cups_pt_BR.po" para a pasta do idioma "pt_BR".

Digite o comando abaixo, pressione a tecla "Enter", insira a sua senha se for solicitada e pressione a tecla "Enter".

$ sudo cp cups_pt_BR.po /usr/share/cups/locale/pt_BR


Para ativar o CUPS no antiX da ISO "full" ou "completa" do tipo SysVinit, clique no menu do antiX, percorra os menus "Aplicativos", "Sistema" e clique no menu das "Configurações de Inicialização de Serviços" (Choose Startup Services).

Quando a janela do Emulador de Terminal for exibida, insira a sua senha se for solicitada e pressione a tecla "Enter".

Com a tecla direcional para baixo, mova a seleção em cor branca para baixo na coluna 1 até a linha do cups [ ], pressione a tecla de "Espaço", a letra "X" será preenchida no espaço entre os colchetes ficando desta forma [X].

Em seguida, pressione a tecla "=/+" para iniciar o servidor de impressão CUPS, pressione a tecla "Enter" para confirmar e "q" para sair.

Para iniciar a interface gráfica do CUPS, clique no ícone de atalho do navegador de internet, na barra de endereço digite sem as aspas "http://localhost:631" e pressione a tecla "Enter".

