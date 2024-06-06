🌊 Ocean Guardian
Ocean Guardian é uma plataforma web que monitora a saúde dos oceanos em tempo real. Usando sensores IoT e dados de satélite, fornece informações críticas sobre a qualidade da água, temperatura e níveis de poluição para ajudar comunidades costeiras e empresas a promover uma gestão sustentável dos mares.

![Ocean-Guardian](https://github.com/Caue-Garaude/arduino-Ocean-Guardian/assets/162592664/636afb78-9699-4300-87d8-465173be473c)


📋 Índice
Visão Geral
Componentes
Montagem do Circuito
Instalação
Uso
Contribuição
Licença
🌟 Visão Geral
Identificação do Problema
Os oceanos são cruciais para a vida na Terra, mas enfrentam desafios graves como poluição e mudanças climáticas. Comunidades costeiras e empresas dependem de dados precisos para tomar decisões que protejam os ecossistemas marinhos e garantam uma exploração sustentável.

Solução Proposta
Ocean Guardian oferece uma solução integrada para monitorar a saúde dos oceanos usando:

Sensores IoT: Para coletar dados sobre a qualidade da água e temperatura.
Satélites: Para monitorar áreas oceânicas extensas.
Plataforma Web: Para visualizar e analisar os dados em tempo real.
🧩 Componentes
Para a implementação do protótipo, utilizamos:

Arduino Uno: Microcontrolador principal.
Sensor de Temperatura LM35: Para medir a temperatura da água.
Sensor de Luminosidade (LDR): Para detectar variações na luminosidade.
LED: Para indicar o status de operação.
Especificações dos Componentes
Arduino Uno

Alimentação: 7-12V
I/O Digital: 14 (6 PWM)
I/O Analógica: 6
Sensor de Temperatura LM35

Faixa de temperatura: -55°C a 150°C
Precisão: ±0.5°C
Sensor de Luminosidade (LDR)

Faixa de Resistência: Alta resistência (escuro) a baixa resistência (luz)
LED

Cor: Vermelho
Tensão de operação: 2V
Corrente de operação: 20mA
🔧 Montagem do Circuito
 https://www.tinkercad.com/things/gcfAtBfOcGx-ocean-guardian?sharecode=hPULp03dIx5VxsCQvUp98UyV1qOmsiE9QgzHFFPIP30

Passos para Montagem
Conecte o LM35:

Pino 1 (VCC) -> 5V no Arduino.
Pino 2 (Vout) -> A0 no Arduino.
Pino 3 (GND) -> GND no Arduino.
Conecte o LDR:

Um lado -> 5V no Arduino.
Outro lado -> A1 no Arduino e resistor de 10kΩ.
Outro lado do resistor -> GND no Arduino.
Conecte o LED:

Anodo (perna longa) -> Pino 13 no Arduino.
Catodo (perna curta) -> GND no Arduino.
Diagrama de Montagem
Esquema: Veja o esquema de montagem.
🚀 Instalação
Requisitos
Software
Arduino IDE
Tinkercad (para simulação)
Passos
Clone o Repositório

bash
git clone https://github.com/Caue-Garaude/arduino-Ocean-Guardian.git
cd arduino-Ocean-Guardian
Abra o Projeto na Arduino IDE

Navegue até ocean-guardian.ino e abra-o com a Arduino IDE.
Carregue o Código no Arduino

Conecte o Arduino ao seu computador.
Selecione a porta correta e carregue o código.
📖 Uso
Inicie o Sistema

Conecte o Arduino à fonte de alimentação.
Verifique se o LED pisca para indicar o funcionamento.
Monitore os Dados

Abra o Serial Monitor na Arduino IDE.
Veja as leituras de temperatura e luminosidade em tempo real.
Visualize e Analise

Use os dados para monitorar a saúde dos oceanos.
Integre com a plataforma web para análise avançada.
Exemplo de Saída
yaml
Temperature: 24.5 °C, Luminosity: 512
Sending data -> Temperature: 24.5, Luminosity: 512
🛠 Contribuição
Contribuições são bem-vindas! Siga os passos abaixo para contribuir:

Fork o Projeto

Crie uma Nova Branch

bash
git checkout -b feature/nova-funcionalidade
Faça Commit das Suas Alterações

bash
git commit -m 'Adiciona nova funcionalidade'
Push para a Branch

bash
git push origin feature/nova-funcionalidade
Abra um Pull Request

📄 Licença
Este projeto é licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.

