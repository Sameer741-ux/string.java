import java.util.Scanner;
 class string {
public static void main(String[] args) {
    String s = new String();int len,i;
    Scanner sc = new Scanner(System.in);
    System.err.println("Enter String");
s=sc.next();
len=s.length();
System.out.println("Length Of String is"+len);
for (i=0;i<len;i++)
System.out.println(s.charAt(i));

    
}

}
