# -to-convert-minutes-into-years-and-days
impart java.util.Scanner;
Public class Convert{
Public static void main(String[]Strings){
double minutes InYear=60*24*365;
Scanner input=new Scanner(System.in);
System.out.println("input the number of minutes:");
double min=input.next Double();
long years=(long)(min/minutesInYear);
int days=(int)(min/60/24)%365;
system.out.println((int)min+"minutes is approximately"+years+"years and"+days+"days");
}
}
