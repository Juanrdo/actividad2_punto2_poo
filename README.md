# actividad2_punto2_poo
package trianguloequilatero;
import java.util.Scanner;
public class Trianguloequilatero {

    public static void main(String[] args) {
        double  lado,perimetro,altura,area;
        Scanner ingreso = new Scanner (System.in);
        
        System.out.println("Ingrese el lado del triangulo equilatero:  ");
        lado = ingreso.nextDouble();
        
        perimetro= 3*lado;
        altura= ((Math.sqrt(3))*lado)/2;
        area=(lado*altura)/2;
        
        System.out.println("el perimetro es :  "+ perimetro);
        System.out.println("la altura es :  "+ altura);
        System.out.println("el area es: "+ area);
        
        
    }
    
}
