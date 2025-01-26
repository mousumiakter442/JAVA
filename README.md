
interface Vehicle {
    void start(); // Abstract method
}

class Car implements Vehicle {
    public void start() {
        System.out.println("Car starts with a key.");
    }
}

public class Main {
    public static void main(String[] args) {
        Vehicle myCar = new Car();
        myCar.start(); // Output: Car starts with a key.
    }
}
