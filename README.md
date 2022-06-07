# cs145proj
The Python Module is named Sender.py
with the following options

-f [string] : change path of data(path includes the txt file name)

-a [string/IPv4]: change IP address of receiver

-s [integer]: change port number of receiver

-c [integer]: change port number of sender

-i [string]: change ID

by default these are their values

ip address='10.0.7.141'

port of receiver=9000

ports=6756

id="9bb836ec"

path="9bb836ec.txt"

when running the format will strictly be

python(or python3) Sender.py [tags with the change]

sample

python3 Sender.py -f '/path/to/text.txt' -a 10.2.3.4

Since this protocol assumes that the request is always valid, it will not be responsible for errors due to user input.
