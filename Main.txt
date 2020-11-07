public class Main {
    public static void main (String[] args) {
        int ticket = 25000;
        int bonus = 20;
        int result = ticket / bonus;
        int score = 0;
        if (result >= 1) {
            score = result;
        }
        System.out.println (score);
    }
}