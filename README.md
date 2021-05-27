# Assignment-1-
Assignment 1 done by Group 59

The points that need to be satisfied are as follows:creates value for the business measured in financial returns per product/service portfolio, 
create efficiency in the human resource function, create customer relationship management database to serve as a sales tool.

We decided to create a Webpage that both contains information about Ayesha and once the customers gain interest they can become exclusive members by signing up for a
Virtual Phone platform that allows them to buy the latest products and communicate directly with the company all whole receiving exclusive deals.

Module 1
Customer Care 
contributor (George Diyeve)

Module 2 
Beauty Queens 
contributor (Jesaya Nakuumba)

Module 3 
Employees
contributor (Aidan Reid)
It gives different information to the admins and employees. Acts as a sort of view mechanism where 
Employees can only check their own information and admins can check all their info.

Module 4 
Products  & Shipping
contributor (Andrew Festus)

Module 5 
Finances
contributor (Jesaya & George)
-------------------------------------------------------------------------------------------------------------------------------------------------:-)

#Module 1
//Website Access LogIn details
Start 
Enter "www.AyeshaBeauty.com"
Display virtualLogIn
Prompt user for LogIn details
Get "username==(1) && password==(2)"
logIn = username1 + password1
Proceed to virtualPhone 
Fetch LogIn(details)
//Once logged in 
Enter Virtual Phone

Choice
Display "Please select choice"
Get choice
Case of (Choice){
1) Customer Care
2) Beauty Queens
3) Employees
4) Products & Shipping
5) Finances
End case
End

logIn(details){
username && password
If registered (username == "Ayesha" && password == "1234")


logIn(){
If (LogIn details are false) then 
Display "Access Denied!"
Else 
If (LogIn details are false)then
redirect to registrationPage
}endfunction
  End if 
 End if
End

begin
    numeric nRoll
    display "ENTER EMPLOYEE CODE : "
    accept nRoll
    switch(nRoll)
    begin
        case 1 : display "BLAKE"
            break;
        case 2 : display "AIDAN"
            break;
        case 3 : display "SHAUN"
            break;
        case 4 : display "ERASTUS"
            break;
        case 5 : display "ASHANTE"
            break;
        case 6 : display "QUINN"
            break;
        case 7 : display "HILTON"
            break;
        case 8 : display "BRANDON"
            break;
        case 9 : display "OLIVIA"
    end case
end

class Employee
  input string lastName
      num hourlyWage
      num weeklyPay

  void setLastName(string name)
     lastName = name
    return

  void setHourlyWage(num wage)
     hourlyWage = wage
     calculateWeeklyPay()
    return

  string getLastName()
  return lastName

  num getHourlyWage()
  return hourlyWage

  num getWeeklyPay()
  return weeklyPay

  void calculateWeeklyPay()
       num WORK_WEEK_HOURS = 40
      weeklyPay = hourlyWage * WORK_WEEK_HOURS
     return
endclass


void setHourlyWage(num wage)
   inputs
        num MINWAGE = 13.50
        num MAXWAGE = 65.00
   if wage < MINWAGE then
      hourlyWage = MINWAGE
   else
      if wage > MAXWAGE then
         hourlyWage = MAXWAGE
      else
         hourlyWage = wage
      endif
    endif
    calculateWeeklyPay()
return



  Employee = myAssistant
  num LOW = 13.50
  num HIGH = 65.00
       myAssistant.setLastName("Izaaks")
       myAssistant.setHourlyWage(LOW)
    print "My assistant makes ",
      myAssistant.getWeeklyPay(), "per week"
 myAssistant.setHourlyWage(HIGH)
    print "my assistant makes "
      myAssistant.getWeeklyPay(), "per week"
      
      
input employeeCode

Enter employeeCode
logIn(){   if employeeCode = "true"
      print "code valid" then
      output employeeInformation
   Else
      if employeeCode = "false"
         print "code invalid" then
         redirect to homePage
}endfunction
      Endif
   Endif
end  

//Module 4
Start

READ Product 1

Product1 = Hair Spray

READ Product1Cost

Product1 Cost = 50

Print Product1 + Product1 Cost

OUTPUT = Hair Spray 50


Product2 = Shampoo
Product3 = Conditioner
Product2 Cost = 45 && Product Cost = 75

IF (Customer buys Product1) then
Product1 IS Sold

If(Customer BuyingPrice FOR Product2 IS < 45) then
Print "Not Enough Money"
Else if
(Customer BuyingPrice FOR Product2 = 45) then
Cost = Cost - sellingPriceSUBTRACT SellingPrice FROM BuyingPrice THEN
OUTPUT = "Here is your change"
  End If
 End If
End

IF Customer BuyingPrice FOR Product3 IS < 75 THEN
OUTPUT = "Not Enough Money"
ELSE IF Customer BuyingPrice FOR Product3 IS > 75 THEN
SUBTRACT SellingPrice FROM BuyingPrice THEN
OUTPUT = "Here is your change"
END


Start
Prompt user for gender
get gender
   If (Gender==male) then
     Display "MaleCatalogue"
   else
     (Gender==female) then
     Display "FemaleCatalogue"
   endif
Display "selected hairstyle"

HairStyles=0
DO (count= 0 to 69)
prompt HairStyles(count)
get HairStyles(count)
ENDDO
Display HairStyle
END
START
HairStyles=0
 DO (count= 0 to 39)
   prompt HairStyles(count)
   get HairStyles(count)
 ENDDO
Display HairStyle
END

Start
Website Access
//LogIn details
1)username1 == "Ayesha"
2)password1 == "1234"
Input "www.AyeshaBeauty.com"
Display virtualLogIn
Prompt user for LogIn details
Get LogIn ()
Proceed to virtualPhone

logIn(){
username= Ayesha
password= 1234
}endfunction
  End if 
 End if
End
If (LogIn details are false) then 
Print "Access Denied!"
Else 
If (LogIn details are false)then
redirect to registrationPage
Start 
Display Virtual Phone
Prompt user for LogIn details 
(1)Username = customerID
(2) Password = St@customerID
If (username = (1) AND password = (2)) then
Proceed to Profile 
else if 

Display invalidDetailsMessage
 End if
End if
End

Conclusion the apps are supposed to be created in a more fun way that allow the user to feel like 
they are part of something special. The data stored on the phone allows for easier interaction between users and management.


