# Find-the-this-year-is-leap-year-or-not.-
public class how_to_use_user_input {
    public static void main(String[] args) {

        java.util.Scanner sc = new java.util.Scanner(System.in);
        System.out.println(" Enter your year which is what you want to check");
        int year = sc.nextInt();
        if  (year%4==0) {
            System.out.println(" This year is LeapYear");
        }else if  (year%100==0) {
            System.out.println(" This year is LeapYear");
        }else if  (year%400==0) {
            System.out.println(" This year is LeapYear");
        }

        else{
            System.out.println(" This year is not LeapYear");
        }


    }
}
