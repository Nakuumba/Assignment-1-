# Assignment-1-
Assignment 1 done by Group 59

The points that need to be satisfied are as follows:creates value for the business measured in financial returns per product/service portfolio, 
create efficiency in the human resource function, create customer relationship management database to serve as a sales tool.

We decided to create a Webpage that both contains information about Ayesha and once the customers gain interest they can become exclusive members by signing up for a
Virtual Phone platform that allows them to buy the latest products and communicate directly with the company all whole receiving exclusive deals.

Module 1
Customer Care 
This is the first app on the virual phone and it deals with the 
contributor (George Diyeve)

Module 2  
Beauty Queens 

Hair Style Catalogue
When a customer whether old or new, they can view the different hair styles that Ayesha’s business offers. They are able to see the hairstyles from different angles and view they price and time it would potential take to complete. 
This will put a customer at ease that they people doing their hair are professionals that are capable of doing a great job. This process will be simple for the customer to use.
c
ontributor (Jesaya Nakuumba)

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

//Website Access LogIn details
Start 
Enter "www.AyeshaBeauty.com"
Display "Virtual LogIn"
Prompt user for LogIn details
Get "username==(1) && password==(2)"
logIn = username1 + password1
Proceed to virtualPhone 
//Once logged in show Virtual Phone and select application

Choice 
Display "Applications"
Get choice
Case of (Choice){
1) Customer Care
2) Beauty Queens
3) Employees
4) Products & Shipping
5) Finances
End case
End

##Module 1

Customer Care
selectProblem(){
1) I registered but can't login
2) Be assisted by worker
3) Product shipment
4) Applying for ayeshaCreditCard 
5) Balance enquiry
}endfunction
Start
Prompt the user for query
Get query
If (problem  == '1')then
Display "username=customerID + password=St@customerID"

else if (problem  == '2')then
call/contact (JOE)
fetch(employeeCode){
count = 0
DOWHILE (count < 9)
employeeCode = employeeCode + name[count]  
count = count + 1
ENDDO

else if (problem  == '3')then
fetch(Transport module)
call "driver"

else if (problem  == '4')then


else if (problem  == '5')then
fetch(Finance module)
Prompt user for Pin
Get Pin
Balance = currentBalance - Amount
Display "Balance"
else
Display "webPage is undergoing maintenance"

	end if
      end if
    end if
   end if
 end if
End

logIn(details){
username && password
If registered (username == "Ayesha" && password == "1234") then
access is granted

}end function

logIn(){
if (username !="customerID" && password !="St@customerID") then 
display errorMessage
else if (username =="customerID" && password =="St@customerID")then
display virtualPhone
}endfunction
  End if 
 End if
End

##Module 2
Beauty Queens

Start
Count=0
Do While (count<80)
Prompt the user for hairStyle[count]
Get hairStyle[count]
Count=count+1
End Do
Count2=0
Do While (count2<30)
Display hairstyle[count2]
Count2=count2+1
End Do
End


START
HairStyles=0
 DO (count= 0 to 39)
   prompt user for hairStyles(count)
   get hairStyles[count]
 ENDDO
Display HairStyle
END

calalogue(){

##Module 3
Start
case of (code) {

    display "ENTER EMPLOYEE CODE : 
    begin
        code 1 : display "BLAKE"
        code 2 : display "AIDAN"
        code 3 : display "SHAUN"
        code 4 : display "ERASTUS"
        code 5 : display "ASHANTE"
        code 6 : display "QUINN"
        code 7 : display "HILTON"
        code 8 : display "BRANDON"
        code 9 : display "OLIVIA"
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



Conclusion the apps are supposed to be created in a more fun way that allow the user to feel like 
they are part of something special. The data stored on the phone allows for easier interaction between users and management.

