package stepDefinations;



import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;


import io.cucumber.java.en.Given;
import io.cucumber.java.en.Then;
import io.cucumber.java.en.When;

public class Orangehrm_stepDefination {
public WebDriver driver;


@Given("^user is on OrangeHrm landing page$")
   public void user_is_on_orangehrm_landing_page() throws Throwable {
	 System.setProperty("webdriver.chrome.driver","E:\\Drivers\\chromedriver_win32_new\\chromedriver.exe");
	 WebDriver driver = new ChromeDriver();
	 driver.get("https://opensource-demo.orangehrmlive.com/index.php/auth/login");
		driver.findElement(By.id("txtUsername")).sendKeys("Admin");
	   	driver.findElement(By.id("txtPassword")).sendKeys("admin123");
	   	driver.findElement(By.xpath("//input[@id='btnLogin']")).click();
       
   }

   @When("^user enter valid user name and passward$")
   public void user_enter_valid_user_name_and_passward() throws Throwable {
   
	   System.out.println("new changes 1");
	   System.out.println("new changes 2");
       }

   @Then("^user should logged in sucessfully$")
   public void user_should_logged_in_sucessfully() throws Throwable {
       
   }
		
	}
	

