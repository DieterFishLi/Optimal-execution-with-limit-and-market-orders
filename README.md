# Optimal-execution-with-limit-and-market-orders
The repo is dedicated to reproduce results of the paper 'Optimal execution with limit and market orders' written by Álvaro Cartea and Sebastian Jaimungal (https://doi.org/10.1080/14697688.2015.1032543)



<p align="center">
  <img src=./pics/inventory_hist.png width="300" alt="Inventory"/>
</p>

ÁC and SJ propose an execution policy that tells when to cancel a limit order and submit a market order instead when targeting 
a given volume schedule, such as Almgren-Chriss or TWAP. According to my experience, the waiting time for the LO to be filled is 
hard-coded/ predetemined (invariant within the trading horizon). A potential improvement to the above mentioned method is to optimally switch
between LO & MO.

<p align="center">
  <img src=./pics/mid_price.png width="600" alt="Price"/>
</p>


<p align="center">
  <img src=./pics/price_per_share_.png width="400" alt="Cost"/>
</p>


This paper provides a nice way to that. Moreover, this paper tackles the problem of the depth of LOs. 

I am only a beginner to algo tading / optimal control. Please do remind me if I make any mistake in repo. Feel free to leave a comment.

<p align="center">
  <img src=./pics/schedule.png width="400" alt="schedule"/>
</p>


