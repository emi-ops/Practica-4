# Practica-4
POO
public class EVA1_3_MODIFICADORES {

    public static void main(String[] args) {
     //instanciar un ejemplo
     //clase identificador = new contructor (parametros)
      Persona perso = new Persona();
       perso.setNombre("Angel Emiliano ");
        System.out.println("Nombre: " + perso.getNombre());
        
        perso.setApellidos("Herrera Rascón ");
        System.out.println("Apellido: " + perso.getApellidos());
        
        perso.setEdad(19);
        System.out.println("Edad: " + perso.getEdad());
        
        perso.setGenero("Hombre");
        System.out.println("Genero: " + perso.getGenero());
        
        perso.setCurp("LPGA5");
        System.out.println("Curp: " + perso.getCurp());
    }
}
public class Persona {
    //ATRIBUTOS
   private String nombre;
   private String apellidos;
   private int edad;
   private String genero;
   private String curp;
    //String setnombre;
   //CONSTRUCTURES
   //METODOS
   //metodos get y set
   public String  getNombre(){
       return nombre;
   }  
   public void setNombre(String Valor){
       nombre = Valor;
   }
  
   
   public String getApellidos(){
       return apellidos;
   }
   public void setApellidos(String valor){
       apellidos = valor;
   }
   
   
   public int getEdad(){
       return edad;
   }
   public void setEdad(int valor){
       edad = valor;
   }
   
   
   public String getGenero(){
       return genero;
   } 
   public void setGenero(String valor){
       genero = valor;
   }
   
   
   public String getCurp(){
       return curp;
   }
   
   public void setCurp(String valor){
       curp = valor;
   }
   
 }
