### Hello, I'm Alvin 👋
![](https://github-profile-trophy.vercel.app/?username=blackchalk)

```kotlin
import kotlin.io.*

class MobileDeveloper {
  val name = "Alvin"
  var codes = listOf("kotlin","swift","java","c#")
  
  fun present(){
     println("Hello there! I'm $name 👋")
  }
  
  fun superThink(language: String?): String{
    val result = codes.contains(language)
    return if(result) "$language, I know that too! So cool!" else "$language, Wow I don't know that. Teach me!"
  }
}

fun main(args: Array<String>) {
    
    val me = MobileDeveloper()
    me.present()
    println("Let's play a game!")
    println("Name a language you know for building mobile apps or games! Go!")
    val yours = readLine()
    println(me.superThink(yours))
    
}
    
```
Try it with [Kotlin Online Compiler!](https://repl.it/languages/kotlin)
powered by [@replit](https://twitter.com/replit)
<!--
**blackchalk/blackchalk** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
