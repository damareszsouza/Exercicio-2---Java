# Exercicio-2---Java
# Coordenadas Cartesianas 

# Este exemplo declara uma classe (Circulo) e em seguida cria um objeto deste tipo em main e
# altera o conteúdo desta variável. Uma classe é parecida com um record de Pascal, a nossa representa
# um círculo com os atributos raio e x , y, que são coordenadas cartesianas. Note que este objeto não
# possui métodos ainda.

//Classe circulo, arquivo Circulo.Java 

public class Circulo {
 //so atributos entre as chaves
 public float raio; //atributo raio do circulo 
 public float x;
 //posicoes em coordenadas cartesianas
 public float y;
}

//Classe principal, Arquivo Principal.Java

public class Principal {
 public static void main(String args[]) {
 Circulo umcirc; //declaracao de uma variavel circulo no metodo main.
 umcirc = new Circulo(); //alocacao dessa variavel
 System.out.println("(" + umcirc.x + "," + umcirc.y + "," + umcirc.raio + ")");
 umcirc.x = umcirc.x + 17;
 System.out.println("(" + umcirc.x + "," + umcirc.y + "," + umcirc.raio + ")");
 }
}
