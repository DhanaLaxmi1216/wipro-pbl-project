import java.util.*;

public class Main {
    public static String secondWordUpper(String str) {
        String[] words = str.split(" ");
        
        if (words.length < 2)
            return "";

        return words[1].toUpperCase();
    }

    public static void main(String[] args) {
        System.out.println(secondWordUpper("hello good morning"));
    }
}
