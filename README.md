data class Direccion(
val departamento: String,
val municipio: String,
val distrito: String,
val complemento: String
)
    
data class Estudiante(
val id: Int,
val nombre: String,
val carrera: String,
val materia: String,
val edad: Int,
val direccion: Direccion  
    )
    fun main (){
        //codigo aca
        val student = Estudiante(
        1, "melvin", "software", "zacatecoluca", "itca")
    }
    
   // val producto1 = Producto("Manzana", 30, "el arbol", null , "2025/10/20", 0.75)
   // val producto2 = Producto("Mango", 10, "el arbol", null , "2025/10/30", 1.25, )
   // val producto3 = Producto("Melocoton", 40, "el arbol", null , "2025/10/15", 2.00, )
    //val producto4 = producto3.copy(precio = 0.25, nombre = "pera")
   
   val listProducts = listOf()
   //  producto1 = Producto("Manzana", 30, "el arbol", null , "2025/10/20", 0.75)
   //  producto2 = Producto("Mango", 10, "el arbol", null , "2025/10/30", 1.25, )
   // producto3 = Producto("Melocoton", 40, "el arbol", null , "2025/10/15", 2.00, )
    //producto4 = producto3.copy(precio = 0.25, nombre = "pera")
   
    
   // println(producto3)

    
}
