# ib-camping
Simple Portfolio-Monitor for FA-Accounts on InteractiveBrokers

The monitor is realized with 470 lines of code using ib-ruby and camping. 
You can select any detected Account. In addition to basic information, such as the NetLiquidation, the used Margin and available Cash, all portfolio-positions are displayed. A simple form to place an emergency-order is provided, too.

Install Ruby 2.2 (via rvm)
Initialize with 'bundle install' following with 'bundle update'

Start a TWS or a Gateway with multible Accounts (A Demo-Account is prefered)

Edit the script and change the :host-Entry in line 12 to the host running the TWS/Gateway (eg. 'localhost').
If a connection is made with the Gateway, specify the port, too, eg 'localhost:4001'

Run the camping-Server 
```
camping simple_monitor.rb -p 3333
```

Open a Browser-Window at http://localhost:3333

enjoy

