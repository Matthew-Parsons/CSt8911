# Step 1: Create a VM
![alt text](lab4-vm1.png)
![alt text](lab4-vm2.png)
![alt text](lab4-vm3.png)
![alt text](lab4-vm4.png)
![alt text](lab4-vm5.png)

# Step 2: Create an alert rule and corresponding action group for virtual machine created in step 1, if Percentage CPU goes over certain metric stop the virtual machine
![alt text](lab4-alert-ag1.png)
![alt text](lab4-alert-ag2.png)
![alt text](lab4-alert-ag3.png)
Action is linked to automation account created in step 3

# Step 3: Create an Automation account
![alt text](lab4-automation-account.png)

# Step 4: Create a runbook in powershell in the automation account
![alt text](lab4-automation-runbook.png)

# Step 5: Edit the code so that it will stop the virtual machine you created in Step 1 if it has a specific tag and test the code to see if it stops the virtual machine
![alt text](lab4-runbook-test1.png)
![alt text](lab4-runbook-test2.png)
![alt text](lab4-runbook-test3.png)
![alt text](lab4-runbook-test4.png)
![alt text](lab4-runbook-test5.png)

# Step 6: After demo delete all resources and policies created
![alt text](lab4-deleted-RG.png)