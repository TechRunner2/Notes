Network Security
========================

single -packet queryresponse<br>
S                R <br>
	query -> <br>
<-	Respone <br>


- IPv4
	- 32 -bit
	- Human-Readable Format:
		- 4 bytes
		- 4 Decimal values
			- Dotted decimal notation
		

2.2.2 IP (Internet Protocol)
- Network layer: host-to-host delivery
	- Trans


4. IP Address
- Ip address: 32-bit identifier


NAT - Network Address Translation


- 3 blocks of Private Ip addresses
- 10.x.y.z (10.0.0.0/8)
  - Not routable on global internet

- Broadcast link
  - Connecting multiple computers
- Point to point link
  - Connecting 2 computer


ipv4 - 32 bit
ipv6 - 128 bit





- Two Types of Network Links

  - Point-to-point: connecting only 2 nodes
  - Broadcast: connecting more than 2 nodes
    - One node sents data, all nodes receive data
    - Two or more nodes sent data simultaneously

- Ethernet (IEEE 802.3)

  - Most widely-sed wired LAN technique
  - Low cost (Ethernet card is as cheap as $20)
  - Kept up with speed race 10Mbps - 10Gbps


Ethernet Frame Structure
- Preamble: synchronize transmission timing between sender and receiver
- Dest MAC addr:
	- if adapter receives frame with matching dest addr, or with broadcast addr, it passes data in frame to network layer
	- otherwise, adapter discards frame
- Type: indicate higher layer protocol (IP, ARP, ...)
- FCS(frame check sequence): error detection


# Cryptogrophy
- Three Primary Security goals
	- Confidentiality
		- The assurance to an entity that no one can read a particular piece of data except the reciever(s) 
		explicityly intended
	- Integrity
		- The assurance to an eentity that data has not been altered (intentionally or unitentionally) between "There"
		and "here", or between "then" and "now"
	- Authentication:
		- The assurance to one entity that another entity is who he/she/it claims to be.

- Basic Assumptions
	- Kerckhoffs' principle: public algorithm, secret key
		- The cipher is completely known to the attacker
		- Only the key is secret
		- That is, crypto algorithms are not secret
	- Secret by obscurity: keep algorithm secret
		- This tactic almost never works
- Two Types of Cryptography
	- Is Encryption key the same as Decryption key?
		- K<sub>e</sub> = K<sub>d</sub>?
	- Secret-key/symmetric cryptography
		- K<sub>E</sub> = K<sub>D</sub>



# Organizations
* ICANN (Internet Corporation for Assigned Names and Numbers)
	* In charge of coordinating  the assignment of domain names and IP addresses
* RIR
	* Managing the allocation of IP addr within a particular region
* Domain Name Registry Operator
	* Maintaining domain name registry (database)
* Domain Name Registrar
	* Agent of _Domain name registry Operator_, managin the reservation of domain names

# Terms
- **Regional Internet Registry**: organization
- **Domain Name Registry**: database
- **Domain Name registry Operator**: organization
- **Domain Name Registrar**: organization
- **Domain Name Registrant**: user/assignee


# Recon
- Social Engineering
- Web
- Whois DB (web interface)
- DNS server (command-line interface)
	- DB: hostname -> IP addr, other info.
	- Protocol:


# Gaining Access
- Using
	- System Attacking
	- Network Attacking

# Sniffing on LAN
- 1: Hub-based LAN
	- Passive sniffing: 
		- Listen Silently
- 2: Switch-based LAN:
	- Active Sniffing:
		- Inject traffic then listen
	- Techniques
		- 1: MAC Flooding
			- Mess up switch and make it behave like a hub
		- 2: ARP spoofing
			- Mess up IP addr to MAC addr translation
		- 3: Port Stealing
			- Mess up MAC addr to switch port translation
		- 4: DNS Spoofing
			- Mess up hostname to IP addr translation
		- 5: Monkey-In-The-Middle (AKA Man-In-The-Middle)
			- Attacker 

- 1: Mac Flooding:
- 2: ARP spoofing:
- 3: Port Stealing:
- 4: DNS Spoofing:
- 5: Man in the middle:

- 1: Encrypt data
- 2: Pay attention to warning message on certificate
- 3: Replace hub with switch

```bash
ifconfig | grep inet | grep -o '[0-9]*\.[0-9]*\.[0-9]*\.[0-9]*' | grep "10"
```



# Keywords
- noarchive:
	- do not save a copy in google cache