# EEN251-Microcontroladores

- Fernanda Veneroso de Almeida (FernandaVeAL)   RA: 17.00112-9 
- Xiaoying He (Jessicahe333)                    RA: 17.00670-8
- Karina L. D. Kuroda (Otis02)                  RA: 17.00709-7

Proposta 1: Alimentador automático de cachorros e gatos 
- O alimentador terá um recipente para água e outro para ração;
- A fonte do recipente de água deve funcionar quando o bicho se aproximar do alimentador;
- O recipentede água de sempre permanecer no seu nível ótimo por meio de um mecanismo automático; 
- A comida deve ter um intervalo programado para que a ração seja despejada no recipente

 - Materiais:
   - Kit de desenvolvimento da Atmel
   - Modulo Real time clock DS1307
   - Módulo Bluetooth 4.0 HC 08

- Sensor Analógico:
  - Sensor pressão - BMP280
	
- Sensor Digital
  - Sensor obstáculo - IR
	
- Atuadores:
  - Mini bomba de água DC-JT160
  - Servo motor mg996
	
- Utilização dos materiais:
	 - O sensor de pressão ficará responsável por monitorar a quantidade de água no recipente;
	 - O Sensor de obstáculo irá registrar quando o bicho de estimação chegar perto do alimentador;
	 - A mimi bomba irá agitar a água(como uma mini fonte), quando o bicho de estimação estiver por perto(Sensor de obstáculo);
	 - O módulo de tempo real irá servir para despejar a ração na hora programada;
	 - O motor servo irá ativar a porta de ração na hora programada.
	 - O módulo de bluetooth irá mandar e captar informações do dispositivo celular que estiver conectado:
         - Programar o horário que a ração seja despejada; 
         - Avisar qunado o bicho de estimação estiver comendo ou bebendo água; 
         - Avisa de precisa de mais ração ou mais água.
		
	
	
