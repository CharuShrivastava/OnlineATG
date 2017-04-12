# OnlineATG
practice
public class DataClass {
	
	@DataProvider(name="Anjali")
	
	public static Object[][] dprovider(){
		
		Object[][] data =new Object[2][3];
		data [0][0] ="first company name " ; data [0][1] =" first name " ;	data [0][2] ="last name " ;	
		data [1][0] ="Second company name" ; data [1][1] ="first name " ;	data [1][2] =" lost name" ;	
				
		return data;
		
	}

}
