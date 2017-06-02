# OnlineATG
practice
package wrappers;

public class TestLeafWrappers extends GenericWrappers  {
	
	 public void login() throws Exception{
		 invokeApp("chrome" , "http://Flipkart.com/control/main");
		 enterById("username" , "DemoSalesManager");
		 enterById("password" , "crmsfa");
		 clickByClassName ("decorativeSubmit");
	 }

sysout("This is just trial ");
}
