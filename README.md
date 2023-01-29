# DZ2
Displayed the result of the calculation
    public DZ2 {
    }

    public static void main(String[] args) {
        int longWallWidth = 6;
        int longWallHeight = 3;
        int shortWallWidth = 4;
        int ShortWallHeight = 3;
        int resultlongWallArea = longWallWidth * longWallHeight;
        System.out.println("" + longWallWidth + " * " + longWallHeight + " = " + resultlongWallArea);
        int resultshortWallArea = shortWallWidth * ShortWallHeight;
        System.out.println("" + shortWallWidth + " * " + ShortWallHeight + " = " + resultshortWallArea);
        int resultroomArea = resultlongWallArea + resultshortWallArea * 2;
        System.out.println("" + resultlongWallArea + " + " + resultshortWallArea + " * 2 = " + resultroomArea);
    }
}
