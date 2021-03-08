# TEST

I have tried updating many times

updating today -first change-

Difference bewtween driver.findElements and driver.findElements

Driver.findElements return a list of WebElement
Driver.findElement return a single WebElement

Driver.findElements- if unable to findElement then it will return a list with size zero
Driver.findElement-if unable to find Element then it will throw NoSuchElement exception


Different alert commands
alert.accept()
alert.dismiss()
alert.getText()
alert.sendKeys("ABC")


what is synchronization and how do you acheive synchronization in selenium


Synchronization is the process of running two applications simultaneously with out any issues.
for example and webdriver and our applications will be running at different speeds.
WebDriver will be fast compared to our application and that can cause ElementNot found exception.
In order to avoid that we can go for synchronization.

Synchronization can be acheived using wait commands.
We can use explicit wait  for this.
