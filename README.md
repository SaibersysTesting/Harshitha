# Harshitha
import org.testng.annotations.AfterClass;
import org.testng.annotations.BeforeClass;
import org.testng.annotations.Test;

public class testing {

	  
@BeforeClass
public void login(){
 System.out.println("login successfully");

	}
@AfterClass
public void logout(){
	 System.out.println("logout successfully");
}
@Test
public void search(){
	 System.out.println("search successfully");
}
@Test
public void advancedsearch(){
	 System.out.println("advanced search successfully");
}
@Test
public void buyproducts(){
	 System.out.println("buying products  successfully");
}
}

