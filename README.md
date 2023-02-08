# polymorphismass
public class Main {
    // Task 1: create a class Product inside Main class
    static class Product {
        // Task 3: create a method of following defination public int product(int x, int y)
        public int product(int x, int y) {
            return x * y;
        }

        // Task 4: create a Overloaded method product of following defination public int product(int x, int y, int z)
        public int product(int x, int y, int z) {
            return x * y * z;
        }

        // Task 5: create a Overloaded method product of following defination public double product(double x, double y)
        public double product(double x, double y) {
            return x * y;
        }
    }

    public static void main(String[] args) {
        // Task 2: create object of Product in Main function called p
        Product p = new Product();

        // Task 3: call this method from Main using Product class object p
        System.out.println(p.product(2, 3));  // Output: 6

        // Task 4: call this method also from Main using Product class object p
        System.out.println(p.product(2, 3, 4));  // Output: 24

        // Task 5: call this method also from Main using Product class object p
        System.out.println(p.product(2.0, 3.0));  // Output: 6.0
    }
}
