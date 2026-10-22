> [!NOTE] [[Exam Objectives.pdf#page=4&selection=7,0,8,22|OBJ 1.1]]
> Explain concepts related to the Open Systems Interconnection (OSI) reference model.

# Session Layer
- Keeps conversations separate to prevent intermingling of data
## Set Up Session
- Checking of user credentials and assigning numbers to sessions to help identify them
- Example:
	- Student raises hand to ask question
	- Professor acknowledges student's request
	- Both student and professor know who each other are and what each other wants
## Maintain Session
- Where data transfers back and forth across the network
	- Example:
		- Student and professor go back and forth
- If break happens, need to reestablish connection
	- Example:
		- Professor: "I'm sorry, I didn't hear you. Can you repeat your question?"
- Acknowledge receipt
	- Example:
		- Professor: "Did you understand my answer?"
		- Student: "Yeah, I did."
## Tear Down Session
- Ending of a session after the transfer is done or when the other party disconnects
- Example:
	- Professor: "Did that answer question?"
	- Student: "Yes it does!"
	- Professor: "Time to move on to the next thing in the course."
- Verification that everyone is ready to tear down
- Can be done mutually or after the communication has finished
## Devices and Protocols
- H.323
	- Used to set up, maintain, and tear down voice and video connections
	- FaceTime, Skype
		- Operate over RTP
- NetBIOS
	- Used to share files over a network
- Not really any physical devices