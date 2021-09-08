# assignment2-Ganguru

## Rohith Sai Ganguru
###### Palawan Island

The above **Palawan Island** was in **Philippines**.

### Travel Guide

---

1. Get a cab in Maryville or Rent car to Kansas(MCI) Airport
    1. Volvo, BMW are the best rental cars
        1. Charge will be around $200
    2.Cab charge to the airport will be $50
2. Take a flight from Kansas(MCI) to Chicago(ORD)
    1. American Airlines are flexible with the timings
        1. Charge of the ticket will be $220
    2. Southwest Airlines are cheaper compared to American Airlines
3. From Chicago take flight to Philippines Capital Manila
* In Manila Buy some Food/Drinks for Enjoyment
    * Food Needed
        * Pizza
        * Chicken
        * Rice/Breads
    * Drinks Mandatory
        * Coke
        * Beers
        * Vodka
4. From Manila go to the Palawan Island by Boat

[ABOUT ME](AboutMe.md)

The following table describes the 4 types of food/drinks that everyone should try.<br>
It describes the food/drink item name, location and amount of money.

### Tables

---

| Food/Drink Item | Location | Amount |
|   ----------    |  -----   |   ---- | 
|   Cheese Pizza  |  Kansas  |    30  |
|   Corona Extra  |  Texas   |    90  |
|   Peproni       | MaryVille|    10  |
|   Glennleivdt   |  Chicago |   150  |

### Quotes

---

> The best way is to predict free future is to create it - *ABRAHAM LONCOLN*

> Every pain gives a lesson and every lesson changes a person - *A.P.J ABDUL KALAM*

## Code Fencing

---

> Ternary search is a divide and conquer algorithm that can be used to find an element in an array. 
> It is similar to binary search where we divide the array into two parts but in this algorithm, we divide the given array into three parts and determine which has the key (searched element).

The function `terenary_search` has the definition
```
double ternary_search(double l, double r) {
    double eps = 1e-9;              //set the error limit here
    while (r - l > eps) {
        double m1 = l + (r - l) / 3;
        double m2 = r - (r - l) / 3;
        double f1 = f(m1);      //evaluates the function at m1
        double f2 = f(m2);      //evaluates the function at m2
        if (f1 < f2)
            l = m1;
        else
            r = m2;
    }
    return f(l);                    //return the maximum of f(x) in [l, r]
}
```

Let's know about more about Terenary Search <https://cp-algorithms.com/num_methods/ternary_search.html>
