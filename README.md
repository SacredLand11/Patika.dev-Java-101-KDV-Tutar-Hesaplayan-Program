# Patika.dev-Java-101-KDV-Tutar-Hesaplayan-Program
Java ile kullanıcıdan alınan para değerinin KDV'li fiyatını ve KDV tutarını hesaplayıp ekrana bastıran programı yazın.

## Code
public class Giris
{
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        double price = s.nextDouble();
        double KDV = price*.18;
        double totalPrice = price + KDV;
        System.out.println(totalPrice);
    }
}
