# Projeto: Automação de Movimentação do Mouse com Python
Descrição:
Desenvolvi um script em Python utilizando a biblioteca PyAutoGUI para automatizar movimentos e cliques do mouse. O objetivo do projeto é demonstrar habilidades em automação de tarefas repetitivas em interface gráfica, como arrastar elementos na tela e capturar coordenadas do cursor.

Funcionalidades implementadas:
Movimentação e arraste automático do mouse

O script move o cursor para uma posição inicial definida.

Simula o clique e o arraste até uma posição final, liberando o botão automaticamente.

Permite configurar a velocidade do arraste com o parâmetro duration.

Implementa pausas (time.sleep) para preparação e segurança do usuário.

Trecho de código:

python
Copiar
Editar
pyautogui.moveTo(200, 826, duration=0.2)
pyautogui.mouseDown()
pyautogui.dragTo(243, 133, duration=0.2)
pyautogui.mouseUp()
Captura de coordenadas do cursor

Permite identificar as posições exatas na tela para cliques e arrastes futuros.

Funciona com uma pausa de alguns segundos para posicionamento manual do mouse.

Trecho de código:

python
Copiar
Editar
time.sleep(5)
x, y = pyautogui.position()
print(x, ",", y)
Benefícios do Projeto:
Demonstra automatização de tarefas repetitivas, útil para testes, processos administrativos ou jogos.

Mostra habilidade em Python e manipulação de interfaces gráficas.

Permite ajuste fácil das posições do mouse, velocidade do arraste e intervalos de tempo.

Próximos Passos / Melhorias Futuras:
Implementar loops seguros, permitindo repetição sem travar o sistema.

Adicionar opção de interrupção manual (hotkey) para interromper a execução a qualquer momento.

Criar interface gráfica para que o usuário configure posições e tempos sem alterar o código.

