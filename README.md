# medio.curso.servo
examen
Problema 1

n=[1 10 100 500 1000 2000 4000 8000];
y=(1 + (1./n)).^n
B=exp(1)
x=[1 1 1 1 1 1 1 1];
x1= x*B
error=[y-x1]


Problema 2


A=[2 6;3 9];
B=[1 2;3 4];
C=[-5 5;5 3];
X=[0 0;0 0];
G=[A,X,X;X,B,X;X,X,C


Problema 3

X1=[-10:0.01:-5];
X2=[-5:0.01:2];
X3=[2:0.01:10];
X01=2+sin(X1);
X02=exp(X2);
X03=log((X3).^2)+1;
plot(X1,X01)
hold on
plot(X2,X02)
hold on
plot(X3,X03)
