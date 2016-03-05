# beagleboneblack #

Projeto para analise de desempenho na execução de algoritmos de ordenação, Com informações comparativas (Gráficos) para execução em diferentes plataformas.

## Índice ##

## A BeagleBone ##

### Avisos ###

1. Não posicionar a Beaglebone em superfícies metálicas;
2. Desligar com o comando adequado ou usar os botões. NUNCA PUXAR
O CABO DE FORÇA OU O USB POWER;
3. GPIO são 3.3v tolerantes;
	a. Input: 4mA - 6mA
	b. Output: 8mA
4. ADC são 1.8v tolerantes;
5. Não modificar a senha de root do sistema (eMMC);
6. Desconecte todos os fios da placa ao fazer uma mudança na eletrônica.

## Gnuplot Tutorial ##

O gnuplot é um software que falicita a criação de gráficos (2D e 3D) para vários ambientes (UNIX, Windows, Macintosh, etc.). A seguir teremos alguns comandos básicos para a utilização desta ferramenta.

http://www.dicas-l.com.br/arquivo/usando_gnuplot_para_gerar_bons_graficos.php

### Instalar: ###

	sudo apt-get install gnuplot-x11

### Execuntando ###

Abra o terminal do seu sistema operacional, e escreva:

	gnuplot

O programa será executado no próprio terminal, e assim podemos iniciar a plotar o gráfico.

### Gerando o gráfico ###

1. Acessa o diretório que contém os arquivos "clock.dat" e "clock.dat" (que foram gerados pela execução dos métodos)]

2. Comando:

		plot "clock.dat" using 1:2 title "BubbleSort" with lines, "clock.dat" using 1:3 title "QuickSort" with lines, "clock.dat" using 1:4 title "MergeSort" with lines

		plot "time.dat" using 1:2 title "BubbleSort" with lines, "time.dat" using 1:3 title "QuickSort" with lines, "time.dat" using 1:4 title "MergeSort" with lines

### Salvar como imagem ###

	set terminal png
	set output 'imagem.png'
	replot

### Utilizando o script gnuplot ###

##  ##

## ##

## Membros ##

* Breno Maurício de Freitas Viana
* Felipe Barbalho Rocha
