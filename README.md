# Multiplication-Table
Public class MultiplicationTable {
    Public static void main(String[] args) {
        int number = 5;
        System.out.println("Multiplication Table of " + number);
        for (int i = 1; i <= 10; i++) { 
            int result = number * i; 
            System.out.println(number + " x " + i + " = " + result);
        }
    }
}

OUTPUT:

Multiplication Table of 5
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50
