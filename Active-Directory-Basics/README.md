# Active Directory Basics

December 20, 2023
-----------------------------------

#### Task 1 - Introduction

- Click and continue learning!
	 - `No answer needed`

-----------------------------------

#### Task 2 - Windows Domains 

- In a Windows domain, credentials are stored in a centralised repository called...
	- `Active Directory`

- The server in charge of running the Active Directory services is called...
	- `Domain Controller`

-----------------------------------

#### Task 3 - Active Directory

-  Which group normally administrates all computers and resources in a domain?
	- `Domain Admins`

- What would be the name of the machine account associated with a machine named TOM-PC?
	- `TOM-PC$`

- Suppose our company creates a new department for Quality Assurance. What type of containers should we use to group all Quality Assurance users so that policies can be applied consistently to them?
	- `Organizational Units`

---------------------------------

#### Task 4 - Managing Users in AD

- What was the flag found on Sophie's desktop?
	- `THM`

- The process of granting privileges to a user over some OU or other AD Object is called...
	- `Delegation`

---------------------------------

#### Task 5 - Managing Computers in AD

- After organising the available computers, how many ended up in the Workstations OU?
	- `7`

- Is it recommendable to create separate OUs for Servers and Workstations? (yay/nay)
	- `yay`

---------------------------------

#### Task 6 - Group Policies

- What is the name of the network share used to distribute GPOs to domain machines?
	- `SYSVOL`

- Can a GPO be used to apply settings to users and computers? (yay/nay)
	- `yay`

---------------------------------

#### Task 7 - Authentication Methods

- Will a current version of Windows use NetNTLM as the preferred authentication protocol by default? (yay/nay)
	- `nay`

- When referring to Kerberos, what type of ticket allows us to request further tickets known as TGS?
	- `Ticket Granting Ticket`

- When using NetNTLM, is a user's password transmitted over the network at any point? (yay/nay)
	- `nay`

-----------------------------------

#### Task 8 - Trees, Forests and Trusts

- What is a group of Windows domains that share the same namespace called?
	- `Trees`

- What should be configured between two domains for a user in Domain A to access a resource in Domain B?
	- `a trusting relationship`

