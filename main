// Inserimento e successivo ordinamento di un vettore - Michele Lupoli 
import java.io.*;  
public class OrdinamentoVettore {
	public static void main (String args[])
	{
		// Dichiarazione variabili
		final int n = 10;  			// Dichiarazione di una costante
		int i, j, x;
		int vettore[];
		vettore = new int[10];
		
		// Impostazione dello standard input
		InputStreamReader input = new InputStreamReader(System.in); 	
		BufferedReader tastiera = new BufferedReader(input);			
		
		// Inserimento elementi nel vettore
		for (i=0; i<n; i++)
		{
			try
				{
					System.out.print("Inserisci elemento n. " + i + ": ");
					String numeroLetto = tastiera.readLine();
					vettore[i] = Integer.valueOf(numeroLetto).intValue();
				}
			catch (Exception e)
			{
				System.out.println("Numero inserito non valido! ");
				return;
			}
		}
		
		// Output vettore
		System.out.println("Vettore: ");
		for (i=0; i<n; i++)
		{
			System.out.print("[" + vettore[i] + "]" + " ");
		}
		System.out.println("");
		
		// Calcolo vettore ordinato
		for (i=0; i<n; i++)
		{
			for (j=0; j<n; j++)
			{
				if (vettore[i] < vettore[j])
				{
					x = vettore[i];
					vettore[i] = vettore[j];
					vettore[j] = x;
				}
			}
		}
		
		// Output vettore ordinato
		System.out.println("Vettore ordinato: ");
		for (i=0; i<n; i++)
		{
			System.out.print("["+vettore[i]+"]"+" ");
		}
	}
}
