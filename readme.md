
## Requirements
-We have some customer records in a text file (customers.txt) -- one customer per line, JSON lines formatted. We want to invite any customer within 100km of Dublin for some food and drinks on us. Write a program that will read the full list of customers and output the names and user ids of matching customers (within 100km), sorted by User ID (ascending). 
-Don't forget, you'll need to convert degrees to radians.
-The GPS coordinates for Dublin area is 53.339428, -6.257664. We're looking for you to produce working code, with enough room to demonstrate how to structure components in a small program. Package the searching algorithm as an abstraction layer and installable component through npm package.


## Usage

### Require

```
let filterCustomer = require('searching-customer-within-a-range');
or
import filterCustomer from 'searching-customer-within-a-range';
```


	filterCustomer.searchingCustomers().catch((err) => {
      console.log(`Error received: `, err.message);
    }).then((eligibleCustomers) => {
      console.log(eligibleCustomers);
    });
```







## Testing Repo

https://github.com/ishwarchandratiwari/testingnpmpackage-searching-customer-within-a-range


just hit:
npm install;
npm start;







