# Grade-Point-Average-Calculator

// import java.util.Scanner;

public class test
{ public static void main(String[] args) {

  // Değişkenleri oluştur
  int mat,fizik,kimya,turkce,tarih,muzik;
  
  
 // Scanner sınıfımızı tanımladık
    Scanner inp = new Scanner(System.in);

   // Kullanıcıdan değerleri al
    
 System.out.println("Matematik Notunuz :");
    
mat = inp.nextInt();

    
 System.out.println("Fizik Notunuz :");
 
 fizik = inp.nextInt();
  
 System.out.println("Tarih Notunuz :");

tarih = inp.nextInt();
  
 System.out.println("Kimya Notunuz :");
  
  kimya = inp.nextInt();


System.out.println("Türkçe Notunuz :");
    
    turkce = inp.nextInt();

   
   System.out.println("Müzik Notunuz :");
   
   muzik = inp.nextInt();

  
  double toplam = (mat + fizik + tarih +turkce+ muzik +kimya);
    
   double sonuc = toplam / 6;
  
  System.out.println("Not ortalama sonucunuz : " + sonuc );
    


    }
}
