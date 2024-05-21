
public class matriz1010 {

	public static void main(String[] args) {
		int matriz[][] = new int[10][10];
		matrizgen(matriz);
		verify(matriz);
		
	}
public static int[][] matrizgen(int v[][]) {
	int i,j;
	for (i=0; i < v.length;i++) {
		for (j =0; j< v[i].length;j++) {
			  v[i][j] = i * 2;	
		}
	}
	return v;
	}

	public static void verify(int v[][]) {
		int i, j;
		for (i = 0; i < v.length; i++) {
			for (j = 0; j < v[i].length; j++) {
				if (i == j) {
					  v[i][j] = i * 4;	
					System.out.print(v[i][j] + " ");
				}
			}
			System.out.println();
		}
		System.out.println("");
		System.out.println("elementos presentes na diagonal principal.");
	}
}
