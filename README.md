# InvokeBrowser
//Write a Test Script to open the Test URL in Chrome Browser//
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

public class OpenUrlInChrome {
    WebDriver driver;
        driver = new FirefoxDriver();
        driver.get("https://netbanking.hdfcbank.com/netbanking/");
        driver.manage().window().maximize();
        System.out.println(driver.getTitle());
        Thread.sleep(2000);
        driver.quit();
}
