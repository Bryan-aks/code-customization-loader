# Code customization loader for webpack

Checking and removing different code blocks from webpack bundled script for several customers.   


normal code

/** CHECK_CUSTOMER_START [customer1, customer2] **/

code block to remove for all customers except customer1 and customer2

/** CHECK_CUSTOMER_END **/

normal code


## Usage

[Documentation: Using loaders](http://webpack.github.io/docs/using-loaders.html)

## Parameters 

####customer 

Id of current customer

####logLevel 

0 - no log

1 (default) - log code fragments

2 - full log

## License

MIT (http://www.opensource.org/licenses/mit-license.php)
