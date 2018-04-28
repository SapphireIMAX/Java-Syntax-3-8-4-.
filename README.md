# Java-Syntax-3-8-4-.
public class Main {
    public static void main(String[] args) {
        System.out.println(getSecondsAfter15(12345));
    }

    public static int getSecondsAfter15(int secondsAfter12) {
        int secondsAfter15;
        secondsAfter15 = secondsAfter12 - (3*3600);
        return secondsAfter15;
    }
}
