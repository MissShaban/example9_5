# example9_5
import java.util.Date;
import java.text.*;
public class Example5_9 {
public static void main(String[] args) { 
Date now = new Date();
DateFormat formatter = DateFormat .getDateInstance();   System.out.println("Default date :" + formatter. format (now) ) ; 
formatter = DateFormat. getDatelnstance(DateFormat.SHORT, java.util.Locale.UK);  System.out.println(”Short (UK):“+formatter.format(now)); formatter = DateFormat.getDatelnstance (DateFormat.MEDIUM) ;  System.out.println("Medium:" + formatter.format (now)); 
formatter = DateFormat.getDatelInstance(DateFormat,LONG);  
System.out.println("Long:” + formatter.format(now)); 
formatter = DateFormat.getDateInstance (DateFormat.FULL); System.out.println("Full:" + formatter.format(now));
}
}
