import java.util.Scanner;
public class ReadSeconds {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int second;
        int minutes;
        int hours;
        System.out.print("Enter the number of seconds : ");
        second = input.nextInt();

        while (second != 0) {

            hours = second / 3600;
            {
                if (hours > 24) {
                    System.out.println("This value is too big!");
                    return;
                }
                minutes = (second % 3600) / 60;
                int temp = (second % 3600) % 60;
                if (temp > 1) {
                    System.out.println("The time entered in hours,minutes and seconds is:");
                    System.out.println(hours + " hours, " + minutes + " minutes, " + temp + " seconds");
                } else {
                    System.out.println("The time entered in hours,minutes and seconds is:");
                    System.out.println(hours + " hours, " + minutes + " minutes, " + temp + " second");
                }
            }
            second = input.nextInt();
        }
    }
}
