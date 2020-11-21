### Hello, I'm Alvin 👋

```kotlin
import kotlin.io.*

class MobileDeveloper {
  val name = "Alvin"
  var codes = listOf("kotlin","swift","java","c#")
  
  fun present(){
     println("Hello there! I'm $name 👋")
  }
  
  fun superThink(language: String?): String{
      var myAnswer : String
      val result = codes.contains(language)
      if(result){
          myAnswer = "$language, I know that too! So cool!"
      }else{
          myAnswer = "$language, Wow I don't know that. Teach me!"
      }
      return myAnswer
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
<!--
**blackchalk/blackchalk** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

- 📫 How to reach me: [Send me an email message!](mailto:alvinraygon@yahoo.com?subject=[GitHub]%20Someone%20is%20trying%20to%20reach%20out!)
Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
