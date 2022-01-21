Uknumbers 

****
Example usage

The main object that the library deals with is a PhoneNumber object. You can create this from a string representing a phone number

The PhoneNumber object that is produces typically still needs to be validated.

`num1 = Phonenumber('07974350147')`

`print(num1.valid)` True

`print(num1.prefix)` 7974

`print(num1.location)` EE	mobile numbers	UK

`print(num1.suffix)` 350147

`print(num1.mobile)` True

****

`num2 = Phonenumber('01253896361')`

`print(num2.valid)` True

`print(num2.prefix)` 1253

`print(num2.location)` Blackpool

`print(num2.suffix)` 444444

`print(num2.mobile)` False
