# poo4
1.  Sobrecarga de Métodos
Implementación de métodos con el mismo nombre pero diferentes parámetros, demostrando la capacidad de Java para realizar sobrecarga.

public class Calculadora {
    public int sumar(int a, int b) {
        return a + b;
    }
    public double sumar(double a, double b) {
        return a + b;
    }
    public int sumar(int a, int b, int c) {
        return a + b + c;
    }
}
