data class Usuario (val nome:String, val email:String, val cursos:String, var nivel:String, var duracao:Int)
    

    data class Formacao(val nome: String) {
         val inscritos = mutableListOf<Usuario>()

        fun matricular(usuario: Usuario) {
        inscritos.add(usuario)
        println("${usuario.nome} esta matriculado no Curso : ${usuario.cursos}, com o ${usuario.email}, no Nivel ${usuario.nivel} e com Duração de: ${usuario.duracao} horas)}")
        
        
        
    }
     }
    
  
     fun main(){
     val usuario1 = Usuario("João",  "email:joao@dio.me", "Bootcamp Frontend com Angular" , "Basico" , 30 )
     val usuario2 = Usuario("Maria", "email:maria@dio.me", "Bootcamp Backend com Java", "Basico" , 40)
     val usuario3 = Usuario("Pedro", "email:pedro@dio.me", "Bootcamp Mobile/Backend com Kotlin", "Intermediario" , 60)
     val usuario4 = Usuario("Paulo", "email:paulo@dio.me", "Bootcamp Full stack com .Net e C#", "Avancado",  85)
     
     
     val formacao1 = Formacao("Concluido")
     val formacao2 = Formacao("Concluido")
     val formacao3 = Formacao("Concluido")
     val formacao4 = Formacao("Concluido")
   
     
    formacao2.matricular(usuario1)
    formacao4.matricular(usuario2)
    formacao1.matricular(usuario3)
    formacao1.matricular(usuario4) 
    
    

    }
