public class Main {
    public static void main(String[] args) {

        int columns = 15; //set column width
        int rows = 7; // set row size
        int pivot = columns / 2; // we are finding the middle element for our space

        // top half
        for(int i=0 ; i<= rows ; i++){ // controls row
            for(int j = 0; j <= columns; j++){ // controls columns
                if(j > (pivot - i) && j <= (pivot + i)){ // if the character at j is between the pivot minus the i-th row make it a space
                    System.out.print(" ");
                } else System.out.print('*');
            }   // end inner loop
            System.out.println(); // next line
        } // end outer loop

        // bottom half
        for(int i = rows-1; i >= 0; i--){
            for(int j = columns; j >= 0; j--){
                if(j > (pivot - i) && j <= (pivot + i)){
                    System.out.print(" ");
                } else System.out.print('*');
            } // end inner loop
            System.out.println();
        }
    }
