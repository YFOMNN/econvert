# econvert

First run the following command in a cmd window
~~~
pip install econvert
~~~

Then, Create a new python script

Open the script

Import the module
~~~python
from econvert import econvert as ec
~~~ 
celsius to fahrenheit
~~~python
ec.c_to_f(100)
~~~
The 100 can be changed to any value you wish to convert
fahrenheit to celsius
~~~python
ec.f_to_c(100)
~~~
The 100 can be changed to any value you wish to convert
Full code
~~~python
from econvert import econvert as ec

f = ec.f_to_c(100)

print(f)

c = ec.c_to_f(100)

print(c)

~~~
More convertions will be added soon!!
