public class App {
    public static String truncate(String text, int length) {
        // BEGIN (write your solution here)
        text = "\"Hexlet";
        length = 4;
        text = text.substring(0,length);
        // System.out.println(text + "...\"");
        return (App.truncate (text,length));
        
    }
}
