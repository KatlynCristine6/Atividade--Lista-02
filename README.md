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

## 04-

fun main() {

    println("Digite o lado do quadrado:")
    val lado_quadrado = readLine()!!.toDouble()  
    
    val area = lado_quadrado * lado_quadrado

    println("A área do quadrado é igual: $area")
    
}

## 05-

fun main() {

    println("Digite a base do triângulo:")
    val base = readLine()!!.toDouble()  
    
    println("Digite a altura do triângulo:")
    val altura = readLine()!!.toDouble()
    
    var area = base * altura / 2

    println("A área do triângulo é igual: $area")
    
}

## 07-

```
fun main() {
   
println("Digite a nota 1")
val nota1 = readLine()!!.toDouble()
println("Digite a nota 2")
val nota2 = readLine()!!.toDouble()
println("Digite a nota 3")
val nota3 = readLine()!!.toDouble()

var media = (nota1 + nota2 + nota3) / 3

   
print("A média final é: ${media}")

}
```
## 16-
```
fun main() {

println("ano_nascimento")
val ano_nascimento = readLine()!!.toDouble()
println("ano_atual")
val ano_atual = readLine()!!.toDouble()

var idade_anos = ano_atual - ano_nascimento
var idade_meses = idade_anos * 12
var idade_dias =  idade_anos * 365
var idade_semanas = idade_dias / 7
   
print("Idade em anos: ${idade_anos}")

print("Idade em meses: ${idade_meses}")

print("Idade em dias: ${idade_dias}")

print("Idade em semanas: ${idade_semanas}")

}
```

## 17-

```
fun main() {
   
println("Digite o valor do saco em kg:")
val peso_saco_kg = readLine()!!.toDouble()
println("Digite a quantidade que o gato come em gramas:")
val qtd_diaria_gato_g = readLine()!!.toDouble()

var total_inicial_g = peso_saco_kg * 1000
var total_consumido_g = qtd_diaria_gato_g * 2 * 5
var resto_g= total_inicial_g - total_consumido_g
   
print("Resto em gramas: ${resto_g}")

}
```

## 19-

fun main() {

    println("Digite o comprimento da caixa retangular:")
    val comprimento = readLine()!!.toDouble()  
    
    println("Digite a largura da caixa retangular:")
    val largura = readLine()!!.toDouble()
    
    println("Digite a altura da caixa retangular:")
    val altura = readLine()!!.toDouble()
    
    var volume = comprimento * largura * altura 

    println("O volume da caixa retangular é igual: $volume centímetros cúbicos")
    
}

## 21-
```
fun main() {
println("Digite um valor em dólar para aa conversão:")
val valor_dolar = readLine()!!.toDouble()  

println("Digite um valor da cotação do dólar:")
val cotacao = readLine()!!.toDouble()  

var valor_real = valor_dolar * cotacao
println("Valor em real: $valor_real (considerando a cotação de 5.24")
}
```
## 25-
```
fun main() {
   
println("Digite um numero inteiro")
val numero_i = readLine()!!.toDouble()

var antecessor = numero_i - 1
var sucessor = numero_i + 1
   
print("O antecessor de ${numero_i} é ${antecessor}")
print("O sucessor de ${numero_i} é ${sucessor}")
}
```
