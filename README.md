# EthanWang
Cybersecurity Blog 

The CIA Triad

The CIA triad is a model used to guide the creation of an information security system within an organization—not to be confused with the CIA (Central Intelligence Agency). In addition to implementing new policies and strategies, it can also be used to assess cyberinfastructure.

Like the foreign intelligence service, the CIA triad is also an acronym with each character representing:

Confidentiality

Integrity

Availability

Confidentiality

Grants access to and only to authorized systems or individuals with access to sensitive information or effectively limiting access to those without permission. Essentially keeping data private.

An example of this would be a manager having more access than a lower level worker at a company. The scenario above is commonly referred to as RBAC or Role Based Access Control.

Common ways to achieve confidentiality:

Encryption — Encoding messages so only people with a key can read it

Access Controls — Select who has access and who doesn’t

Multi-Factor Authentication — An extra layer of security to make sure information is only seen by those with privilege.

Integrity

The means in keeping data unaltered. This means that data cannot be changed without detection, effectively keeping data reliable and clean.

For example, a hospital integrating a doctor’s digital signature of integrity to prove the data is legit. Without it, the data can be altered which can create damage physically.

Common ways to achieve integrity:

Hashing — converting data to a string of unreadable text of an arbitrary size through a mathmatical function—a form of cryptograhy

Digital Signatures — a cryptographic ‘fingerprint’ used to prove that data is unaltered

Certificates — Contains information about the owner such as identity and public key to verify data integrity

Availability

For the data to be useful, servers must be up and running to display such information. This means networks and systems must be up regardless of any issues or technical difficulties.

For example, a data center must remain up even during a power outage. They do this with back up generators.

Common ways to achieve availability:

Redudancy — duplicate components to ensure a system is running

Fault Tolerance — A system that still runs even when a problem occurs —a website stays up even when a server goes offline

Patching — Closing security holes

~ ZeroDayCyberJournal

Cawthra, Jennifer, et al. Data Integrity: Detecting and Responding to Ransomware and Other Destructive Events (NIST SP 1800–26A), Volume A: Executive Summary. National Cybersecurity Center of Excellence, NIST, Dec. 2020.

“Understanding CIA Triad” GeeksforGeeks, 22 Dec. 2025.

“CIA Triad.” Fortinet, n.d., accessed 21 Dec. 2025.

_____________________________________________________________________________________
