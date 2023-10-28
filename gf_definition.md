# How to recognize a good faith cybersecurity researcher as opposed to a computer criminal

## A security researcher is someone who:

1. Finds a vulnerability in the course of other non-security research and development, such as a programmer who finds a bug in open-source code, for whom this may be the only vulnerability they ever find.

2. Conducts general cybersecurity research, such as emerging threats and hacker activity, but whose primary job isn't finding vulnerabilities.

3. Hunts for vulnerabilities as a major or primary focus of their job.


## Good faith behavior includes:

1. Reports their findings to a vulnerability owner or to the public.
  
1. Goes above and beyond mere discovery, including providing information for reproducing and mitigating the vulnerability.
    
1. Does not intentionally damage property in the pursuit of discovering or validating vulnerabilities (viewing, copying, or disseminating data is not damage).

   a. Publicly disclosing data that is reasonably likely to harm the public interest and that was intended to be protected prior to the vulnerability being discovered, is not considered good faith behavior (even if all other tenets in this document are followed).
    
1. Designs and carries out their pursuit of vulnerabilities in such a manner as to avoid, as best as possible, any intentional harm to individuals or the public.
   
1. Follows local laws to the best of their ability and knowledge, including reporting and paying taxes on their income to any relevant taxation agencies.
    
1. If a vulnerability owner has been nonresponsive, uses the common best practice of waiting at least:
   
   a. 30 days to publicly disclose a vulnerability that could harm human health or life in critical infrastructure.

   b. 60 days to publicly disclose a software or firmware vulnerability.

   c. 180 days to publicly disclose a physical vulnerability (e.g. one found in a physical lock or the          firmware/hardware of an electronic access control system).

1. In the event of no response from a vulnerability owner during the waiting period, the good faith vulnerability researcher:

    a. should disclose immediately to an escrow partner if it is a critical infrastructure vulnerability, and disclosure should be as close in time as possible to notification of the vulnerability owner.

     b. may disclose an IT/OT or physical vulnerability to an escrow partner before public disclosure, as part of good faith security research practice.
   
1. In the event of a response that establishes a line of communication from a vulnerability, the good faith vulnerability researcher:

     a. Does not disclose a reported vulnerability before the agreed-upon deadline established in prior communications with the vulnerability owner so long as the vulnerability owner continues to engage with the researcher.
   
1. (When the situation arises) Prioritizes the safety and health of others over financial gain and immediately reports to a relevant escrow partner, if an ICS/SCADA vulnerability found that is or could be actively harming people physically.
    
1. Does not withhold the details of a vulnerability in demand for payment from a vulnerability owner.  If a vulnerability owner refuses to pay or does not wish disclosure to them, makes one of three choices:
    
    a. publicly disclosing the vulnerability without intention of profit,
    
    b. disclosing to a relevant escrow partner for assistance in disclosure without intention of profit,

    c. or publicly disclosing the vulnerability without intention of profit, as publicly or privately acknowledged by the escrow partner.
   
### Instances where good faith vulnerability research disclosures have advanced public safety and security:

    a. "Will Your Airliner Get Hacked? Meet the people who are making sure it won’t." Source: https://www.smithsonianmag.com/air-space-magazine/will-your-airliner-get-hacked-180976752/

    b. "BadAlloc vulnerability affects BlackBerry QNX Real Time Operating System" Source: https://www.securitymagazine.com/articles/95888-badalloc-vulnerability-affects-blackberry-qnx-real-time-operating-system

    c. "CISA platform helps agencies uncover more than 1,000 cyber vulnerabilities" Source: https://federalnewsnetwork.com/cybersecurity/2023/08/cisa-platform-helps-agencies-uncover-more-than-1000-cyber-vulnerabilities/ 

### Definitions & Assumptions

* Critical Infrastructure: impacts the physical and digital infrastructure that society relies on, e.g.: water and wastewater; electricity; oil and gas; telecommunications; finance; health; government; sectors that rely on Industrial Control Systems (ICS) and SCADA systems, common third party / supply chain software and applications.

* Good Faith: "having honest or sincere intentions" to abide by the communications they have established with vulnerability owners and who understand the impact of their actions on the public while trying to prevent harm.
  
* Escrow partner: a government or private organization that can mediate between a researcher and a vulnerability owner, and has the ability to shield the researcher's identity as well as balance the need for a public response to critical infrastructure vulnerabiities and other vulnerabilities.

* Vulnerability owner: whoever owns the system in which the vulnerability has been found. May be a government entity, a private company, or other organization or person.

* Days before disclosure: The number of days to wait before disclosure is based on two things: first, an average of the lengths of time published by organizations such as Google’s Project Zero, US CISA, and vulnerability reporting mechanisms for such companies as Splunk, Symantec, Master Lock, and more; and, second, what would be commonly seen as a reasonable waiting time amongst cybersecurity researchers and vulnerability owners (at least according to their documentation).
