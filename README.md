# ib-camping
Simple Portfolio-Monitor for FA-Accounts on InteractiveBrokers

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

