# SQA_Ep-01

Question: 
Create the new class as LaunchFirefoxBrowser

1. launch the Chome/firefox/Safari/Edge brower
2. Navigate to the amazon.com
3. Get the title
4. Navigate to the  slickdeals.net
5. get the title
6. backward to the amazon.com
7 get the title
8. maximize the window
9. refresh the page
10. forward to the  slickdeals.net
11. get the title
12. Close the broswer

Solution: 

driver.navigate().to("https://amazon.com");
System.out.println(driver.getTitle()); 
driver.navigate().to("https://slickdeals.net/");
System.out.println(driver.getTitle()); 
driver.navigate().back();
System.out.println(driver.getTitle()); 
driver.manage().window().maximize();
driver.navigate().refresh();
driver.navigate().forward();
System.out.println(driver.getTitle()); 
driver.close();








