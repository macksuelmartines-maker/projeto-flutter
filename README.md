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

