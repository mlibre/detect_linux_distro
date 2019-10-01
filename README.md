# Detect Linux distribution
Simple **python** 3 module/api to detect **Linux distribution**.

## Table Of Contents
* Install from source/git
* Example
* Step By Step example
* Tested Distributions
* [Donate](#donate)

## Install from source/git
~~~bash
git clone "https://github.com/mlibre/detect_linux_distro.git"
cd detect_linux_distro/
sudo python setup.py install
~~~

## Example  
~~~python
from detect_linux_distro.dld import dld
my_linux_name = dld()
my_linux_name.detect()

my_linux_name.print_all_result()

#my_linux_name.get_distro_id()
#my_linux_name.get_distro_name()
#my_linux_name.get_distro_pretty_name()
#my_linux_name.print_all_result()
~~~


### Step by step example
1. open terminal
2. create a file like test.py on your Linux
~~~bash
    touch test.py
~~~
&nbsp;&nbsp;&nbsp;&nbsp;3. copy and past this code in test.py
~~~python
    from detect_linux_distro.dld import dld
    my_linux_name = dld()
    my_linux_name.detect()

    my_linux_name.print_all_result()

    #my_linux_name.get_distro_id()
    #my_linux_name.get_distro_name()
    #my_linux_name.get_distro_pretty_name()
    #my_linux_name.print_all_result()
~~~
&nbsp;&nbsp;&nbsp;&nbsp;4. run code
~~~python
    python3 test.py
~~~
&nbsp;&nbsp;&nbsp;&nbsp;or
~~~python
    python test.py
~~~
## Tested Distributions
* arch

>note: probably it's work on all distribution, but i did not test.

## Donate
My Bitcoin Address:
> 3JfNjydkEgKGjsnrU1SoCCAv1q2yTuCoDY