public class HargaBarang
{
	public static void main (String [] Args)

	{
		int jumbrg=40;
		int totbonus= jumbrg/2;
		int totbarang=jumbrg+totbonus;
		int harga=25000;
		int bayar=jumbrg*harga;

		System.out.println("beli 2 gratis 1");
		System.out.println("jumlah barang\t: "+jumbrg+" barang");
		System.out.println("pembayaran\t:  Rp |"+bayar);
		System.out.println("total bonus\t:"+totbonus+" barang");
		System.out.println("total barang\t:"+totbarang+" barang");

	}
}
