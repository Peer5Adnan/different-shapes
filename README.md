# different-shapes
public class paramid {
    public static void main(String args[]) {
        int n;
        n = 5;
        for (int i = 0; i < n; i++) {
            System.out.print("*  ");
        }
        System.out.print("\n");
        System.out.println("new pattern of stars");

        for (int j = 0; j < n; j++) {
            System.out.println("\n");
            for (int m = 0; m < n; m++) {
                System.out.print("*  ");

            }
            for (int k = 0; k < n; k++) {
                System.out.println(" ");
                for (int y = 0; y < k; y++) {
                    System.out.print("  &");
                }
            }
            for (int t = 0; t < n; t++) {
                System.out.println("");
                for (int q = 0; q < t; q++) {
                    System.out.print(" ");
                }
            }
            for (int d = n; d >= 0; d--) {
                for (int r = 0; r <= d; r++) {
                    System.out.print("*");
                }
                System.out.println(" ");
            }
            for(int f=0;f<n;f++) {
                for (int c = 0; c < f; c++) ;
                {
                    System.out.print(" *");
                }
                for (int o = n; o >= 0; o--) {
                    System.out.print(" ");
                }
                System.out.println( "  ");
            }

        }
    }
}
