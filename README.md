package OOPS_USING_JAVA;

public class calsi {
	int sum(int a,int b) {
		 return a+b;
		 }
     
	int sub(int a,int b) {
		return a-b;
	}
	int div(int a,int b) {
		return a/b;
	}	
	int mul(int a,int b) {
		return a*b;
	}
	
	

	public static void main(String[] arg){
		calsi cal=new calsi();
		System.out.println(cal.sum(10,5));
		System.out.println(cal.sub(10,5));
		System.out.println(cal.mul(10,5));
		System.out.println(cal.div(10,5));
	
	}	}	
