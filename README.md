# Introdução a Linguagem Kotlin

> 🐙 Variáveis:

Val ⇒ não muda

Var ⇒ pode mudar 

---

🚀 Declarando variáveis no Kotlin:

```jsx
fun main() {
    var name = "Bem-vinda"
    println(name)
}
```

---

📋 Planejamento do desenvolvimento App Mobile com a Linguagem Kotlin, projeto App Mobile, calcular IMC, focado em Lógica de programação, operadores matemáticos,  Algoritmos, variáveis, referente ao curso DevSpace, mentor Roque Buarque.

> 📈 Operadores matemáticos:
> 

Utilização do calculo IMC:

IMC ⇒ peso(kg) / altura(m) X altura(m)

---

## Linguagem de Programação  - KOTLIN

> ✅ Boolean como declarar :
> 

```kotlin
val bool: Boolean = true
val bool1: Boolean = false

printIn(bool)
printIn(bool1)

if(bool){
// Se for verdadeiro aqui executa
printIn("Minha condição e verdadeira")
} else{
//Se for false executa aqui
printIn("Minha condição é false")
}

```

> ♟️ Operadores lógicos:
> 

Exercicio de condição:

   menor < 12 => criança
   12 anos e 17 anos => adolescente
   maior/igual >= a 18 => adulto

```kotlin
val idade : Int = 14

val result : Boolean = idade < 12
printIn(result)

if(result){
printIn("Faixa etaria Criança")
}else{
printIn("Faixa etaria de Adolescente")

}

```

Código mais limpo:

val idade: Int = 14

if(idade < 12){
printIn("Faixa etaria Criança")
}else if(idade >= 12 && idade <= 17) {
printIn("Faixa etaria de Adolescente")
}else if(idade >= 18){
printIn("Faixa etaria Adulto")
}