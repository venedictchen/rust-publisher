# Question

1. How many data your publlsher program will send to the message broker in one run? 
    - Program publisher akan mengirimkan data ke message broker sebanyak 5 data dalam 1 kali run.

2. The url of: amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?
    - Itu berarti subscriber dan publisher memiliki broker yang sama digunakan untuk `messaging` antar subscriber dan publisher.