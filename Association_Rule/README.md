Association Rule Learning
================

### What’s the Association Rule Learning (ARL)?

  - Association rule learning from
    [Wikipedia](https://en.wikipedia.org/wiki/Association_rule_learning#cite_note-piatetsky-1)

> a rule-based machine learning method for discovering interesting
> relations between variables in large databases. It is intended to
> identify strong rules discovered in databases using some measures of
> interestingness.

  - Association Mining (Market Basket Analysis) from
    [r-statistics](http://r-statistics.co/Association-Mining-With-R.html)

> Commonly used to make product recommendations by identifying products
> that are frequently bought together. But, if you are not careful, the
> rules can give misleading results in certain cases.

  - Association Rule from
    [RDataMining](http://www.rdatamining.com/docs/association-rule-mining-with-r)
      - To discover association rules showing itemsets that occur
        together frequently \[Agrawal et al., 1993\].  
      - Widely used to analyze retail basket or transaction data.
      - An association rule is of the form A ⇒ B, where A and B are
        items or attribute-value pairs.  
      - The rule means that those database tuples having the items in
        the left hand of the rule are also likely to having those items
        in the right hand.  
      - Examples of association rules:
          - bread ⇒ butter  
          - computer ⇒ software  
          - age in \[20,29\] & income in \[60K,100K\] ⇒ buying
            up-to-date mobile handsets
  - How to measure the strength of a rule?
      - Assume there are 100 students.  
        10 out of them know data mining techniques, 8 know *R language*
        and 6 know both of them.
      - knows R ⇒ knows data mining
          - **support** = P(R & data mining) = 6/100 = 0.06
          - **confidence** = **support** / P(R) = 0.06/0.08 = 0.75
          - **lift** = **confidence** / P(data mining) = 0.75/0.10 = 7.5
