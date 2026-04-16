# Exercícios 

## Exercício 1 - Pergunta conceitual 

### Internet das Coisas (IoT)
 ​A Internet das Coisas (IoT) é o conceito de conectar objetos físicos do dia a dia à internet, permitindo que eles coletem, processem e troquem dados entre si ou com sistemas centrais. Isso transforma objetos "burros" em dispositivos inteligentes que podem ser monitorados ou controlados remotamente.
 
### Exemplo: 
Uma geladeira inteligente que monitora a validade dos produtos e envia uma lista de compras para o seu celular.

## Exercício 2 - Pergunta de aplicação

### Iluminação Automatizada
​Um sistema embarcado (como um Arduino) pode ser conectado a um sensor de presença (PIR) ou de luminosidade (LDR). **O sistema processa o sinal do sensor:** se detectar movimento ou baixa luz natural, ele aciona um relé, que funciona como um interruptor eletrônico para ligar a lâmpada. Ao parar de detectar presença por um tempo X, o microcontrolador desliga a carga automaticamente, economizando energia.


## Exercício 3 - Pergunta de investigação

### Circuito com LED (Observação)

​Ao montar um LED com um resistor no simulador, o parâmetro delay() no código define o tempo de intermitência (blink).

- **​Delay curto (ex: 100ms):** O LED pisca freneticamente, parecendo um alerta rápido.

- **​Delay longo (ex: 2000ms):** A alternância entre aceso e apagado é lenta e bem definida.

 - **Delay muito baixo (ex: 10ms):** O olho humano mal percebe o piscar, parecendo que o LED está apenas com o brilho mais fraco (efeito de persistência da visão).
  


  ## Exercício 6 - Pergunta de aplicação


### Projeto: Alerta de Inundação Residencial

**​Problema:** Alagamentos em áreas de serviço ou porões.

**​Solução:** Utilizar um sensor de nível de água ou um sensor de umidade de solo no chão.

**​Funcionamento:** Quando o sensor detectar a presença de água acima de um limite, o 
microcontrolador aciona um buzzer (alarme sonoro) e um LED vermelho, avisando o morador antes que o dano aumente.


## Exercício 7 - Pergunta de investigação

### Circuito com Botão

​Nesse circuito, o botão funciona como uma entrada digital. O pino do botão é configurado como INPUT (geralmente com um resistor de pull-up ou pull-down). No código, uma estrutura condicional (if) verifica o estado do pino: se o botão for pressionado, o circuito fecha, o microcontrolador lê o sinal e envia um comando HIGH para o pino do LED, completando a lógica de acionamento por demanda.
# Exercício 8 - Pergunta de reflexão

## Movimento Maker


​O movimento maker (cultura do "faça você mesmo") democratiza o acesso à tecnologia ao incentivar o aprendizado prático (learning by doing). Ele tira a teoria do papel, permitindo que estudantes criem protótipos reais com ferramentas acessíveis. Isso estimula a criatividade, o raciocínio lógico e a resolução de problemas reais de forma colaborativa e interdisciplinar.


## Exercício 9 - Pergunta de aplicação

### Irrigação Automatizada

**​Eles trabalham em um ciclo de feedback:** ​O sensor de umidade do solo mede a quantidade de água na terra e envia esse dado ao controlador.
​O controlador compara o valor com o limite programado.
​Se o solo estiver seco, o controlador aciona o atuador (bomba d'água ou válvula solenoide) para iniciar a rega.
​Quando o sensor detecta que a umidade ideal foi atingida, o controlador desliga o atuador.


## Exercício 10 - Pergunta de investigação

### Modificação de Projeto (Exemplo)
​Ao explorar um projeto de semáforo no Wokwi, alterei o parâmetro da variável de tempo do LED Verde de 5000ms para 10000ms.

**Resultado:** O fluxo simulado de carros "passaria" por mais tempo, aumentando a vazão da via. Essa modificação mostra como pequenos ajustes no código alteram o comportamento físico do sistema sem precisar trocar nenhum componente de hardware.


