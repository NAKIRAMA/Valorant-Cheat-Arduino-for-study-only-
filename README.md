# Valorant-Cheat-Arduino-Logitech-for-study-only-

Este projeto implementa um sistema de aim assist baseado em visão computacional, utilizando OpenCV para capturar a tela e processar imagens dentro de um campo de visão (FOV) configurável. O programa detecta pixels em uma faixa de cores específica, calcula a posição do alvo e envia comandos de movimentação para o Arduino via porta serial, simulando o ajuste da mira.

Além disso:

- Permite ativar/desativar o sistema com uma tecla de atalho (atualmente configurado para botão do meio do mouse).

- Inclui feedback sonoro com pygame (sons de ligado/desligado).

- Possui configuração de velocidade e sensibilidade de ajuste da mira.

OBS: Só funciona para borda roxa e em mouses logitech (talvez funcione em outros, mas o código em C++ foi feito exclusivamente para mouses ligitech)


PASSOS PARA USAR:

 - Ter um ARDUINO e um USB HOST SHIELD
 - Passar todo o código C++ para o arduino, com o arduino.ide
 - Ter python no PC e posteriormente baixar todas as bibliotecas (imports) condizentes com o código em python
 - Abrir o cmd, colocar localização da pasta e digitar "py edge.py"
 - Recomendo entre 50 - 60 de FOV e 0.3 - 0.6 de SPEED, o SPEED vai depender da sua sensibilidade em jogo, exemplo: 0.2 1600 dpi (O DPI TEM QUE SER 1600), você pode usar 50 de FOV e 0.5 de speed.
 - SEJA FELIZ 

