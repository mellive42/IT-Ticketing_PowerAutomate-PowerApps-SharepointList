# Centralized IT Ticketing app - Power Apps
This app was created via Power Apps, so users can submit new tickets and consult existing tickets.

  Main page:
  <br><img width="312" height="536" alt="image" src="https://github.com/user-attachments/assets/77e9d76b-6d30-4527-a647-5193b1df8b95" /> 
  
  Submitting a ticket:
  <br><img width="312" height="536" alt="image" src="https://github.com/user-attachments/assets/e28142b3-ba56-4435-a1ba-cc7b54cf40fa" />
  
  Seeing ticket queue:
  <br><img width="312" height="536" alt="image" src="https://github.com/user-attachments/assets/f2d6fd7c-2e26-4003-9032-d40ae62f7435" />
  
  Consult ticket details:
  <br><img width="312" height="536" alt="image" src="https://github.com/user-attachments/assets/426ee3b2-b044-457b-8092-1d683b70c491" />
  

# Automated email updates - Power Automate
Once a ticket is created the IT team receives an automated email notifying them of the newly created ticket:
<br><img width="514" height="276" alt="image" src="https://github.com/user-attachments/assets/29cd61d8-1ef1-4280-bcfe-392023079984" />

Using the flow:
<br><img width="1072" height="671" alt="image" src="https://github.com/user-attachments/assets/3f4097ef-a699-4bf4-a208-1d40e6ac5b6c" />

Additionally, once the tickeet is completed an automated email notifies the requestor:
<br><img width="830" height="240" alt="image" src="https://github.com/user-attachments/assets/24a34eaa-1375-4603-923b-ffca3a6b342d" />

Using the flow:
<br><img width="1362" height="784" alt="image" src="https://github.com/user-attachments/assets/e93bada5-dfc1-43c3-8990-c9c67deef037" />


# Ticket repository - Sharepoint Lists
The ticket data is automatically registered in a Sharepoint List upon submission from the requestor's ticket. Here the IT Team can consult the tickets and update their status. The creation within the list and the Status column update is what triggers the flows in Power Automate described above. 
<br><img width="892" height="628" alt="image" src="https://github.com/user-attachments/assets/032a38c0-d784-4ffe-9591-06a6e995640a" />
