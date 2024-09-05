#incluir <ultrassônico.h>
#incluir <servo.h>
#incluir 'notas_musicais.h'

#definir pinoservo 7 
#definir trigonometria 2
#definir eco 3
#definir b1a 8
#definir b1b 9
#definir a1a 10
#definir aib 11

inteirodistanciad;
inteirodistanciae;
inteiropino de campainha =6;

flutuadordistanciaobstaculo -36;

ultrassônicoultrassõnico(trig, eco);

servo servo; 

vazio configurar() {
serial.começar(9600);

servo.anexar(pinoservo);

modo pin(b1a, saida);
modo pin(b1b, saida);
modo pin(a1a, saida);
modo pin(a1b, saida);
modo pin(buzzerpin, saida);

servo.escrever(90);

}

vazio laço() {

serial.imprimir(ultrassõnico.alcance(

se(ultrassõnico.alcance(CM) <= distan
