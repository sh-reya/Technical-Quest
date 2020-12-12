# Day-wise content of my Technical Training:
 
 Day 52:
 # IP, netmask, and gateways
 How can we make our system ping to google but not to FB without involving firewall?
 Ans: By making some minor manipulation in the routing table.
 We can simply remove the undesired IP from the routing table. 

 CONCLUSION:
  Our system can ping to any other system only if its IP is present in the range of IPs in the routing table.
  However, according to need, we can maniputable the table. What is the process of doing? Step by Step process is available in the folder named day 52

 # DevOps
  The new terminologies that we came across are:
  - [x] Handlers
  - [x] Notify
  - [x] ignore_errors

  ignore_errors is a useful module, which helps us to solve a use-case. In ansible, if one task fails, other task are not executed and the playbook is terminated. It can be a useful feature when multiple tasks are interrelated, but sometimes we dont want this to happen.

  - command: "date1234"
     ignore_errors: yes
  Now, even if the date command will not run, as it is wrong, our ansible playbook wil ignore this error.
