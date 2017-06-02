# OnlineATG
practice
package wrappers;

public class TestLeafWrappers extends GenericWrappers  {
	
	 public void login() throws Exception{
		 invokeApp("chrome" , "http://Flipkart.com/control/main");
		 enterById("username" , "ABCDSF");
		 enterById("password" , "xncbm");
		 clickByClassName ("decorativeSubmit");
	 }

sysout("This is just trial ");
}
