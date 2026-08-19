
# Exercícios 
Larissa, Kevin Willian e Manuela

## Exercício 1 - Pergunta conceitual

### O LED acendeu. Está tudo certo?

Não. Mesmo que o LED tenha acendido, não significa que o circuito esteja totalmente correto. É importante verificar a tensão, a corrente e a resistência para ter certeza de que os componentes não estão recebendo valores acima do que suportam.

O resistor é importante porque ajuda a controlar a corrente que passa pelo LED e evita que ele seja danificado.

---

## Exercício 2 - Pergunta de aplicação

### Iluminação Automatizada

Para evitar que as luzes fiquem ligadas sem necessidade, poderia ser usado um sensor de presença.

**Funcionamento:** O sensor detecta se existe alguém na sala e manda essa informação para o microcontrolador. Depois disso, o microcontrolador decide se deve ligar ou desligar a lâmpada usando um relé.

**Entrada:** Sensor de presença.

**Processamento:** Microcontrolador.

**Saída:** Relé e lâmpada.

**Fluxo:**

`Sensor de presença → Microcontrolador → Relé → Lâmpada`

Quando não tiver ninguém na sala por um determinado tempo, o sistema pode desligar a luz automaticamente.

---

## Exercício 3 - Pergunta de classificação

### Sensor ou atuador?

- **Sensor de temperatura:** entrada
- **Sensor de luminosidade:** entrada
- **Botão:** entrada
- **Motor:** saída
- **LED:** saída
- **Buzzer:** saída
- **ESP32:** processamento

Um projeto pode precisar de vários sensores e atuadores porque cada um pode ter uma função diferente. Por exemplo, um sensor pode medir a temperatura enquanto outro verifica a luminosidade, e o sistema pode usar essas informações para controlar um motor e um LED.

---

## Exercício 4 - Pergunta de reflexão

### Automatizar tudo é sempre melhor?

Não. Se o sensor indicar que o solo está seco, não significa que a bomba deve ligar imediatamente.

O sistema também pode verificar se o sensor está funcionando corretamente, se existe água disponível, quanto tempo a bomba deve ficar ligada e se está dentro do horário programado.

Também seria interessante ter uma opção para ligar a bomba manualmente caso seja necessário.

Isso é importante porque um sistema automático também pode apresentar falhas e precisa estar preparado para situações inesperadas.

---

## Exercício 5 - Pergunta de investigação

### Quando um projeto se torna IoT?

Os dois sistemas usam sensores e microcontroladores, mas existe uma diferença entre eles.

**Sistema A:**

`Sensor de temperatura → Arduino → LED`

Nesse caso, o sistema funciona sozinho e não possui conexão com a Internet.

**Sistema B:**

`Sensor de temperatura → ESP32 → Wi-Fi → Internet → Aplicativo`

Nesse sistema, os dados podem ser enviados pela Internet e o usuário consegue acompanhar as informações pelo aplicativo.

Por isso, o **Sistema B é o que mais se encaixa no conceito de IoT**, pois possui conexão com a Internet e permite a troca de informações entre o dispositivo e outros sistemas.
