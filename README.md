# NULL-SAFETY

// 2 - Introducao Null_Safety
// Linguagem - Dart

void main() {
String? nome;
nome = 'Gabriel';
print(nome);
nome = null;

late String sobrenome;
sobrenome = 'Fulano';
print(sobrenome);
//sobrenome = null;
}


/* 1 - Variável nome:
É declarada como String?, o que significa que pode conter um valor ou ser nula.
Primeiro, atribui-se o valor 'Gabriel' à variável nome.
Em seguida, imprime-se o valor de nome.
Por fim, a variável nome é definida como null.

*/

/* 2 - Variável sobrenome:
É declarada como late String, o que indica que será inicializada posteriormente.
Atribui-se o valor 'Fulano' à variável sobrenome.
Imprime-se o valor de sobrenome.
Finalmente, a variável sobrenome é definida como null.

*/

/* Resumo: 
Em resumo, o código demonstra o uso de variáveis nulas (String?) e variáveis atrasadas (late String). 
O resultado da execução será a impressão dos valores 'Gabriel' e 'Fulano'.

*/
****
