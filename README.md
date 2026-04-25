# Step 1: Create a resource group
# Step 2: Search for Azure Database postgreSQL flexible servers and create
# Step 3: Set up Server details and set workload type to 'Dev/Test'
# Step 4: Change the Compute + storage seetings to Burstable to cut down price
# Step 5: Select 'PostgreSQL authentication only' in the Authentication method 
# Step 6: Set up login details
# Step 7: click 'next' to the networking section and Allow public access from any Azure service within Azure to this server
# Step 8: Security ' click on service-managed key'
# Step 9: Review and Create
# Step 10: After deployment, go to resource select settings and click on 'database'
# Step 11: Create a new database 'demodb'
# Step 12: Click on connnect and change database to 'demodb'
# Step 13: Scroll down to 'Connect from browser or locally', Psql and copy the code below
# Step 14: Click on the Cloud shell icon and type 'psql --version'
# Step 15: Paste the code copied in step 12 and enter your password
# Step 16: Final result
