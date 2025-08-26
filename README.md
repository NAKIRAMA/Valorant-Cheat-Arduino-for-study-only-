# Valorant-Cheat-Arduino-Logitech-for-study-only-

Este projeto implementa um sistema de aim assist baseado em visão computacional, utilizando OpenCV para capturar a tela e processar imagens dentro de um campo de visão (FOV) configurável. O programa detecta pixels em uma faixa de cores específica, calcula a posição do alvo e envia comandos de movimentação para o Arduino via porta serial, simulando o ajuste da mira.

Além disso:

- Permite ativar/desativar o sistema com uma tecla de atalho (atualmente configurado para botão do meio do mouse).

- Inclui feedback sonoro com pygame (sons de ligado/desligado).

- Possui configuração de velocidade e sensibilidade de ajuste da mira.

OBS: Só funciona para borda roxa e em mouses logitech (talvez funcione em outros, mas o código em C++ foi feito exclusivamente para mouses ligitech)
