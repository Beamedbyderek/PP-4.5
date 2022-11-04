# PP-4.5

public class Car {
  //private fields
private string _model;
private string _make
private int _year;
Scanner scan = new Scanner(System.in);

//constructor
public Car(String make, String model, int year) 
{
  _model = model;
  _make = make;
  setYear(year);
}

public String getModel() { return _model; }
public String getMake() { return _model; }
public int getYear () { return _year; }

public void setModel( String model) {_model = model;}
public void setMake( String make) {_make = make;}
public void setYear (int year)
{
    while (year < 1900)
   }
   public String toString()
   {
      return _make + " " +_model + " " + Integer.toString(_year);
     }
 }
 
 /////
 
 import Java.util.Scanner;
 
public class carTest {

  public static void main(String[] args) {
    String model; make;
    int year = 0;
    Scanner scan = Scanner(System.in);
    
    // empty
    Car car = new Car(" ", " ", 0);
    {
      System.out.prinln( Enter make,model.year");
      make = scan.next();
      model = scan.next();
      year = scan.next();
      
      Car car = new Car (make,model,year);
      Scan.next.Line();
      
      System.out.println( "Here is your car" + car);
      
      }
 }
      
 
 
    
