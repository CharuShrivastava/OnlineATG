# OnlineATG
practice
package wrappers;

public class TestLeafWrappers extends GenericWrappers  {
	
	 public void login() throws Exception{
		 invokeApp("chrome" , "http://leaftaps.com/control/main");
		 enterById("username" , "DemoSalesManager");
		 enterById("password" , "crmsfa");
		 clickByClassName ("decorativeSubmit");
	 }

}
