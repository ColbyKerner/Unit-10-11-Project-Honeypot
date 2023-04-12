# Unit-10-11-Project-Honeypot
# Honeypot Assignment

**Time spent:** 7 hours spent in total

**Objective:** Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

### MHN-Admin Deployment (Required)

**Summary:** How did you deploy it? Did you use GCP, AWS, Azure, Vagrant, VirtualBox, etc.?
I used GCP in order to deploy since this was what was what code path suggested. This process was pretty straightforward since the directions were created as if the student was using GCP. This resulted in the creation of both virtual machines listed in the directions. 

![Screenshot VM instances](https://user-images.githubusercontent.com/122297650/231557512-c1d51a17-c43d-463c-ba55-a6a46f8b9122.gif)


### Dionaea Honeypot Deployment (Required)

**Summary:** Briefly in your own words, what does dionaea do?
Dionaea is a type of honeypot that is considered to be low level. Its use is to be able to capture malware and different types of attack payloads.

![Screenshot of attack report](https://user-images.githubusercontent.com/122297650/231557439-4f01b805-2ca7-48e6-8816-82d65d820f5b.gif)

### Database Backup (Required) 

**Summary:** What is the RDBMS that MHN-Admin uses? What information does the exported JSON file record?
In order to do this, there needs to be two VMs set up. One would be the admin VM and the other would be the honeypot. The single Admin VM will deploy, manage, and collect data from the honey pot. in turn, the honeypot will obviously proivde the data for this. The JSON file will then record all of the data that is collected from the Admin VM.


### Deploying Additional Honeypot(s) (Optional)

#### X Honeypot

**Summary:** What does this honeypot simulate and do for a security researcher?
The goal of this it to expose insecure features that would be exploited by an attacker. This is all done on purpose to see what information can be revealed. This is important for a security researcher because it will help them to understand the threats available to attackers and what information they can gather from doing so.

<img src="x-honeypot.gif">

## Notes

Describe any challenges encountered while doing the assignment.

The largest challange I faced when doing this assingmnet was simply setting up all of the commands in order for me to run my attack. Everything was very straight forward but once I got to the attack phase, trying to download my session.json file was very difficult and took a long time to figure out.
