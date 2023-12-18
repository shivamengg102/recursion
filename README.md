# recursion
 
 /**
 * basic
 */
public class basic {
    public static void printMemory(int n ){
        if(n==10){
          return;
        }
        System.out.println(n);
        printMemory(n+1);
    }

    public static void main(String[] args) {
        int n = 1;
        printMemory(n);
    }
}
