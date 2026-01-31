# 3D-Arrays-Java
3D Arrays Java
public class threeDarrays {
    public static void main(String[] args) {
        int[][][] matrix3D = {
            {
                {1, 2, 3},
                {4, 5, 6},
                {7, 8, 9}
            },
            {
                {10, 11, 12},
                {13, 14, 15},
                {16, 17, 18}
            },
            {
                {19, 20, 21},
                {22, 23, 24},
                {25, 25, 27}
           },
                };
                for(int i = 0; i < matrix3D.length; i++){// block
                    System.out.println("Block" + (i + 1) + ":");// rows
                    for(int j = 0; j < matrix3D[i].length; j++){
                        for(int k = 0; k < matrix3D[i][j].length; k++){// colunms
                            System.out.print(matrix3D[i][j][k] + " ");
                        }
                        System.out.println();
                    }
                    System.out.println("_____");
                }
    }
}
/*Block 1:
1 2 3
4 5 6
7 8 9
_____
Block 2:
10 11 12
13 14 15
16 17 18
_____
Block 3:
19 20 21
22 23 24
25 26 27
_____*/
