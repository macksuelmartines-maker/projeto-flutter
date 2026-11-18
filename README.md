# projeto-estudo flutter 
void main() {
  String nome = "Macksuel";
  int idade = 16;
  double altura = 1.75;
  bool estudante = true;

  print('meu nome é $nome');
  print('bem eu tenho $idade anos');
  print('Bem eu tenho $altura de tamanho');
  print('Ano que vem terei ${idade + 1} anos');
  print('Altura $altura # | EStudante $estudante');

  nome = "João";
  print("Segundo nome é $nome");

  const pi = 3.14149;
  final anoNascimento = 2010;

  // Variáveis 'const' e 'final' não podem ter seus valores alterados depois de criadas.
  print('PI: $pi | Ano de nascimento: $anoNascimento');
}


Codigo abaixo As contas matematicas que da para fazer

void main() {
  int a = 17;
  int b = 5;

  print(a + b);
  print(a - b);
  print(a * b);
  print(a / b);
  print(a ~/ b);
  print(a % b);
}

Abaixo esta o codigo de como o calculo de notas escolares ocorre nesta linguagem

void main() {
  double nota1 = 4.5;
  double nota2 = 9.5;
  double media = (nota1 + nota2) / 2;

  print('Média: $media');

  if (media >= 7) {
    print('Aprovado');
  } else if (media >= 5) {
    print('Em recuperação');
  } else {
    print('Reprovado');
  }
}


## Atividades feitas em aula

fixa pessoal

void main() {
  String nome = "Macksuel";
  int idade = 16;
  double altura = 1.75;
  bool trabalha = false;

  print('FICHA PESSOAL');
  print('Nome: $nome');
  print('Idade: $idade anos');
  print('Altura: $altura m');
  print('Trabalha: $trabalha');
}

Calculadora Basica

void main() {
  int a = 17;
  int b = 5;

  print('Soma: ${a + b}');
  print('Subtração: ${a - b}');
  print('Multiplicação: ${a * b}');
  print('Divisão: ${a / b}');
  print('Divisão inteira: ${a ~/ b}');
  print('Resto: ${a % b}');
}

media de tres Notas

void main() {
  double nota1 = 7.5;
  double nota2 = 8.0;
  double nota3 = 6.2;

  double media = (nota1 + nota2 + nota3) / 3;

  print('Média: ${media.toStringAsFixed(1)}');
}

Horas em minutos

void main() {
  int totalMinutos = 200;

  int horas = totalMinutos ~/ 60;
  int minutos = totalMinutos % 60;

  print('$horas h e $minutos min');
}

Troca de valores

void main() {
  int a = 5;
  int b = 9;
  print('Antes da troca: a = $a, b = $b');
  int temp = a;
  a = b;
  b = temp;
  print('Depois da troca: a = $a, b = $b');
}

Positvo ou negativo

void main() {
  double numero = -4.5;

  if (numero > 0) {
    print('$numero é positivo.');
  } else if (numero < 0) {
    print('$numero é negativo.');
  } else {
    print('O número é zero.');
  }
}
Idade criança, adolecente, adulto ou idoso



void main() {
  int idade = 25;

  if (idade < 0) {
    print('Idade inválida.');
  } else if (idade <= 11) {
    print('Com $idade anos, é criança.');
  } else if (idade <= 17) {
    print('Com $idade anos, é adolescente.');
  } else if (idade <= 59) {
    print('Com $idade anos, é adulto.');
  } else {
    print('Com $idade anos, é idoso.');
  }
}





