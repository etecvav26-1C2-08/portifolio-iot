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
  


  # Exercicío 4 - Pergunta de reflexão


  ## Hardware Open Source

**​Vantagens:** Baixo custo, grande comunidade de suporte para resolver erros e flexibilidade para modificar o design do hardware conforme a necessidade do projeto.
 
**​Desvantagens:** Menor garantia de suporte técnico oficial, possíveis vulnerabilidades de segurança se o código não for bem auditado e variações de qualidade entre diferentes fabricantes do mesmo design aberto.
# Exercício 5 - Pergunta conceitual

## Função do Microcontrolador

​O microcontrolador atua como o **"cérebro"** do sistema embarcado. Ele é um computador em um único chip que executa o código programado para ler sinais de entrada (sensores), processar essas informações logicamente e tomar decisões, enviando comandos para os periféricos de saída (atuadores).


# Exercício 6 - Pergunta de aplicação


## Projeto: Alerta de Inundação Residencial

**​Problema:** Alagamentos em áreas de serviço ou porões.

**​Solução:** Utilizar um sensor de nível de água ou um sensor de umidade de solo no chão.

**​Funcionamento:** Quando o sensor detectar a presença de água acima de um limite, o 
microcontrolador aciona um buzzer (alarme sonoro) e um LED vermelho, avisando o morador antes que o dano aumente.


# Exercício 7 - Pergunta de investigação

## Circuito com Botão

​Nesse circuito, o botão funciona como uma entrada digital. O pino do botão é configurado como INPUT (geralmente com um resistor de pull-up ou pull-down). No código, uma estrutura condicional (if) verifica o estado do pino: se o botão for pressionado, o circuito fecha, o microcontrolador lê o sinal e envia um comando HIGH para o pino do LED, completando a lógica de acionamento por demanda.


