# testone
package packone;

import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

public class test_one {

public static void main(String[] args) {
	
   System.out.println("Hello SR");
		 
   System.setProperty("webdriver.chrome.driver","C:\\Users\\lenovo\\Downloads\\Surbhi\\SELENIUM\\chromedriver_win32\\chromedriver.exe");
   WebDriver driver=new ChromeDriver();
   
   driver.get("https://www.google.com/");

   System.setProperty("webdriver.gecko.driver","");	 
   
   
	
	}
}
