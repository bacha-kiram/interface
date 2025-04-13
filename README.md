# interface
interface.java
interface Animal {
    void makeSound();
    void eat();
}

class Cat implements Animal {
    public void makeSound() {
        System.out.println("Meow");
    }

    public void eat() {
        System.out.println("Cat eats fish");
    }
}

public class Main {
    public static void main(String[] args) {
        Cat c = new Cat();
        c.makeSound();  
        c.eat();        
    }
}
