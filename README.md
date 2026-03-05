public class Factorial {
        public static void main(String[] args) {
        int numero = 8;
        System.out.println("Factorial de " + numero + " es: " + calcularFactorial(numero));
    }
    
    public static long calcularFactorial(int n) {
        long factorial = 1;
        for (int i = 2; i <= n; i++) {
            factorial *= i;
        }
        return factorial;
    }
}

