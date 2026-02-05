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

## 02-

fun main() {

    // Solicita o primeiro nome
    print("Digite o primeiro nome: ")
    val primeiroNome = readLine()  

    // Solicita o segundo nome
    print("Digite o segundo nome: ")
    val segundoNome = readLine()  
    
   
    if (primeiroNome != null && segundoNome != null) {
      
        val resultado = primeiroNome + " " + segundoNome

        println("Nome completo: $resultado")
    } else {
        println("Erro: você não digitou um nome válido.")
    }
}

## 03-

fun main() {

    println("Digite o primeiro número:")
    val primeiroNumero = readLine()!!.toDouble()  

    println("Digite o segundo número:")
    val segundoNumero = readLine()!!.toDouble()  

    val subtracao = primeiroNumero - segundoNumero
    val multiplicacao = primeiroNumero * segundoNumero
    val divisao = primeiroNumero / segundoNumero

    println("Subtração: $subtracao")
    println("Multiplicação: $multiplicacao")
    println("Divisão: $divisao")
}
