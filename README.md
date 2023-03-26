# GithubFinalProject

## Explanation

A calculator that calculates simple interest given principal, annual rate of interest and time period in years.

## Input:
   p, principal amount
   t, time period in years
   r, annual rate of interest
   
   ```shell
   echo "Enter the principal:"
   read p
   echo "Enter rate of interest per year:"
   read r
   echo "Enter time period in years:"
   read t
   ```
   
   
## Output:
   simple interest = p*t*r
   
   ```shell
   s=`expr $p \* $t \* $r / 100`
   echo "The simple interest is: "
   echo $s
   ```
   
## Contributing
Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.
   
## License
[Apache Licence, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0)
