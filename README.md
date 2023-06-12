# Jmeter-Dmoney

# Technology Used:

*Apache JMeter

*Java

# Scenario :

Add following requests:

1.Login to user
2.Create a new agent
3.Give balance to the newly created agent from system
4.Create a customer
5.Search the newly created user by phone number
6.Deposit balance to the customer from the agent
7.Withdraw some money from the agent
8.Delete the user

# How to run this project:
clone this project
save the DmoneyApi.jmx file into bin folder of installed location of Jmeter
open the DmoneyApi.jmx file with jemeter & run the project
to Generate report on the command prompt, delete the already copied .csv file and Report folder from the project
hit the command:
$ jmeter -n -t DmoneyApi.jmx -l DmoneyApi.csv -e -o Reports

# Html Report:
![Screenshot (478)](https://github.com/Diba327/Jmeter-Dmoney/assets/62925300/e232138d-76e8-4baf-987c-d525252cd123)
![Screenshot (479)](https://github.com/Diba327/Jmeter-Dmoney/assets/62925300/ec01bec1-a30a-402a-8ad1-51e879e412b3)
![Screenshot (480)](https://github.com/Diba327/Jmeter-Dmoney/assets/62925300/c365ee2e-7941-4be8-a954-70849af1832a)







