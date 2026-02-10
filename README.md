# Atividade--Lista-02

## 01-
```
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
```
## 02-
```
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
```
## 03-
```
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
```
## 04-
```
fun main() {

    println("Digite o lado do quadrado:")
    val lado_quadrado = readLine()!!.toDouble()  
    
    val area = lado_quadrado * lado_quadrado

    println("A área do quadrado é igual: $area")
    
}
```
## 05-
```
fun main() {

    println("Digite a base do triângulo:")
    val base = readLine()!!.toDouble()  
    
    println("Digite a altura do triângulo:")
    val altura = readLine()!!.toDouble()
    
    var area = base * altura / 2

    println("A área do triângulo é igual: $area")
    
}
```

## 06-
```
fun main() {

    val peso = 45

    val altura = 1.56

    val imc = peso / (altura * altura)

    if (imc < 18.5){
        print(" $imc = Peso baixo")
    }

    else if(imc > 18.5){
        print(" $imc = Peso normal")

    }

    else if(imc > 25){

        print(" $imc = Sobrepeso")
    }

    else if(imc >30){

        print(" $imc = Obesidade")
    } 

}
```
## 07-
```
fun main() {

    val diasTotais = readln().toInt()

    val anos = diasTotais / 365
    val restoAnos = diasTotais % 365

    val meses = restoAnos / 30
    val dias = restoAnos % 30

    println("Sua idade em anos é " + anos + ", sua idade em meses " + meses + ", sua idade em dias é " + dias)
}
```

## 08-
```
fun main() {
    print("Digite a primeira nota:")
    val nota1 = readLine()!!.toIntOrNull()?: 0
    
    print("Digite a segunda nota:")
    val nota2 = readLine()!!.toIntOrNull()?: 0
    
    print("Digite a terceira nota:")
    val nota3 = readLine()!!.toIntOrNull()?: 0
    
    var media_final = (nota1 + nota2 + nota3) / 3

    print("O resultado da média é: $media_final")
}
```
## 09-
```
fun main() {

    val tempoSegundos = readln().toDouble()

    val horas = tempoSegundos / 3600
    val restoHoras = tempoSegundos % 3600

    val minutos = restoHoras / 60
    val segundos = restoHoras % 60

    print("Em horas são: " + horas + ", em minutos são: " + minutos +  ", e em segundos são: " + segundos)
}
```
## 10-
```
import kotlin.math.sqrt
import kotlin.math.pow

fun main() {

    val x1 = readln().toDouble()
    val y1 = readln().toDouble()

    val x2 = readln().toDouble()
    val y2 = readln().toDouble()

    val distancia = sqrt((x2 - x1).pow(2) + (y2 - y1).pow(2))

    println("A distancia entre os pontos Ã©: " + distancia)
}
```
## 11-
```
fun main() {
    print("Digite o primeiro número: ")
    val A = readLine()?.toIntOrNull() ?: 0

    print("Digite o segundo número: ")
    val B = readLine()?.toIntOrNull() ?: 0

    print("Digite o terceiro número: ")
    val C = readLine()?.toIntOrNull() ?: 0

    val R = (A + B) * (A + B)
    val S = (B + C) * (B + C)

    val D = (R + S) / 2

    print("D = $D")
}
```
## 12-
```
fun main() {
    print("Digite o valor do custo de fábrica de um carro:")
    val fabrica = readLine()!!.toIntOrNull()?: 0
    
    print("Digite a porcentagem do distribuidor:")
    val porcentagem_dist = readLine()!!.toIntOrNull()?: 0
    
    print("Digite a porcentagem calculada pelo imposto:")
    val porcentagem_imp = readLine()!!.toIntOrNull()?: 0
    
    var custo_final = fabrica + (fabrica * 0.28) + (fabrica * 0.45)

    print("O custo total do distribuidor é de: $custo_final")
}
```
## 13-
```
import java.util.Scanner

fun main() {
    val sc = Scanner(System.`in`)

    val a = sc.nextDouble()
    val b = sc.nextDouble()
    val c = sc.nextDouble()
    val d = sc.nextDouble()
    val e = sc.nextDouble()
    val f = sc.nextDouble()

    val den = a * e - b * d

    if (den != 0.0) {
        val x = (c * e - b * f) / den
        val y = (a * f - c * d) / den

        println("x = $x")
        println("y = $y")
    } else {
        println("Sem solução única")
    }
}
```
## 14-
```
fun main() {

println("Digite o salário_mensal:")
val salario_mensal = readLine()!!.toDouble() 
println("Digite a porcentagem de aumento:")
val porcentagem_aumento = readLine()!!.toDouble()

var aumento = salario_mensal * (porcentagem_aumento / 100)

var novo_salario = (salario_mensal + aumento)


println("O novo salário do funcionário é: $novo_salario")
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

## 18-
```
fun main() {
    println("Digite um valor:")
    var A = readLine()!!.toDouble()

    println("Digite outro valor:")
    var B = readLine()!!.toDouble()

    val troca = A
    A = B
    B = troca

    println("Após a troca - a = $A, b = $B")
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

## 20-
```
fun main() {
    println("Digite um valor:")
    val A = readLine()!!.toDouble()

    println("Digite outro valor:")
    val B = readLine()!!.toDouble()

    var quadrado_A = ( A * A )
    var quadrado_B = ( B * B )
    
    var resultado = (quadrado_A - quadrado_B) 

    println("O resultado do quadrado da diferença do primeiro valor em relação ao segundo é de: $resultado")
}
```
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

## 22-
```fun main() {
println("Digite o primeiro valor:")
val A = readLine()!!.toDouble()  

println("Digite o segundo valor:")
val B = readLine()!!.toDouble()  

println("Digite o terceiro valor:")
val C = readLine()!!.toDouble()  


var soma_dos_quadrados = (A * A) + (B *B)  + (C * C)


println("O valor das somas dos quadrados é: $soma_dos_quadrados")
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
