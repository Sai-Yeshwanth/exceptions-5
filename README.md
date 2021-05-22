class Do{
	public void findException(){
       int i=2;
       int j=0;
       int k;
       try{
    	   k=i/j;
       }
       catch(ArithmeticException ae)
       {
    	   System.out.println("Number cant be divided by zero " );
       }
    }
}
class Jala {
	public static void main(String[] args){
		Do d = new Do();
        d.findException();
	}
}
