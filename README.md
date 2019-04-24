# CPSC455-SecurityBankingApp	
### Program created by: 
Nelson Luong nluong@csu.fullerton.edu

Daniel Truong ddtruong50@csu.fullerton.edu

John Nguyen block3d@csu.fullerton.edu

Long Nguyen Longnguyen0024@csu.fullerton.edu 

Scott Ng 

### How to run project
Install these packages before running with these commands

**>** *npm install express*

**>** *npm install client-sessions*

**>** *npm install body-parser*

 **>** *npm install body-parser-xml*

**>** *npm install xss-filters*

**>** *npm install helmet*



Run project with this command

**>** *node dashboard.js*


To exit program, within terminal, **[CTRL + C]**

### This banking application contains these features and functionality:
- User login (unique username & password)
- Register for accounts
- Keeps track of account balances and displays balances
- Withdraw money from accounts
- Deposit money into accounts
- Transfer money between accounts
- Logoff from account
-


### Security implementations:
- Implemented Sessions which log the User off after 3 minutes of idle.

- HTML sanitizing

- used xss-filters to filter user input 

- only numbers can be entered into the deposit/withdrawal/transfer fields

- data is encoded in XML when passed from front-end to back-end

- uses a CSP header to only allow information from trusted sources

		
### Files included along with descriptions
**dashboard.js**: Node.js file that will process all front-end and back-end functions. When login is successful, it will redirect to dashboard page.
**index.html**: Initial page when you access localhost:3000. Includes a login page where you are to input login username and password in order get access the dashboard.
**register.html**: Page where you input Username, first name, last name, email address, password
**mydb.txt**: holds user information that is parsed by XML into JSON format
**/node_modules**: stores “npm” packages



