import java.util.Scanner;

public class Program {

    public static void main(String args[]) {

        Test human = new Test("Albert", 55);
        human.show();
    }
}
       class Test {
           String name;
           int age;

             Test(String name){
                this.name = name;
             }

             Test(String name, int age){
                 this.name = name;
                 this.age = age;
             }

             void show (){
                 System.out.println("Name: " + name + "\nAge: " + age);
             }
        }


