# PP-4.5

/* 

11/7/2022

 Derek Durand

Out puts car and if antique 

*/ 
import java.util.Scanner;


public class Car {
            //private fields

            private String _model;
            private String _make;
            private int _year;
            Scanner scan = new Scanner(System.in);

        //constructor
            public Car(String make, String model, int year) {
                _model = model;
                _make = make;
                setYear(year);

                 _year = year;
         }

            public String getModel() {
                return _model;
         }
 
            public String getMake() {          //Strings for my code
                return _model;
         }

            public int getYear() {
                return _year;
         }

            public void setModel(String model) {
                _model = model;
         }

            public void setMake(String make) {
                _make = make;
         }

            public void setYear(int year) {
                while (year < 1900) {

                  }
         }


            public String toString() {                  //to string
                return _make + " " + _model + " " + Integer.toString(_year);
    }
}

 
 /////
 
/* 

11/7/2022

 Derek Durand

Out puts car and if antique 

*/ 
import java.util.Scanner;
 
public class carTest {

  public static void main(String[] args) {
    String model, make;
    int  year = 0 ;
    Scanner scan = new Scanner(System.in);
    
     
    
    {
      System.out.println( "Enter make,model,year");
      make = scan.next();
      model = scan.next();       //scanners
      year = scan.nextInt();
      
      Car car = new Car (make, model, year);         //formatting
      scan.nextLine();
      
      System.out.println( "Here is your car " + car);
      
      if (year < 1977)          //this reads if code is antique or not
      {
                   System.out.println("Your car is antique");
         }
    }
}

}
      
 
 
    
