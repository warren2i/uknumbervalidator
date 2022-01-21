Uk Phone Number Validation

This library allows for phone number validation based on the Ofcom National Telephone Numbering Plan.

Useful data can be obtained from a phone number such as locality, mobile provider etc.

Phone numbers are of variable length. Local numbers are supported from land-lines or numbers can be dialled with a '0'-lead prefix that denotes either a geographical region or another service. Mobile phone numbers have their own prefixes which are not geographical and are completely portable between providers.

****
Example usage

The main object that the library deals with is a PhoneNumber object. You can create this from a string representing a phone number

The PhoneNumber object that is produces typically still needs to be validated.

`num1 = Phonenumber('07974350148')`

`print(num1.valid)` True

`print(num1.prefix)` 7974

`print(num1.location)` EE	mobile numbers	UK

`print(num1.suffix)` 350148

`print(num1.mobile)` True

****

`num2 = Phonenumber('01253444444')`

`print(num2.valid)` True

`print(num2.prefix)` 1253

`print(num2.location)` Blackpool

`print(num2.suffix)` 444444

`print(num2.mobile)` False
