# Twice-as-old---Kata


This is a kata 8 

Description:

How many year AGO was the father/mother the double age of his/her son/daughter: 


Test number ====> parent age = 36;  child age = 7


Logic behind this problem. 


first focus on child age;  child age = 7


then double that number ===> 14


then substract parents age with the double child's age ===> 36 - 14 = 22.


this means that 22 years ago the parent was 14, which is the double of actual child's age, which is 7. 

another number example :


parent age = 22; child age = 1;


double of child age == 2 


parent age substract double of child age ===> 22 - 2 = 20


this means... 20 years ago the parent was two years old; which is double of child age which is one. 




FYI In this Kata there is a mistake in numbers. if the age of parent is less than double of child age you have to convert the number to positive

ex:


parent age = 48 

child age = 28


double of 28 = 56 

when you subtract parent age minues double child age you get negative eight. ====> 48 - 56 = -8 





here is the code of this problem:


function twiceAsOld(parentYearsOld, childYearsOld) {
  
  var c = childYearsOld*2
 
 var d = parentYearsOld - c;
  
  if(d <= 0)
   
   return d*(-1);
 
 else
  
  return d
  
}



Enjoy your day and remember ABC... Always Be Coding !
