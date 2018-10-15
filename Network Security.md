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
	* Agent of _Domain name registry Operator_ 

# Terms
- **Regional Internet Registry**: organization
- **Domain Name Registry**: database
- **Domain Name registry Operator**: organization
- **Domain Name Registrar**: organization
- **Domain Name Registrant**: user/assignee

