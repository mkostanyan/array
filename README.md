# array
Actions with arrays
public class Array {
    public static void main(String args[]) {
        int[] a = {2, 5, 7, 3, 9, 1, 8};
        for (int i : a) {
            System.out.print(i + ", ");
        }
        System.out.println();
     int min = a[0];
     int minIndex = 0;
     int max = a[0];
     int maxIndex = 0;
     for (int i = 1; i < a.length; i++) {
         if (a[i] < min) {
              min = a[i];
              minIndex = i;
         }
      }
     for (int i = 1; i < a.length; i++){
          if (a[i] > max){
              max = a[i];
              maxIndex = i;
          }
     }
    System.out.println("From a minimum is " + min);
    System.out.println("Form a minimum index is " + minIndex);
    System.out.println("From a maximum is " + max);
    System.out.println("Form a maximum index is " + maxIndex);
    
