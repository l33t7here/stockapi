# stockapi                                                                                                                                                            Api Link = http://leethere.herokuapp.com/stock                                                                                                                      Method = Post                                                                                                                                                   Accept = URLENCODED (it does not accept json format)

#Example in Python                                                                                                                                                   
  import requests
list = requests.post('http://leethere.herokuapp.com/stock',data='list').text //List is command for more command list Go to http://leethere.herokuapp.com/stock
print(list)


#SIMPLE BETTER FASTER
