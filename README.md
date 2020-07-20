# Stock Api<br />
**Api Link = http://leethere.herokuapp.com/stock <br />
Method = Post<br />
Accept = URLENCODED (it does not accept json format)<br />
Commands<br />
List : Returns List Of Stocks <br />
Price : Returns Stocks List With Price<br />
Detailedstock : Returns Dictionary Consist Of-<br />
Price,Name,Volume,Last-Traded-Price And Many More<br />
#Example in Python<br />**                                                                                                                                           
```
import request
list = requests.post('http://leethere.herokuapp.com/stock',data='list').text
print(list)
// IT WILL RETURN LISTS OF STOCK
```
#SIMPLE BETTER FASTER
