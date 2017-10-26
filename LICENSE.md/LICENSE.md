package hafta7_1;

public class algo7_2 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		double ilkucret = 10000;
		double ucret=ilkucret;
		int sene=0;
		while(ucret <= ilkucret*2)
		{
			ucret= ucret *1.07;
			sene++;
		}
		System.out.println(sene+ "sonra iki katına çıkıcak");

	}

}
