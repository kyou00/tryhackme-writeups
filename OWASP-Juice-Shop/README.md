OWASP Juice Shop

December 8, 2023 

```
jim@juice-sh.op -tryhackme123
admin@juice-sh.op - admin123
mc.safesearch@juice-sh.op - Mr. N00dles
```

#### Task 1 - Open for business!

- Once the machine has loaded, access it by copying and pasting its IP into your browser; if you're using the browser-based machine, paste the machines IP into a browser on that machine.
	- `No answer needed`

#### Task 2 - Let's go on an adventure!

- Question #1: What's the Administrator's email address?
	- `admin@juice-sh.op`

- Question #2: What parameter is used for searching? 	
	- `q`

- Question #3: What show does Jim reference in his review?
	- `Star Trek`

#### Task 3 - Inject the juice

- Question #1: Log into the administrator account!
	- `32a5e0f21372bcc1000a6088b93b458e41f0e02a`

- Question #2: Log into the Bender account!
	- `fb364762a3c102b2db932069c0e6b78e738d4066`

<details>
	Steps:
	Just put this in the username when you intercept the POST request in the website using burp. 

 	This

 	
</details>

#### Task 4 - Who broke my lock?!

- Question #1: Bruteforce the Administrator account's password!
	- `c2110d06dc6f81c67cd8099ff0ba601241f1ac0e`

- Question #2: Reset Jim's password!
	- `094fbc9b48e525150ba97d05b942bbf114987257`

#### Task 5 - AH! Don't look!

- Question #1: Access the Confidential Document!
	- `edf9281222395a1c5fee9b89e32175f1ccf50c5b`

- Question #2: Log into MC SafeSearch's account!
	- `66bdcffad9e698fd534003fbb3cc7e2b7b55d7f0`

- Question #3: Download the Backup file!
	- `bfc1e6b4a16579e85e06fee4c36ff8c02fb13795`

#### Task 6 - Who's flying this thing?

- Question #1: Access the administration page!
	- `946a799363226a24822008503f5d1324536629a0`

- Question #2: View another user's shopping basket!
	- `41b997a36cc33fbe4f0ba018474e19ae5ce52121`

- Question #3: Remove all 5-star reviews!
	- `50c97bcce0b895e446d61c83a21df371ac2266ef`

#### Task 7 - Where did that come from?

- Question #1: Perform a DOM XSS!
	- `9aaf4bbea5c30d00a1f5bbcfce4db6d4b0efe0bf`

- Question #2: Perform a persistent XSS!
	- `149aa8ce13d7a4a8a931472308e269c94dc5f156`

- Question #3: Perform a reflected XSS!
	- `23cefee1527bde039295b2616eeb29e1edc660a0`

#### Task 8 - Exploration!

- Access the /#/score-board/ page
	- `7efd3174f9dd5baa03a7882027f2824d2f72d86e`