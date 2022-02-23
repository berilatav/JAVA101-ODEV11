Hava Sıcaklığına Göre Etkinlik Önerme

Sıcaklık 5'dan küçük ise "Kayak" yapmayı öner.
Sıcaklık 5 ve 15 arasında ise "Sinema" etkinliğini öner.
Sıcaklık 15 ve 25 arasında ise "Piknik" etkinliğini öner.
Sıcaklık 25'ten büyük ise "Yüzme" etkinliğini öner.

import java.util.Scanner;

public class Odev11 {

    public static void main(String[] args) {

        int temperature;

        Scanner input = new Scanner(System.in);
        System.out.println("Enter the temperature value: ");
        temperature = input.nextInt();

        if(temperature < 5) {
            System.out.println("You can ski.");
        }
        else if(temperature ==15 ){
            System.out.println("You can go to the cinema and picnic.");
        }
        else if(temperature > 5 && temperature < 15){
            System.out.println("You can go to the cinema.");
        }
        else if(temperature > 15 && temperature < 25) {
            System.out.println("You can have a picnic.");
        }
        else {
            System.out.println("You can swim.");
        }

    }
}
