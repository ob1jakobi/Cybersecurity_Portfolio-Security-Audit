# Cybersecurity Portfolio Security Audit

## Overview
Audits help ensure that security checks are made, as well as monitor for threats, risks, or vulnerabilities that can affect an organization's business continuity and critical assets.

## Background
> [!NOTE]
> This scenario is based on a fictional company

Botium Toys is a small U.S. busienss that develops and sells toys.  The business has a single physical location;
however, its online presence has grown, attracting customers in the U.S. and abroad.  Their information
technology (IT) department is under increasing pressure to support their online market worldwide.

The manager of the IT department has decided that an internal IT audit needs to be conducted.  She expresses
concerns about not having a solidified plan of action to ensure business continuity and compliance as the
business grows.  She believes an internal audit can help better secure the company's infrastructure and help
them identify and mitigate potential risks, threats, or vulnerabilities to critical assets.  The manager is also
interested in ensuring that they comply with regulations related to accepting online payments, and conducting
business in the European Union (EU).

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity
Framework (NIST CSF), establishing an audit scope and goals, and completing the assessment.  The goal of the
audit is to provide an overview of the risks the company might experience due to the current state of their
security posture.  The IT manager wants to use the audit finding as evidence to obtain approval to expand their
department.

This portfolio project task is to review the IT manager's scope, goals, and risk assessment.  Then, perform an
internal audit to complete a controls assessment and compliance checklist.

### Scenario

You received the following email from your IT manager:

> Hello!
>
> I have completed the audit scope and goals, as well as a risk assessment.  At a high level, the main goals
> and risks are as follows:
>
> **Goals:**
> * Improve Botium Toys' current security posture by aligning to industry best practices (e.g., adhere to the NIST CSF, implement concept of least permissions)
> * Provide mitigation recommendations (i.e., controls, policies, documentation), based on current risks
> * Identify compliance regulations Botium Toys must adhere to, primarily based on *where* we conduct business and *how* we accept payments.
> * To review the full report, read the **Botium Toys: Audit scope and goals** document.
>
> **Risks:**
> * Inadequate management of assets
> * Proper controls are not in place
> * May not be compliant with U.S. and international regulations and guidelines
> * Current risk score is 8/10 (high), due to a lack of controls and adherence to compliance regulations and standards
> * To review the complete list of assets and risks, read the **Botium Toys: Risk assessment** document.
>
> Thank you,
>
> Botium Toys IT Manager

#### Supporting Documents

> [!NOTE]
> The Audit Scope and Goals and the Risk Assessment documents are located in the `Supporting Documents`
> directory.

The audit needs to align current business practices with industry standards and best practices.  The audit is 
meant to provide mitigration recommendations for vulnerabilities found that are classified as "high risk," and
present an overall strategy for improving the security posture of the organization.  The audit team needs to
document their findings, provide remediation plans and efforts, and communicate with stakeholders.

#### Scope

The Botium Toys internal IT audit will assess the following:

1. Current user permissions set in the following systems:

	a. Accounting
	
	b. End-point detection
	
	c. Firewalls
	
	d. Intrusion detection system
	
	e. Security information and event management (SIEM) tool
	
2. Current implemented controls in the following systems:

	a. Accounting
	
	b. End-point detection
	
	c. Firewalls
	
	d. Intrusion detection system
	
	e. Security information and event management (SIEM) tool
	
3. Current procedures and protocols set for the following systems:

	a. Accounting
	
	b. End-point detection
	
	c. Firewalls
	
	d. Intrusion detection system
	
	e. Security information and event management (SIEM) tool
	
4. Ensure current user permissions, controls, procedures, and protocols in place align with necessary compliance
requirements.

5. Ensure current technology is accounted for (both hardware and system access).

#### Goals

The goals for Botium Toys' internal IT audit are:

1. To adhere to the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF);

2. Establish a better process for their systems to ensure they are compliant;

3. Fortify system controls;

4. Impliment the concept of least permissions when it comes to user credential management;

5. Establish their policies and procedures, which includes their playbook;

6. Ensure they are meeting complianec requirements.

### Questions to Consider

> [!IMPORTANT]
> My answers to the following questions are commented-out to provide a good-faith attempt to limit other
> persons pursuing a Google Cybersecurity Certificate from copying my work.

1. What are the biggest risks to the organization?
<!--
The biggest risks to the organization are twofold:
(a) the company does not have the necessary controls in place to protect its assets, and 
(b) the company is (likely) not in compliance with required regulations & standards protecting the privacy 
of its customers' and vendors' data.
-->
2. Which controls are most essential to implement immedately versus in the future?
<!--
First, the company should immediately implement administrative controls that align the company's policies
and procedures with regulations regarding customer data privacy.  Once the company has developed the
administrative controls that align with regulatory requirements, then the company will have the foundation
necessary to identify and implment proper technical controls (i.e., software and hardware solutions to protect
assets) and physical controls (i.e., security cameras, locks, etc.) to ensure assets are sufficiently protected.
-->
3. Which compliance regulation does Botium Toys need to adhere to in order to ensure the company keeps customer
and vendor data safe, avoid fines, etc.?
<!--
Since the scenario specifically mentions that the company is wanting to conduct business in European countries,
the company would have to become compliant with the European Union's General Data Protection Regulation (GDPR),
which involves (among other things) how companies should protect and treat personally identifiable information
(PII).
-->

#### Compliance Checklist

> [!IMPORTANT]
> The explanations for each checkbox (either checked or un-checked) has been commented-out to provide a
> good-faith attempt to limit other persons pursuing a Google Cybersecurity Certificate from copying my work.

The **compliance regulations and standards** that Botium Toys needs to adhere to are selected (i.e., related
to conducting business in the E.U., accepting online payments, user permission policies) along with
explanations.

- [ ] The Federal Energy Regulatory Commission - North American Electric Reliability Corporation (FERC-NERC)
- [x] General Data Protection Regulation (GDPR)
- [x] Payment Card Industry Data Security Standard (PCI DSS)
- [ ] The Health Insurance Portability and Accountability Act (HIPAA)
- [x] System and Organizations Controls (SOC type 1, SOC type 2)

<!--
1. FERC-NERC: Because the FERC-NERC involves regulations pertaining to organizations that work with electricity
   or that are involved with the U.S. and North American power grid, this regulation does not specifically
   apply to Botium Toys.  Based on the information provided in the background and the scenario description,
   Botium Toys is not a company that would have a potential security incident that could negatively affect the
   power grid.  Of course, depending on the type of toys manufactured, as well as electrical requirements
   involved in the manufacture of said toys, this might change; however, a toy company like a board game
   company, for example, would likely not have an impact on the power grid.
   
2. GDPR: The background specifically mentions that Botium Toys is interested in conducting business in the
   E.U., which would require the company to ensure that it is compliant with GDPR.
   
3. PCI DSS: The background implies that Botium Toys has already been conducting business in the U.S., and
   mentions that it is interested in accepting online payments in the E.U..  Because the PCI DSS is an
   international security standard meant to ensure that organizations storing, accepting, processing, and
   transmitting credit card information do so in a secure environment, Botium Toys would have to ensure that it
   is compliant with the PCI DSS.
   
4. HIPAA: Similar to the explanation for FERC-NERC, Botium Toys is a company that does not specifically work
   within the field of healthcare/patientcare.  If the toy company were to be a patient-centered company that
   worked with specific hospital groups/populations, then there may be a reason to pursue compliance with HIPAA;
   however, as the background and scenario are currently described, HIPAA compliance is not applicable.
   
5. SOC type 1 & 2: Because SOC1 and SOC2 are used to assess an organization's financial compliance and levels of
   risk (and because this also covers confidentiality, privacy, integrity, availability, security, and overall
   data safety), Botium Toys would have to ensure compliance with these regulations - especially since control
   failures in these aras can lead to fraud.
-->

#### Controls Assessment

**Current Assets:** Assets managed by the IT Department for Botium Toys include:
* On-premises equipment for in-office business needs.
* Employee equipment:
     * End-user devices (desktops/laptops, smartphones)
	 * Remote workstations
	 * Headsets
	 * Cables
	 * Keyboards
	 * Mice
	 * Docking stations
	 * Surveillance cameras
* Management of systems, software, and services:
     * Accounting
	 * Telecommunication
	 * Database
	 * Security
	 * E-commerce
	 * Inventory
* Internet access
* Internal network
* Vendor access management
* Data center hosting services
* Data retention and storage
* Badge readers
* Legacy system maintenance: end-of-life systems that require human monitoring

<table>
 <col>
 <colgroup span="4"></colgroup>
 <tr>
   <th colspan="4" scope="colgroup">Administrative Controls</th>
 </tr>
 <tr>
   <th scope="col">Control Name</th>
   <th scope="col">Control type and explanation</th>
   <th scope="col">Needs to be implemented (X)</th>
   <th scope="col">Priority</th>
 </tr>
 <tr>
   <td>Least Privilege</td>
   <td>Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the
   assets/data they need to do their jobs</td>
   <td>X</td>
   <td>High</td>
 </tr>
</table>
