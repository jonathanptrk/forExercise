# forExercise
Crie um contador de 1 a 10000 que conte apenas os números ímpares.


package aula03.estruturasDeRepeticao;
public class forFor {
    public static void main(String[] args) {

        // Crie um contador de 1 a 10000 que conte apenas os números ímpares.

        for (int i = 0; i <= 10000; i++) {
            if (i % 2 != 0){
            System.out.println(i);
            }
        }
    }
}

