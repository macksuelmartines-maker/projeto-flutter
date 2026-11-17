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
