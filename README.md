import static have  Lang  character*;
 public class Example{
 public static void main(string[]args
 {
 system  out  println("Upprcasa('a') ="+
 system  outprintln("isLettrr('a') ="+
 isLetter('a'); 
 system  out print("isLetter('*')="+
 isLetter('*');
 system out println("isUppercase('b') =";
 isUppercase('b'); 
 system out print("isspacechar('')="+
 isspaceChar(''));
 }
 }

 impor java utilDate; 
 import java text*;
 public class Examples{
 public static void main(string[]args) 
 {
 Datenow=newDate();
 Dateformat formatter=Dateform  getDateInstance();
 system  outprintln("Default date:"+
 for matter  format(now); 
 for matter=Datfirmat  getDatelnstance(Dateformat  SHORT, 
 java  until  Locale  Uk); 
 system  out println("short(Uk):"formatter  format(now));
 formatter=DateFormat  getDateInstance(Dateformat  MEDIUM)
 system  out println("Medium:"+formatter  format(now)); 
 formatter=Dateformat  getDateInstance(dateformat  LONG); 
 system out  println("long:"+formatter  .format(now)); 
 formatter=Dateformat  getDateInstance(Datfirmat  fULL); 
 system out println(full:"+formatter  format(now)); 
 }
 }

 public class Example
 {
 public static void main(string[]args
 {
 intx, y; 
 lnteqernum1,num2;
 num1=8;  //Autobox8
 num2=16;  //Autobox16
 system  out print("num1="+num1+",num2="+num2);
 x=2*num1+num2://auto-unboxing
 y=num1+num2;  //auto-unboxing
 system  out println("x=+x+",y="+y); 
 string s=new string("12");
 x=lnteger  parselnt(s); 
 s=+num1.toString()+num2.tostring();
 system  out println("convert int to string and concate:"+s); 
 }
 }

  public classExample
  {
   public ststic void main(string()args) 
   {
    stringBuffer str=new stringBuffer("Hello")
    system  out println("strbefore calling the method:"+str); 
    }
    //**********
     public static void testMethod(stringBuffer pstr) 
     {
     system  out println("ln method:pstr"+
      before changing it's value:"+ pstr); 
       pstr  happened("sunnyDay");
       system out println ("ln method: pstr"+
       after changing it's value:"+ pstr); 
       }
       }
 
