# Common-Cyber-Threats.md
<b><h1>PART A: Definitions</h1></b>
<b>1. What is a cyber threat?</b>
<p>Cyber threats are attempts by criminals or hackers to harm or interfere with computer networks or systems for illegal purposes. Usually, the goal is to steal, modify, or destroy targets by breaking into weak systems and then using that access point as a weapon of attack.</p>

<b>2. What is a vulnerability?</b>
<p>Vulnerabilities are security weaknesses or flaws in an internet-facing application that an attacker could exploit to compromise it and gain entry to steal information or engage in other illegal acts, including poor input validation, incorrect configuration settings or outdated components among many other sources of vulnerability.</p>

<b>3. What is a cyber attack?</b>
<p>Any method by which a malevolent attacker enters a computer or network without authorization and delivers their payload or reward. By using human weaknesses as part of an offensive plan, cyber attackers enable hackers to take advantage of system flaws, including human ones.</p>

<b>4. Explain the difference between a threat, a vulnerability, and an attack.</b>
<p>A threat is when a hacker or criminal attempts to harm your computer networks or system for illegal purposes. A vulnerability is a security weakness or flaws in a business, it could either be physical vulnerability or technical vulnerability. An attack is when a hacker has unauthorized access to a computer or network.</p>

<b><h1>PART B: Research</h1></b>
<b>1. Phishing</B>
<p>Phishing is a type of social engineering in which attackers pose as reputable organizations in order to trick victims into disclosing private information, such credit card numbers, passwords, or business credentials.</p>

<b>How it works</b>
<p>Phishing is usually started by attackers via electronic communication methods, such as phone calls, texts, or emails. There are typically four steps in the process:</p>
<p>1. Reconnaissance: To make their strategy seem plausible, attackers investigate targets utilizing social media, public profiles, or business directories.</p>
<p>2. Pretexting: They create a plausible situation, like an urgent security alert, a billing problem, or an IT support need.</p>
<p>3. Execution: Victims are tricked into doing anything, like reading out a password, downloading a file, or clicking a malicious link.</p>
<p>4. Exploitation: The attackers obtain the data or credentials and use them to gain access to accounts, steal money, or penetrate internal networks.</p>

<b>Real-Life Example</b>
<p>The catastrophic nature of targeted phishing is demonstrated by the July 2020 Twitter cyberattack. Attackers pretended to be IT staff and tricked Twitter employees into giving up their login credentials by using phone spear phishing, commonly referred to as vishing. They used this access to get beyond internal security measures and take over 130 prominent accounts, including those of Bill Gates, Elon Musk, and Barack Obama, in order to operate a cryptocurrency hoax.</p>
<b>Protection Measures</b>
<P>For People:
Use security keys or authenticator apps instead of SMS to enable multi-factor authentication (MFA) on all personal and business accounts.
<P>Regarding Organizations:</P>
Use the least privilege concept to limit lateral movement in the event that credentials are hacked and to restrict access to internal tools.

<b>Ransomware</b>
<p>A malicious software program known as ransomware encrypts a victim's files, locks computer systems, or steals confidential information and demands a monetary payment to unlock it.</p>

<b>How It Operates</b>b>
<p></p>Attacks using ransomware typically have a multi-step, structured lifecycle:</p>
<p>1. Initial Access: Phishing emails, compromised login credentials, or software flaws allow attackers to enter a network.</p>
<p>2. Lateral Movement: After gaining access, the malware searches the network for important files, backups, and administrative controls.</p>
<p> Data Exfiltration: Before encryption, hackers often steal private or sensitive company information, allowing them to use double extortion techniques by threatening to make the information public.</p> 
<p>4. Extortion and Encryption: 1. The ransomware uses sophisticated encryption methods to lock files and then displays a ransom letter requesting payment—usually in cryptocurrency like Bitcoin—in exchange for the decryption key.</p>

 <b>Real-World Examples</b>
<p>Fuel transportation throughout the United States was substantially affected by the ransomware assault on Colonial Pipeline in May 2021. Using a hacked virtual private network (VPN) credential without multi-factor authentication, attackers gained access to the company's IT network.Colonial Pipeline shut down 5,500 miles of pipeline operations as a precaution after the DarkSide ransomware organization compromised company systems. In the end, the business paid a $4.4 million Bitcoin ransom to get the decryption tool.</p>

<b>Protection measures</b>
<p>For individuals:</p> 
Keep regular offline backups of your most crucial personal files so you can restore them without having to pay a ransom.

<p>Regarding Organizations:</p
Implement isolated, unchangeable offline backups that are impervious to malware encryption and deletion.</p>

<b>Password attack</b>
<p>A password attack is an attempt by malevolent actors to break, guess, or steal user passwords in order to obtain unauthorized access to systems, networks, or accounts.</p>
 <b>How It Operates</b>
<p>Automated tools and particular tactics are used in password attacks to get around authentication systems:</p>

1. Target Identification: Attackers typically obtain email addresses or usernames from public directories or prior data breaches in order to identify target user accounts or login portals.

<p>2. Automated Iteration: They quickly evaluate a huge number of password combinations, frequently used dictionary terms, or lists of stolen credentials using specialized scripts.</p>
<b>Real-Life example</b>
<p>The scope of automated password attacks is demonstrated by credential stuffing attempts against major financial and e-commerce systems. From unrelated data breaches, attackers regularly obtain lists of billions of compromised username and password pairs that are sold on the dark web. In order to accomplish successful account takeovers at scale, they use botnets to automatically test these stolen credentials across thousands of unrelated websites, taking advantage of the widespread human tendency to reuse passwords across numerous personal and professional accounts.</p>
<b>Safety Procedures</b>
<p>For People:</p>
To avoid credential reuse, create and preserve lengthy, one-of-a-kind passwords for each online account using a password manager.
<p>Regarding Organizations:</p
To identify and prevent automated login attempts, use rate limitation, account lockout, and bot management.

<b>Social Engineering</b>
<p>Instead of using technical software flaws, social engineering is the psychological manipulation of people into carrying out tasks or disclosing private information by taking advantage of human traits like trust, curiosity, and fear.</p>
<b>How It Operates</b>
<p>Attackers use a planned series of behavioral triggers to control human psychology:</p>
1. Research and Profiling: In order to establish rapport and credibility, attackers obtain public information about a target person or organization from social media, business websites, or public directories.

<p>2. Creating Pretext: To support their request, they create a made-up scenario or character, such as an executive, a government official, or an IT support professional.</p>
<b>Real-Life example</b>
<p>An attacker posing as the head of IT or human resources and phoning a business employee is a classic real-life example. The caller fabricates an urgent issue, saying that if the employee doesn't connect into a given URL or provide their credentials, payroll would fail and a major system upgrade must be applied right away. The employee grants the attacker complete network access because they trust the request's seeming authority and urgency.</p>
<b>Protection measures</b>
<p>For People:</p>
Use a separate, reliable communication channel instead of the one specified in the request to confirm the identity of anyone asking for sensitive information or access.
<p>Regarding Organizations:
To assist staff in identifying manipulation techniques, conduct frequent security awareness training and simulated social engineering exercises.</p>
<b>Denial-of-Service(DoS/DDoS)</b>
<p>A denial-of-service (DoS) or distributed denial-of-service (DDoS) attack is a malevolent attempt to interfere with a targeted server, service, or network's regular operations by flooding it with requests. A DDoS assault uses a vast network of hijacked devices, referred to as a botnet, to execute coordinated floods from several sources, whereas a DoS attack starts with a single machine.</p>
<b>How It Operates</b>
<p>DDoS assaults usually target network bandwidth or system resources through a multi-stage process:</p>
1. Botnet Assembly: To construct a remotely controllable botnet, attackers infect thousands or millions of linked devices (such computers, servers, or Internet of Things appliances) with malware.
<p>2. Command and Coordination: Using a command-and-control server, the attacker instructs all of the network's bots to target a particular IP address or service at the same time.</p>

<b>Real-world metrics</b>
<p>Amazon Web Services (AWS) defended against a significant volumetric DDoS attack in February 2020, which peaked at 2.3 Tbps, the highest rate ever recorded at the time. The attack demonstrated how attackers abuse open network protocols and third-party infrastructure to cause widespread service outages. It targeted a customer using AWS Shield and used compromised Connection LDAP (CLDAP) web servers to amplify and reflect massive amounts of traffic toward the victim's infrastructure.</p>

<b>Protection measures</b>
<p>For People:</p>
To stop home routers and linked smart devices from being recruited into botnets, make sure they are secured with strong, one-of-a-kind administrator passwords and updated firmware.
<p>egarding Organizations:Use content delivery networks (CDNs) with Anycast routing and cloud-based DDoS mitigation services to distribute and absorb volumetric traffic spikes before they reach origin servers.</p>

<b><h1>Part C: Critical thinking</h1></B>
<p>1. Which cyberattack, in your opinion, is the most hazardous right now, and why?</p>

Because it may entirely disrupt an organization's activities by encrypting vital data and demanding payment for its release, ransomware is one of the most destructive assaults available today. In order to threaten to reveal private information if the ransom is not paid, modern ransomware assaults frequently entail collecting sensitive data before encrypting it. Because of this, businesses that depend on continuous access to secure data, including banks, hospitals, and government agencies, are especially vulnerable to the attack. Ransomware is one of the biggest cybersecurity risks that businesses face today since it can cause financial losses, harm to an organization's brand, legal repercussions, and the disruption of vital services.
<p>2. Which three security measures would you put in place initially to safeguard clients if you were a bank's IT manager?</p>

The first security precaution I would put in place if I were a bank's IT manager is multi-factor authentication (MFA), which makes it considerably harder for unauthorized access by requiring customers and staff to authenticate themselves using more than just a password. Second, I would use sophisticated encryption to safeguard private client data while it is being transmitted and stored, making it difficult for hackers to access even if it is intercepted.
