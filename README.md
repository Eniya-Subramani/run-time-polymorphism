# run-time-polymorphism
package runtimepolymorphism1;
class vechile{
    public void display(){
        System.out.println("vechie types");
    }
}
class car extends vechile{
    public void display(){
        System.out.println("car starts");
    }
}
class bike extends vechile{
    public void display(){
        System.out.println("bike starts");
    }
}
public class Runtimepolymorphism1 {
 public static void main(String[] args) {
        vechile vechile1=new car();
        vechile1.display();
        vechile vechile2=new bike();
        vechile2.display();
    }
    
}
output:
car starts
bike starts
