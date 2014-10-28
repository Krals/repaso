repaso
======
public class Curso {
 private String nombre; 

    @Override
    public String toString() {
        return "Curso{" + "nombre=" + nombre + ", cuatrimestre=" + cuatrimestre + ", profesor=" + profesor + '}';
    }
    private int cuatrimestre; 
     private String profesor; 
 
 
   public Curso() { 
     }  
 
   public Curso(String nombre, int cuatrimestre) { 
         this.nombre = nombre; 
         this.cuatrimestre = cuatrimestre; 
     } 
 
 
    public Curso(int cuatrimestre, String profesor) { 
         this.cuatrimestre = cuatrimestre; 
         this.profesor = profesor; 
     } 
 
 
     public String getProfesor() { 
         return profesor; 
     } 
 
 
     public void setProfesor(String profesor) { 
         this.profesor = profesor; 
     } 
 
 
     public String getNombre() { 
         return nombre; 
    } 
 
     public void setNombre(String nombre) { 
         this.nombre = nombre; 
    } 
 
 
    public int getCuatrimestre() { 
         return cuatrimestre; 
     }  
 
    public void setCuatrimestre(int cuatrimestre) { 
         this.cuatrimestre = cuatrimestre; 
     } 

   
    
    
}
