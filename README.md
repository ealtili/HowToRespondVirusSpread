# **How to respond Malware/Virus spread?**

We are living through historical moments of humankind because of Coronavirus (COVID-19), which is pandemic now. My objective is to raise awareness of following guidelines of health authorities and point similarities about how do we respond virus spread in IT industry.

Computer viruses cause billions of dollars damage each year due to causing system failure, corrupting data, increasing maintenance costs etc.

**MyDoom** was one of the most devastating and infectious computer virus, which caused over $38 billion in damages and 25% of all emails infected in 2004.

**ILOVEYOU** was another fatal and infectious computer virus that caused over $10 billion damages and spread 10% of the computer systems all over the world. Half of those computer systems was infected within the first week in May 2000. It was so bad that governments and large corporations took their mailing system offline to prevent infection.

**Stuxnet** was the first cyberwarfare virus intended to disrupt nuclear efforts of Iran. It managed to ruin one fifth of Iran&#39;s nuclear centrifuges and that nearly 60% of infections were concentrated in Iran.

![How Stuxnet Works](https://images.squarespace-cdn.com/content/v1/555b2d4ee4b011aa38092227/1501872317673-U2DITDKAIUY67EI0FW5J/ke17ZwdGBToddI8pDm48kA0wePVlgOGM5yNNrADThjYUqsxRUqqbr1mOJYKfIPR7LoDQ9mXPOjoJoqy81S2I8N_N4V1vUb5AoIIIbLZhVYxCRW4BPu10St3TBAUQYVKc3f5rMIUspMOT17T3MGHdS3s1KwpjdUupKJDR9JNb8i8O932tY93Uq43o4DcCmt6U/stuxnet2.jpg?format=1000w)

In this post, I will try to highlight fundamentals computer malwares/viruses and how do we respond them without boring you to death with technical details. I will try to emphasize similarities of biological malwares/viruses such as Coronavirus (Covid-19). I am not expert of the biological malwares/viruses so I will present my point of view as an IT professional.

## **What is Malware/Virus?**

Malware is a malicious software intentionally designed to cause damage to a computer, server, client, or computer network. Therefore we can define Malware is the collective name for variety of malicious software like computer viruses, worms, Trojan horses, ransomware, spyware, adware, and scareware.

 ![What Is Malware](https://2.bp.blogspot.com/-yiPD0rRDsqs/Uff3KgWogBI/AAAAAAAAADk/YK5h12Ql5os/s320/malware_types.png)
 
A **computer virus** is a piece of code replicates itself by modifying other programs and spread from one host to others when it is executed. Which often results damage to the host. A zero-day virus is a previously unknown computer virus that has no known anti-virus signatures available.

A memory-resident virus (resident virus), installs itself as part of the operating system when executed, and remains in RAM until it is shut down. Like some viruses stay permanently in the body.
A non-memory-resident virus (non-resident virus), it does not remain in RAM after executed, scans for targets, infects them and then exits.

A **biological virus** is a microscopic infectious agent that replicates inside the living cells of an organism. Viruses can infect all types of life forms, people, animals, plants, microorganisms, including bacteria and archaea. **A vaccine** helps the body&#39;s immune system to recognize and fight pathogens like viruses or bacteria, which then keeps us safe from the diseases they cause.

 ![Computer Virus](https://www.cleanvirusfrompc.com/wp-content/uploads/2016/10/adware.png)

If we can call signatures as the vaccines of computer viruses. There is a similarity between COVID-19 and Zero-day virus. Because there are no known drugs or vaccines for Coronavirus (COVID-19).

## **What are signatures for Anti-virus software?**

A computer virus signature is a unique pattern of code that is for detecting and identifying specific viruses. The antivirus software scans signatures and relies on signature database of known malicious codes. This is effective but cannot defend against zero-day malware/virus, if no samples obtained signatures generated and updates distributed. Signature based method is vulnerable to obfuscation and variety of other techniques. Therefore modern Anti-Virus software use more advanced methods (Heuristic: Similarity with related viruses, Real-time behavior: Anomalies of the behavior, Sandbox and Signature).

 ![Anti-Virus Signatures](https://media.kasperskydaily.com/wp-content/uploads/sites/92/2016/10/06021417/malanov-1.png)

Signatures are outcome of the malware analysis performed by experts. Typically, there are two types:

1. **Static Malware analysis** : Static or Code Analysis is a reverse engineering which is examining each component and relationships with other resources of the binary code without executing.
2. **Dynamic Malware analysis** : Observing the behavior of the malware while it is actually running on a sandboxed environment same as the host system.

Vaccines developed by taking viruses and weakening or killing them so that they cannot reproduce. The body&#39;s immune system recognize them as a threat and destroy it. Therefore, body&#39;s immune system recognize and destroy any of the microorganisms associated with that virus it may encounter in the future.

Similar to Anti-virus software companies who are developing signatures today many pharmaceutical companies working on developing a drug or vaccine for Coronavirus (COVID-19)

## **Components, Symptoms and Lifecycle of the viruses**

Typically, a computer virus has these three components:

- **Infection Vector** : How the virus spread/propagate (Coronavirus through respiratory droplets, surface, close contact etc.)
- **Trigger:  ** Events/Conditions that will start out the malicious function/payload (incubation of the coronavirus)
- **Payload** : Data/code performs the malicious actions (Coronavirus can lead to serious illnesses, like pneumonia or death)

There are 4 stages at the lifecycle of computer virus (As an analogy to biology):

1. **Virus Entry (Dormant):** The virus has managed to access the target host. (Coronavirus gets into body)
2. **Replication (Propagation)**: The virus starts propagating, that is multiplying and replicating itself. (Coronavirus starts infecting cells, replicating itself and propagates thru respiratory droplets)
3. **Triggering**: The virus activated as a result of conditions or the events, so it starts performs the function that is intended. (the period between exposure to an infection and the appearance of the first symptoms like incubation period of coronavirus)
4. **Execution** : The virus gets to work where payload is released, and the end user will begin to notice problems such as deleted files, the system crashing or endless popups on the screen. (This is where infected person starts to see symptoms like cough, shortness of breath, fever and can lead to serious illnesses, like pneumonia or death) (this is where body fights with the virus)

## **How do we respond (Computer security incident response)?**

Employee behavior can have big impact on information security in organizations. Similar people behavior can have big impact on virus spread in these days&#39; pandemic. Therefore, employees are important part of information security chain in the organization.  Similar as people we are important part of the global effort in the security and health of loved ones and other people (especially elderly people).

In order to respond incidents, there are two level of planning&#39;s:

- Strategic Plan: Executive level, Strategic Level
- Incident Response Plan: Operational Level, Tactical Level

### **Strategic Plan**

Organization defines and communicate its executive-level strategy, priorities, direction, operation and allocate its resources to achieve its strategic objectives and asses, adjust organization&#39;s direction in response to changing environment on the whole business for information security.

Typically, at this level followings are done:

- **Pre-Evaluation** : to identify employee awareness of information security and analyze current security policy.
- **Strategic Planning:** to come up with a better awareness program, clear targets and grouping people or units to achieve goals.
- **Operative Planning** : Establish a good security practice based on internal communication, management, awareness and a training program
- **Implementation** : Commitment of the management, Commitment of employees, Communication and training for all members.
- **Post-Evaluation** : to assess the success of the planning and implementation, and to identify areas of concern.

This is similar to guidelines of WHO, CDC, ministry of health authorities. All over the world there are these awareness campaigns about importance of:

- **STAY HOME, SOCIAL DISTANCE, PERSONAL AND FACILITY HYGIENE, DO NOT STOCKPILE, ASSIST ELDERLY PEOPLE FOR THEIR NEEDS etc.**
- **QUARANTINE 14 DAYS IF YOU ARE TRAVELLING FROM ABROAD OR RISK AREA**
- **QUARANTINE YOURSELF IF YOU HAVE ANY FEVER, COUGH OR SHORTNESS OF BREATH etc.**
- **FIRST CALL YOUR PHYSICIAN OR EMERGENCY MEDICAL LINE IF YOU HAVE SYMPTOMS DO NOT GO TO MEDICAL FACILITIES BY YOUSELF LET THEM GIVE YOU THE GUIDELINES AND PICK YOU UP**

### **Incident Response Plan**

An incident response plan is a systematic approach taken by an organization to assist IT Security teams to prepare, detect, contain, respond and recover from security incidents. The goal of Incident Response Plan is to detect and react to security incidents, determine their scope and risks, respond appropriately, communicate results and risks to all stakeholders. Also reduce costs, recovery time and likelihood of the incident from reoccurring.

This is similar to local health authorities and medical facilities produce their incident handling processes based on the guidelines and plans given by governments, ministry of health, CDCs etc.

**Incident Handling Guideline** :  General guidelines and procedures to IT Security teams for dealing with security incidents. There are four key components of a security incident handling guideline:

 ![Incident Handling Guideline](https://www.researchgate.net/profile/Muhammad_Kiru/publication/330069340/figure/fig4/AS:805550992416769@1569069731725/Incident-response-plan-Computer-security-Incident-handling-guide-2012-Source-National.png)

1. **Preparation** : Establishing and training an incident response team, acquiring necessary tools, resources and applying set of controls. (Establishing and training Medical teams, testing kits, restriction on public events, facilities etc.)
2. **Detection and Analysis** : Identifying and investigating suspicious activity to confirm a security incident, prioritizing the response based on impact and coordinating notification of the incident (testing, analysis and prioritizing patients, investigating and tracking people those patients contacted with and etc.)
3. **Containment, Eradication and Recovery** : Isolating affected systems to prevent escalation, limit impact, finding root cause of the incident, removing malware, affected systems and bad actors from the environment. Restoring systems and data when a threat no longer remains. (Isolating people or areas that are affected by Coronavirus, treatment at hospitals, etc.)
4. **Post Incident Activity** : lessons learned analysis, its root cause and response, report opportunities to improve the incident response plan and future response efforts (published journals and cases that are shared between medical professionals and countries)

### **End user security awareness**

The end-user is the weakest link in the security chain and it is estimated that more than 90% of security incidents and breaches involve some kind of human error. We are the weakest link in this pandemic and virus spread from people to people. We should be following guidelines for coronavirus from health authorities.

### **Digital hygiene**

Like end-user training, digital hygiene is a fundamental principle of information security. Similar with personal hygiene, it is about establishing simple routines to minimize the risks from cyber threats. Digital hygiene practices give users another layer of protection, reducing the risk that a vulnerable node will be affected and compromise other nodes or networks. Personal and facility hygiene practices give us another layer of protection, reducing the risk that a vulnerable one will be affected and compromise others.

### **Isolation**

Containment is important before an incident overwhelms resources or increases damage. Most incidents require containment, so that is an important consideration early in the course of handling each incident. Containment provides time for developing a tailored remediation strategy. In order to slowdown virus spread and limit damages we must adhere social isolation and stay home.

[![Pale Blue Dot](https://i.pinimg.com/originals/9a/1a/83/9a1a8365a1f60a6853ca6a7046918abe.jpg)](https://youtu.be/wupToqz1e2g)
