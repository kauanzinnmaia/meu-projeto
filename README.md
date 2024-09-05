#incluir <Ultrassônico.h>
#incluir <Servo.h>
#incluir "notas_musicais.h"

#definir pinoServo 7
#definir Trigometria 2
#definir Eco 3
#definir B1A 8
#definir B1B 9
#definir A1A 10
#definir A1B

InteriordistanciaD;vazio laço() ( Serial. imprimir(ultrassônico.Alcancel se(ultrassônico.Alcance(CM) <= distar Andar (5): Inteirostatus =Radar(): atraso(500); se(estado ==1) { Andar (2): atraso(600); Andar (4): atraso(400): Andar (5); se(estado ==2) 4 Andar (2); atraso(600); Andar (3); atraso(400); Andar (5): se(estado ==0) { Andar (2); atraso(500); Andar (4); atraso(300); Andar (5); atraso(1000); outrol Andar (1);
InteriordistanciaE;
Interiorpino de campainha =6;

flutuadordistancia0bstáculo =35;

Ultrassônicoultrassônico(Trig, Eco);

Servo servo:

vazio configurar () {
1 Serial. começar (9600);

servo.anexar (pinoServo);
//pinos da ponte H
Modo pin(B1A, SAIDA);
Modo pin(B1B, SAÍDA);
Modo pin(AIA, SAÍDA):
Modo pin(A18, SAÍDA);
Modo pin(buzzerPin, SAÍDA):

servo, escrever (90);
//radar();
}

vazio laço() {
Serial. imprimir(ultrassônico.Alcancel se(ultrassônico.Alcance(CM) <= distar
 Andar (5):
  Inteirostatus =Radar():
  atraso(500);
  se(estado ==1) { 
  Andar (2):
  atraso(600);
  Andar (4):
  atraso(400):
  Andar (5);
}
se(estado ==2) {
 Andar (2);
 atraso(600);
 Andar (3);vazio laço() ( Serial. imprimir(ultrassônico.Alcancel se(ultrassônico.Alcance(CM) <= distar Andar (5): Inteirostatus =Radar(): atraso(500); se(estado ==1) { Andar (2): atraso(600); Andar (4): atraso(400): Andar (5); se(estado ==2) 4 Andar (2); atraso(600); Andar (3); atraso(400); Andar (5): se(estado ==0) { Andar (2); atraso(500); Andar (4); atraso(300); Andar (5); atraso(1000); outrol Andar (1);
 atraso(400);
 Andar (5):
 }
 se(estado ==0) {
 Andar (2);
 atraso(500);
 Andar (4);
 atraso(300);
 Andar (5);
 }
 atraso(1000);
 outro{
 Andar (1);
 }


