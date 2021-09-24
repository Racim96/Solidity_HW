# Solidity_HW

![smart-contract](https://user-images.githubusercontent.com/80929638/134748810-44436e59-a6ed-47a2-808f-25718b5d106d.png)

## Purpose: 
The team wants to build smart contracts to automate some company finances to make everyone's lives easier, increase transparency, and to make accounting and auditing practically automatic. These contracts will do several things, for instense pay your Associate-level employees quickly and easily and distribute profits to different tiers of employees

## WalkThrough: 
First, once the solidity code is done, we select the compiler 0.5.17+commit.d19bba13 and compile it. 

  ![image](https://user-images.githubusercontent.com/80929638/134748919-224b8082-a3e2-43ae-b9cd-945eadd7b235.png)
  
In order to deploy the smart contract, I selected the injected web 3 environment and the three addresses that I want to interact with. Address One represents employee one, Address Two represents employee Two and Address Three represents employee Three. The main Account represents the employer account which will be debited a specific amount of ether and be distributed to all three employees equally.


![image](https://user-images.githubusercontent.com/80929638/134749006-a3ca2d88-7fe1-4c93-ba27-ccf0450ba1a8.png)

In this case I wanted to pay each employee 2 ether which means that I had to debit 6 ethers from the main account. This was done by selecting a value (6) and deposit it.

![image](https://user-images.githubusercontent.com/80929638/134749026-4d71371b-7965-4b22-8af8-f5a0b110731e.png)

We can see that now on Ganache 2 ethers were deposited in each of the employees’ account 

![image](https://user-images.githubusercontent.com/80929638/134749041-2588a2c8-0993-45be-aa66-ba043e3261bb.png)

Next I am going to do the same transactions but in Ropsten Test Network: 

![image](https://user-images.githubusercontent.com/80929638/134749056-06fd300f-985d-4c5a-82c6-ab2f5df8bcf9.png)
![image](https://user-images.githubusercontent.com/80929638/134749064-3ed06765-04e3-4912-b8a9-43d3fbe8dd69.png)
