# Código do Arduino/ESP

Mantenha neste diretório todo o código do Arduino ou ESP. Para isso, salve aqui o arquivo .ino.
[Uploading trablho.ino…]()// Definição dos pinos dos LEDs
const int led1 = 13;
const int led2 = 12;
const int led3 = 14;
const int led4 = 27;
const int led5 = 26;
const int led6 = 25;
const int led7 = 33;
const int led8 = 32;
const int led9 = 35;

// Definição dos pinos dos botões
const int botao1 = 02
;
const int botao2 = 15;
const int botao3 = 4;
const int botao4 = 5;
const int botao5 = 18;
const int botao6 = 19;
const int botao7 = 21;
const int botao8 = 22;
const int botao9 = 23;

// Variáveis de estado dos botões
int estadoBotao1;
int estadoBotao2;
int estadoBotao3;
int estadoBotao4;
int estadoBotao5;
int estadoBotao6;
int estadoBotao7;
int estadoBotao8;
int estadoBotao9;

void setup() {
  // Configuração dos pinos dos LEDs como saída
  pinMode(led1, OUTPUT);
  pinMode(led2, OUTPUT);
  pinMode(led3, OUTPUT);
  pinMode(led4, OUTPUT);
  pinMode(led5, OUTPUT);
  pinMode(led6, OUTPUT);
  pinMode(led7, OUTPUT);
  pinMode(led8, OUTPUT);
  pinMode(led9, OUTPUT);

  // Configuração dos pinos dos botões como entrada
  pinMode(botao1, INPUT);
  pinMode(botao2, INPUT);
  pinMode(botao3, INPUT);
  pinMode(botao4, INPUT);
  pinMode(botao5, INPUT);
  pinMode(botao6, INPUT);
  pinMode(botao7, INPUT);
  pinMode(botao8, INPUT);
  pinMode(botao9, INPUT);
}

void loop() {
  estadoBotao1 = digitalRead(botao1);
  estadoBotao2 = digitalRead(botao2);
  estadoBotao3 = digitalRead(botao3);
  estadoBotao4 = digitalRead(botao4);
  estadoBotao5 = digitalRead(botao5);
  estadoBotao6 = digitalRead(botao6);
  estadoBotao7 = digitalRead(botao7);
  estadoBotao8 = digitalRead(botao8);
  estadoBotao9 = digitalRead(botao9);

  digitalWrite(led1, estadoBotao1);
  digitalWrite(led2, estadoBotao2);
  digitalWrite(led3, estadoBotao3);
  digitalWrite(led4, estadoBotao4);
  digitalWrite(led5, estadoBotao5);
  digitalWrite(led6, estadoBotao6);
  digitalWrite(led7, estadoBotao7);
  digitalWrite(led8, estadoBotao8);
  digitalWrite(led9, estadoBotao9);
}

