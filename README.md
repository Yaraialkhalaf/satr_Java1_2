import java.util.Arrays;

public class App {

   public static void main(String[] args) {
    
      String[] names = {"Yara", "ali", "ibrahim"};
      double[] grades = {99.9, 98, 95.6};
      
      System.out.println(Arrays.toString(names)); 
      System.out.println(Arrays.toString(grades));
      
      
      displayStudentAverageGrades(grades);
      displayStudentNamesAndGrades(names, grades);
   }

   public static void displayStudentNamesAndGrades(String[] names, double[] grades) {
      System.out.println();
   }


   public static void displayStudentAverageGrades(double[] grades) {
      double sum = 0;
      
      for (double g : grades) {
        sum += g;
    }

      double average = sum / grades.length;
      System.out.println("The average is: " + average);
   }
}
    
