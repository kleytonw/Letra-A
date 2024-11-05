import java.util.Scanner;


public class Main {
    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);
        int i;
        int soma = 0;

        String palavra;

        System.out.print("Digite uma palavra ");
        palavra = scanner.next();

        char[] arr = palavra.toCharArray();

        for( i =0; i < arr.length; i++ )
        {
            if( arr[i] == 'a' || arr[i] == 'A')
            {
                soma = soma + 1;
            }

        }

        if(soma != 0)
        {
            System.out.println("A palavra 'a' existe e elas está na palavra " + soma + " vezes");
        } else
        {
            System.out.println("Não exista a palavra 'a' na palavra!");
        }

    }
}
