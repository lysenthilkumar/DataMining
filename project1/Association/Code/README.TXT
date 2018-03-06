•	The program execution is done by running the aprioriProgram.py using Python 3

>python3 aprioriProgram.py

The total number of frequent itemsets are printed from 1 to n, uptil 0 n-frequent itemsets are generated. 

The total number of frequent itemsets are generated.

The association rules are generated and printed.
Association rules will print in the following format. 
G59_Up--------->G72_Up
G72_Up--------->G59_Up
G59_Up--------->G96_Down
G96_Down--------->G59

The total number of association rules is printed as follows.
The total number of rules generated are 4


>Enter your query: “query to be entered here”

To run for any query enter queries in the following for Template 1

(result11, cnt) = asso_rule.template1("xxx", "yyy", [‘zzz’,’zzz’ ])

Replace xxx with RULE, BODY or HEAD.
Replace yyy with NONE, ANY or 1.
Replace zzz with any gene expression.

To run for any query enter queries in the following for Template 2

(result21, cnt) = asso_rule.template2("xxx", K)

Replace xxx with RULE, BODY or HEAD.
Replace K with 1, 2, 3...n. Here n can be any integer. 

To run for any query enter queries in the following for Template 3

(result31, cnt) = asso_rule.template3("abc", "xxx", "yyy", ['zzz'], "xxx", yyy, ['zzz'])

Replace abc with 1or1, 1or2, 2or1, 2or2, 1and1, 1and2, 2and1 and 2and2.
Replace xxx with RULE, BODY or HEAD.
Replace yyy with NONE, ANY or 1.
Replace zzz with any gene expression.

