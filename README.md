class Main { 
    
    public static void main(String [] args) { 
        java.util.Scanner myscanner = new java.util.Scanner(System.in);
        System.out.println("Введите первое слагаемое");
        int value1 = myscanner.nextInt();
      
        System.out.println("Введете второе слагаемое");
        int value2 = myscanner.nextInt();
      
        int result = sumMethod(value1,value2);
        System.out.println("Результат сложения " + result );
    
    }
  
    static int sumMethod(int value1,int value2) { 
        return value1 + value2 ;
  }
}
