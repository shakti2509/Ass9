# Ass9
Ass9
package Ass9;

public class Point {

	private int x, y;
	private int a,b;
	public Point()
	{
	x=y=0;
	a=b=1;
	}
	public Point(int x,int y,int a,int b)
	{
		this.a=a;
		this.b=b;
		this.x=x;
		this.y=y;
		
	}
	public void display()
	{

		System.out.println("Starting pointi is "+x+"  "+y);
		System.out.println("ending  pointi is "+a+"  "+b);
	}
}
package Ass9;

public class Demopoint {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Point p=new Point();
		p.display();
		Point p1=new Point(1,2,3,4);
		p1.display();
	}

}
