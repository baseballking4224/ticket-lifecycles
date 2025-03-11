<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
 I role-played multiple ticket scenarios. By logging in as both end users (e.g., Karen, Ken) and help desk agents (e.g., John, Jane), I demonstrated how tickets move from creation to resolution, incorporating SLA changes, department reassignment, and agent collaboration.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>focus area</h2>
- Opening tickets as different end users
<p>
- Assigning & updating ticket properties (SLA, help topic, department)
<p>
- Resolving and closing tickets

<h2>scnarios<h2>
  
-Business Critical Outage (misclassified by the user, corrected by agent)
<p>
-General Inquiry → Low priority → Quick fix
<p>  
-Personal Computer Issue from a high-level executive (CFO)

<p></p>  

Archiving the Maintenance Department
<p>
Before creating tickets, I archived an unused “Maintenance” department under Agents > Departments, simplifying our department structure.
</p>
<img width="935" alt="image" src="https://github.com/user-attachments/assets/e0efa255-1782-4dab-85ba-044a22c8c813" />
<p>
<p>
Ticket One: Business Critical Outage
</p>
User Karen logs into the End User portal, opens a new ticket describing “mobile online banking is down,” but mistakenly picks Report a Problem instead of Business Critical Outage.
<br />
<img width="513" alt="image" src="https://github.com/user-attachments/assets/c44dfddf-631d-424e-bddd-e7174af681ef" />
<p>
Agent John logs in and sees the new ticket. He changes SLA to Sev-B, corrects the Help Topic, and assigns it to the Online Banking team.  
<p>
<img width="910" alt="image" src="https://github.com/user-attachments/assets/ceb32229-76d6-4775-9413-1cace0a6df05" />
<img width="618" alt="image" src="https://github.com/user-attachments/assets/1fc91e16-6e26-4f5b-93c3-7389824e872a" />
<p>
 Agent Jane (member of Online Banking) reassigns the ticket to herself, updates Karen with the fix, and resolves the ticket. 
</p>
<img width="848" alt="image" src="https://github.com/user-attachments/assets/e14c5066-8cd7-4d67-afdf-cd2323d49855" />
<img width="617" alt="image" src="https://github.com/user-attachments/assets/ca606969-d8c5-4616-be33-1cf5ebb17caf" />
<img width="670" alt="image" src="https://github.com/user-attachments/assets/3a83923a-7476-40cb-b856-c346af55a822" />
<p></p>
Ticket Two: General Inquiry (Adobe Software Issue)
<p>
User Ken opens a ticket labeled General Inquiry about the accounting department being unable to use Adobe software.  
</p>
<img width="539" alt="image" src="https://github.com/user-attachments/assets/227308af-ce39-4c5d-a071-83f4143772ad" />
<p>
Agent John responds to request more info. Ken says only 2 people are affected, so John sets SLA to Sev-C. Ken tries a system reboot, which fixes the issue. John documents that and closes the ticket.  
</p>
<img width="896" alt="image" src="https://github.com/user-attachments/assets/9a7bb6ea-bf30-4e39-81e8-e1c36e890dc9" />
<img width="682" alt="image" src="https://github.com/user-attachments/assets/2ff22699-97e7-4044-9de4-8bae443f62fd" />
<p>
Ticket Three: Personal Computer Issue (CFO)
<p>
User Karen opens another ticket about the CFO’s laptop not powering on, selecting Personal Computer Issues.  
</p>
<img width="449" alt="image" src="https://github.com/user-attachments/assets/d60d4472-f42e-4696-8ef7-cb51c86dab95" />
<p>
Agent John sees it’s for the CFO, sets priority to Emergency and SLA to Sev-B, then assigns the ticket to himself. The root cause was a faulty charger, so once replaced, he resolves the ticket.
<p>
<img width="622" alt="image" src="https://github.com/user-attachments/assets/1a7b077d-2a73-4eae-a502-40fa0ed45162" />
<img width="757" alt="image" src="https://github.com/user-attachments/assets/f7b378ce-6eba-4fb8-bf3f-fbfee756c748" />
<img width="887" alt="image" src="https://github.com/user-attachments/assets/fd52614b-bedb-40bf-8469-4a2a8371a0dc" />
</p>
Reviewing Closed Tickets
</p>
Under the Agent Panel’s Tickets > Closed section, I verified the resolved tickets. This confirms each scenario was properly documented and closed.  
<p>
<img width="693" alt="image" src="https://github.com/user-attachments/assets/dadbc1b9-b90d-485c-b018-cf5c129b5141" />
</p>
<br />
CONCLUSION
<p>
These three ticket scenarios illustrate how osTicket handles different priorities (Business Critical vs. General Inquiry vs. Personal Computer Issue). Agents can reclassify tickets, change SLAs, or pass them to different teams as needed. Overall, osTicket’s structure and my prior configurations make for an efficient help desk workflow.
</p>
