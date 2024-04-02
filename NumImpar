/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package sistemasoperativos;

import javax.swing.JOptionPane;

/**
 *
 * @author yalidominguez
 */
public class NumerosImpares {
    int num[] = new int[10];
    int i;
    String result = "";
    String resultpares = "";

    public void IngresarNumeros() {
        for (i = 0; i < num.length; i++) {
            do {
                num[i] = Integer.parseInt(JOptionPane.showInputDialog("Digita numeros del 1 al 10"));
            }while (!Error(num));
        }
    }

    public boolean Error(int num[]) {
        boolean rango;
        if (num[i] >= 1 && num[i] < 11) {
            rango = true;
        } else {
            rango = false;
        }
        return rango;
    }

    public void Resultados() {
        for (i = 0; i < num.length; i++) {
            result = result + num[i];
            result += "\n";
        }
        JOptionPane.showMessageDialog(null, result, "Números introducidos", JOptionPane.INFORMATION_MESSAGE);
    }

    public int NumeroINPar() {
        for (i = 0; i < num.length; i++) {
            if (num[i] % 3 == 0) {
                resultpares = resultpares + num[i];
                resultpares += "\n";
            }
        }
        JOptionPane.showMessageDialog(null, resultpares, "Numeros Inpares", JOptionPane.INFORMATION_MESSAGE);
        return num[i];
    }

    public static void main(String[] args) {
        NumerosImpares np = new NumerosImpares();
        np.IngresarNumeros();
        np.Resultados();
        np.NumeroINPar();
        np.Error(np.num);
    }
}
