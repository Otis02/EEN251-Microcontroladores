# EEN251-Microcontroladores

- Fernanda Veneroso de Almeida (FernandaVeAL)   RA: 17.00112-9 
- Xiaoying He (Jessicahe333)                    RA: 17.00670-8
- Karina L. D. Kuroda (Otis02)                  RA: 17.00709-7

Proposta 1: Alimentador automático de cachorros e gatos 
- O alimentador terá um recipente para água e outro para ração;
- A fonte do recipente de água deve funcionar quando o bicho se aproximar do alimentador;
- O recipiente de água deve sempre permanecer no seu nível ótimo por meio de um mecanismo automático; 
- A comida deve ter um intervalo programado para que a ração seja despejada no recipente.

 - Materiais:
   - Kit de desenvolvimento da Atmel
   - Modulo Real time clock DS1307
   - Módulo Bluetooth 4.0 HC 08

- Sensor Analógico:
  - Sensor pressão - BMP280
	
- Sensor Digital:
  - Sensor obstáculo - IR
	
- Atuadores:
  - Mini bomba de água DC-JT160
  - Servo motor mg996
	
- Utilização dos materiais:
	 - O sensor de pressão ficará responsável por monitorar a quantidade de água no recipente;
	 - O sensor de obstáculo irá registrar quando o bicho de estimação chegar perto do alimentador;
	 - A mimi bomba irá agitar a água (como uma mini fonte), quando o bicho de estimação estiver por perto (Sensor de obstáculo);
	 - O módulo de tempo real irá servir para despejar a ração na hora programada;
	 - O motor servo irá ativar a porta de ração na hora programada;
	 - O módulo de bluetooth irá mandar e captar informações do dispositivo celular que estiver conectado;
         - Programar o horário que a ração seja despejada; 
         - Avisar quando o bicho de estimação estiver comendo ou bebendo água; 
         - Avisar se precisa de mais ração ou mais água.
		
--------------------------------------------------------------------------------------------------------------------------------
	
Proposta 2: Controlador de temperatura e fumaça
- Teremos um equipamento que ficará lendo a temperatura do ambiente;
- Teremos um equipamento que ficará verificando se há presença de fumaça;
- Se tivermos a temperatura alta e fumaça irá acionar a água.

 - Materiais:
   - Kit de desenvolvimento da Atmel
   - Módulo Bluetooth 4.0 HC 08
   - LED
 
 - Sensores Analógicos:
   - Sensor fumaça - MQ 02
   - Sensor temp.  - DTH11
   
 - Atuadores:
  - Mini bomba de água DC - JT160
  - Bateria 12V
  
 - Utilização dos materiais:
          - O sensor de temperatura ficará responsável por ler a cada 5 minutos a temperatura do ambiente;
	  - O sensor de fumaça irá ficar responsável por detectar se há fumaça no local;
	  - A mini bomba de água é para quando ser acionada conseguir resfriar o ambiente ou apagar inícios de incêndios;
	  - A bateria será necessária para a mini bomba de água funcionar;
	  - O módulo de bluetooth irá mandar alertas para avisar se seu ambiente está em perigo;
	  - O LED para acender quando a bomba ativar.
	  
---------------------------------------------------------------------------------------------------------------------------------
	  
Proposta 3: Bafômetro
- Medir índice de álcool no organismo de uma pessoa;
- Poderá fazer análises e pesquisas com base nos dados coletados;

 - Materiais:
   - Kit de desenvolvimento da Atmel
   - Módulo Bluetooth 4.0 HC 08

- Sensor Analógico:
  - Sensor de gás MQ-3 álcool
	
- Atuadores:
  - Display OLED i2c OLED 128x32 Px
	
- Utilização dos materiais:
	 - O sensor de gás MQ-3 identificará a presença do álcool e sua intensidade;
	 - O sensor deverá ser capaz de detectar entre 10 e 10.000ppm de álcool;
	 - O display ficará responsável por mostrar os resultados dos indivíduos;
	 - O bluetooth poderá mandar os dados para um banco de dados para uma possível análise ou pesquisa comportamental.
---------------------------------------------------------------------------------------------------------------------------------

Proposta 4: Girassol
- Irá seguir, durante o dia, a luz do sol para capitar energia no seu painel solar;
- Durante a noite irá ligar os seus leds(com a energia fornecida pelo painel solar) quando captar alguem se aproximando;

- Materiais:
   - Kit de desenvolvimento da Atmel
   - Módulo Bluetooth 4.0 HC 08
   - Leds
   - Mini Módulo Solar Carregador Placa Fotovoltaica 54 X 54 - 2v

- Sensor Analógico:
  - Sensor de Luz

- Sensor Digital:
  - Sensor obstáculo - IR
	
- Atuadores:
  - Servo motor mg996
  
- Utilização dos materiais:
	- Os sensores de luz vão monitorar onde está mais iluminado;
	- O Servo motor irá movimentar o painel solar para onde tem mais luz;
	- Se todos os sensores de luz captarem baixa luminosidade o girassol irá entrar em modo noturno.
	- No modo noturno, o girassol para de seguir a luz e os leds acendem (alimentados com a energia do painel solar) quando alguem se aproximar;
	- Qunado todos os sensores captarem uma alta luminosidade o girassol sai do modo noturno.
	- Os valores de baixa e alta luminosidade ainda não foram estabelecidos.
