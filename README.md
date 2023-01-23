##  10D Challenge

### 📑Explicação

**Desafio 10D Challenge** 
o Desafio 10D Challenge foi criado para a comunidade do DevSpace, que contém varios desafios para a área de programação.
o Intuito do curso e focado para Apps Mobile, Lógica de Programação, Algoritmos e entre outros.

<br>
<br>

## 🤝 Organização

Comunidade :

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="https://user-images.githubusercontent.com/97356148/213753621-a9a01471-dc50-4657-9919-2667b76fc785.png" width="100px;" alt="Foto Devspace comunidade"/><br>
        <sub>
          <b>DevSpace</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

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