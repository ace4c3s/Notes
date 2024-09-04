- Authentication is a process of verifying a user's identity, normally by credentials. Checking that somebody is really who they claim to be. 
    

- A dictionary attack is a  method of breaking into an authenticated system by iterating through a list of credentials. 
    

- Burpsuite and hydra are commonly used to perform this kind of attack. 
    

- Burp intruder automates and customizes web attackers. It loops through and submit a login request using a list of default credential, in the hopes that one of the usernames and passwords in list is correct. 
    

**Process** 

- Fire up burpsuite 
- Go to proxy and turn intercept on 
- Visit the website and navigate the login form 
- Send intercepted traffic to intruder 
- Highlight the values entered and add them as positions 
- Change the attack type to cluster bomb. Accepts multiple positions for looping through each one of them 
- Add the positions' values 
- Start the attack 
- Sort through status and length of each combination. A successful combination will have a different status code or length.