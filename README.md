# Atividade--Lista-02

## 01-

fun main() {

    // Solicita o primeiro número
    print("Digite o primeiro número: ")
    val primeiroNumero = readLine()?.toIntOrNull()

    // Solicita o segundo número
    print("Digite o segundo número: ")
    val segundoNumero = readLine()?.toIntOrNull()

    // Verifica se a entrada foi válida
    if (primeiroNumero != null && segundoNumero != null) {
        // Calcula a diferença
        val diferenca = primeiroNumero - segundoNumero

        // Mostra o resultado
        println("A diferença entre $primeiroNumero e $segundoNumero é: $diferenca")
    } else {
        println("Erro: por favor, digite apenas números válidos.")
    }
}
