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

fun main() {
    val student = Estudiante(
        1,
        "Melvin",
        "Software",
        "Movil",
        18,
        Direccion("La Paz", "Zacatecoluca", "ITCA", "Frente al parque")
    )

    println(student)
}
