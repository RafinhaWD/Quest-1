import java.util.HashMap;
import java.util.Map;

public class Main {
    public static void main(String[] args) {
        int[] numeros = {5, 3, 4, 3, 5, 5, 3};
        System.out.println("Número não repetido: " + encontrarNumeroNaoRepetido(numeros));
    }
    
    public static int encontrarNumeroNaoRepetido(int[] numeros) {
	     Map<Integer, Integer> mapa = new HashMap<>();
     
			for (int num : numeros) {
            mapa.put(num, mapa.getOrDefault(num, 0) + 1);
        }
       
        for (int num : numeros) {
            if (mapa.get(num) != 3) {
                return num;
            }
        }
        return -1;
    }
}



