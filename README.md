# TRABALHO-RETIFICADOR-DE-ONDA-COMPLETA


<img width="538" alt="4" src="https://github.com/user-attachments/assets/a965110b-a8d8-46ee-87cb-8ffff98f2294" />

O esquema que você forneceu no Proteus representa um retificador de onda completa com filtro capacitivo e um regulador de tensão. Vamos detalhar cada componente e sua função no circuito:
TR1 -Transformador
O transformador vai reduzir a tensão da rede elétrica para uma tensão mais baixa, a melhor para o circuito. 
BR1 – Ponte Retificadora
Vai converter a tensão alternada do secundário do transformador em tensão contínua 
C1 - Capacitor 
O capacitor escolhe a melhor saída do BR1, ajudando na tensão. Vai armazenar carga durante os picos da tensão e libera essa carga quando a tensão cai, reduzindo a ondulação.
U1 - Regulador de Tensão
O regulador de tensão mantém a saída em uma tensão constante de 5V, independentemente das variações na entrada 
R1 - Resistor
Limita a corrente que passa pelo LED, protegendo o led de sobrecorrente.
LED
Indica se o circuito está funcionando corretamente 
O circuito é uma configuração básica de uma fonte de alimentação DC regulada, comumente usada em projetos eletrônicos para fornecer uma alimentação estável e confiável a componentes que operam com 5V.
É um circuito básico que é utilizado para alimentar circuitos que precisam de 5V


![󠀡 (1)](https://github.com/user-attachments/assets/52c88783-3a93-4d22-ad76-8bbf9c9faf3b)
 
Este é o circuito de uma fonte de alimentação regulada em uma protoboard. O transformador reduz a tensão da rede elétrica, que é então retificada e regulada para depois fornecer uma saída estável, 5V DC. O LED aceso indica que o circuito está funcionando corretamente. 🚀
Transformador usado para reduzir ou isolar a tensão da rede elétrica (AC) para um nível mais 
Capacitores: usado pra filtrar a tensão ou estabilizar a alimentação do circuito. 
Diodos: formam uma ponte retificadora que é usado para converter AC em DC 
Resistores: limita a corrente no circuito ou forma divisores de tensão 
LEDs: Ira mostrar se está funcionando certo
O transformador reduz a tensão AC da rede.


![󠀡 (2)](https://github.com/user-attachments/assets/201fb898-1182-4dc4-a0d0-d13936d8bdc4)

1.	Transformador: Reduz a alta tensão da rede elétrica para um valor mais baixo permitindo que os componentes do circuito operem com segurança.
2.	Retificação: Os diodos convertem a tensão AC reduzida em uma tensão DC pulsante. O LED aceso indica que a corrente está fluindo e que a retificação está ocorrendo.
3.	Filtragem: O capacitor eletrolítico armazena energia durante os picos da tensão e a libera durante as quedas, suavizando a tensão pulsante e gerando uma tensão DC mais estável.
4.	Regulação: Um regulador pode estar presente para ajustar precisamente a tensão de saída para 5V, compensando variações e garantindo uma tensão constante. A medição de 4,96V mostra que o sistema está funcionando corretamente, fornecendo uma tensão próxima de 5V.
5.	Medição: O multímetro digital, configurado para tensão DC, confirma que a combinação de transformação, retificação, filtragem e regulação está proporcionando uma saída estável e adequada para circuitos eletrônicos.


![󠀡 (3)](https://github.com/user-attachments/assets/67a76252-de7c-4099-b623-113ef46cb8f5)
 
1.	Transformador: Reduz a tensão da rede (110V ou 220V AC) para um nível mais baixo, por exemplo, 9–12V AC, adequado para os circuitos eletrônicos.
2.	Retificação: Os diodos, possivelmente organizados em uma ponte retificadora, convertem a tensão AC reduzida em uma tensão DC pulsante, permitindo que a corrente flua em uma única direção.
3.	Filtragem: Um capacitor eletrolítico armazena carga durante os picos da tensão pulsante e libera durante os vales, suavizando a tensão e reduzindo a ondulação, o que resulta numa tensão DC mais estável.
4.	Regulação (Opcional): Caso esteja presente um regulador de tensão, ele ajusta e estabiliza a tensão para um valor fixo. No cenário, o circuito apresenta uma tensão estável de 7,5V, indicando que os componentes estão funcionando como esperado.
5.	Protoboard e Medição: A montagem em protoboard facilita a montagem, testes e ajustes do circuito. O multímetro digital, configurado para medir tensão DC, exibe 7,5V, confirmando a eficácia da transformação, retificação, filtragem.

![x](https://github.com/user-attachments/assets/f59d47b9-4714-4634-b961-67bb426a7660)


Este layout de PCB é destinado a um circuito de retificação simples, que converte corrente alternada  em corrente contínua . Foi realizado assim para ser de fácil montagem, utilizando componentes padrão como uma ponte retificadora, capacitores, resistores, diodos e conectores 


![y](https://github.com/user-attachments/assets/ce5a675e-b0f5-485d-a063-41397e4fbc14)

Essa seria o retrado em 3d da placa PCB mostrada a cima.
