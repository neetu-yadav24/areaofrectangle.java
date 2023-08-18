package student;

public class area {
	area(int l,int b)
	{
		int Ar;
		Ar=l*b;
		System.out.println("area of rectangle="+Ar);
	}
	area(int s)
	{
		int Ar;
		Ar=s*s;
		System.out.println("area of square="+Ar);
	}
	area(double r)
	{
		double Ar;
		Ar=3.14*r*r;
		System.out.println("area of circle="+Ar);
	}

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		area a1=new area(8);
		area a2=new area(7.2);
		area a3=new area(3,4);

	}

}
