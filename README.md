# indiceLiquidezGeral
A liquidez geral é um indicador utilizado para medir a capacidade que uma empresa tem de honrar com as suas obrigações de curto e longo prazo. A partir de um cenário de encerramento das atividades e liquidação de todos os bens, a liquidez geral é calculada.

```
public class liquidezGeral {
	public static void main(String[] args) {
			double ativoCirculante = 21190000;
			double realizavelLongoPrazo = 13500000;
			double passivoCirculante = 17503000;
			double exigivelLongoPrazo = 12500000;

			double liquidezGeral;

			liquidezGeral = (ativoCirculante + realizavelLongoPrazo) 
					/ (passivoCirculante + exigivelLongoPrazo);

			System.out.println("O índice calculado em liquidez Geral é?  " + 
					liquidezGeral);
	}

}
