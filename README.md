# SampleGit
import java.io.* ;
class Tut1 {
     public static void main(String args[])
     {
               InputStreamReader istream = new InputStreamReader(System.in) ;
               BufferedReader bufRead = new BufferedReader(istream) ;
               
               System.out.println("Welcome To My First Java Program");
           {
               System.out.println("Please Enter In Your First Name: ");
               String firstName = bufRead.readLine();
               System.out.println("Please Enter In The Year You Were Born: ");
               String bornYear = bufRead.readLine();
               System.out.println("Please Enter In The Current Year: ");
               String thisYear = bufRead.readLine();
               
               int age = tYear – bYear ;
               System.out.println(“Hello “ + firstName + ". You are " + age + " years old");
          }
          (IOException err) {
               System.out.println("Error reading line");
          }
     }	
}
