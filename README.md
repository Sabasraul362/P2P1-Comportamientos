public abstract class Comportamientos implements ComportamientoAnimal{
   protected String color;
   protected String especie;

//  public abstract void setColor();

  // public abstract void setColor(String color);

   //public abstract void setEspecie();

   //public abstract void setEspecie(String especie);

   public Comportamientos(){

   }
   public Comportamientos(String color){
       this.color = color;
   }

   @Overide
   Public String getColor(){
       renturn color;
   }
   @Overide
   Public void setColor(String color){
       this.color = color;
   }

   @Overide
   Public void getEspecie(){
       return especie;
   }

   @Overide
   Public void setEspecie(String especie){
       this.especie = especie;
   }
}
