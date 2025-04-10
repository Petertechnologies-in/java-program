public class tech_nos
{
    public static void main(String args[])
{
 for(int i=1000;i<=9999;i++){
int firsthalf=i/100;// to extract first two digits
int secondhalf=i%100;// to extract third fourth digits
int total=firsthalf+secondhalf;// add it 
int square=total*total;//square it
if(square==i) System.out.println("Tech No is: "+i);// check condtn and print result
 }}}
