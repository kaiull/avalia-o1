import java.util.Scanner;

public class SistemaEscolar {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        double[] notas = new double[8];

        // Entrada das 8 notas
        for (int i = 0; i < 8; i++) {
            System.out.print("Digite a nota do " + (i + 1) + "º bimestre: ");
            notas[i] = sc.nextDouble();
        }

        // Cálculos das médias
        double semestre1 = (notas[0] + notas[1] + notas[2] + notas[3]) / 4;
        double semestre2 = (notas[4] + notas[5] + notas[6] + notas[7]) / 4;

        double mediaFinal = (semestre1 + semestre2) / 2;

        // Saída formatada
        System.out.println("\nRESULTADOS\n");

        System.out.println("1º Bimestre: " + notas[0]);
        System.out.println("2º Bimestre: " + notas[1]);
        System.out.println("3º Bimestre: " + notas[2]);
        System.out.println("4º Bimestre: " + notas[3]);
        System.out.println("1º Semestre: " + semestre1);
        System.out.println("----------------------------");

        System.out.println("5º Bimestre: " + notas[4]);
        System.out.println("6º Bimestre: " + notas[5]);
        System.out.println("7º Bimestre: " + notas[6]);
        System.out.println("8º Bimestre: " + notas[7]);
        System.out.println("2º Semestre: " + semestre2);
        System.out.println("----------------------------");

        System.out.println("Média Final: " + mediaFinal);

        sc.close();
    }
}
