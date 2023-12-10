# Overview

<The purpose of this Software Requirements Specification (SRS) document is to provide a comprehensive understanding of the requirements for the development of Online Doctor Appointment Application. The main purpose of this SRS is to provide deatils of the functional and non-functional requirements, change management plan, traceability links, and artifacts associated with the development process>

# Software Requirements

<The two primary sections of this section, Functional Requirements and Non-Functional Requirements, outlines the fundamental requirements for developing the Online Doctor Appointment Application>

## Functional Requirements

### <1.	User Registration and Login> 

| ID  | Requirement |
| :-------------: | :----------: |
| FR1 | <Users shall be able to create/Register accounts with unique usernames and passwords> |
| FR2 | <Users shall be able to login with valid credentials> |
| FR3 | <Users shall be required to verify their email address or phone number to complete the account creation> |
| FR4 | <Password reset and recovery options shall be available for users> |
| FR5 | <The System shall lock the accounts after multiple invalid login agttempts> |


### <2.Appointment Management>

| ID  | Requirement |
| :-------------: | :----------: |
| FR6 | <Patients shall have the capability to schedule, reschedule, and cancel appointments> |
| FR7 | <Admin shall have the authority to view, modify, or cancel appointments upon request> |
| FR8 | <Time conflicts or overlapping appointments shall trigger notifications to users> |
| FR9 | <The system shall send confirmations and reminders for scheduled appointments> |
| FR10| <Doctors shall be able to update their availability and modify appointment slots> |

### <3.Search and Selection of Doctors>

| ID  | Requirement |
| :-------------: | :----------: |
| FR11 | <Users shall be able to search for doctors based on specialties, locations, and availability.> |
| FR12 | <Real time availability updates based on doctor schedules shall be provided> |
| FR13 | <Doctor profiles shall include qualifications, experience, and patient reviews> |
| FR14 | <Filtering options shall be available for doctors based on insurance acceptance or payment methods> |
| FR15 | <Users shall have the ability to save the preferred doctors for future appointments> |

### <4.User Profile and Medical Records>

| ID  | Requirement |
| :-------------: | :----------: |
| FR16 | <Patients shall have access to view and update personal information and medical history> |
| FR17 | <Doctors shall securely access patient records during consultations> |
| FR18 | <Users shall attend the appointment from video call option> |
| FR19 | <Users shall have access to their prescription history and previous consultations> |
| FR20| <Profile updates made by both doctors and users shall reflect immediately in appointment scheduling> |

### <5.Admin and Doctor Profile>
| ID  | Requirement |
| :-------------: | :----------: |
| FR21 | <Doctors shall attend the appointment from video call option> |
| FR22 | <Doctor can change their personal details and password> |
| FR23 | <Doctors shall  view the list of appointments and update the patient medical record after consultation> |
| FR24 | <Admin shall add a new doctor and delete and edit the existing doctor's details> |
| FR25 | <Admin shall add specialist to appointment upon patient's request> |

### <6.Payment>

| ID  | Requirement |
| :-------------: | :----------: |
| FR26 | <Integration of multiple payment gateways shall facilitate seamless billing> |
| FR27 | <Patients shall have the capability to view and settle bills for appointments online> |
| FR28 | <Invoicing and receipt generation shall be provided for paid consultations or services> |
| FR29 | <Automated payment reminders shall be sent for pending bills> |
| FR30 | <Doctors shall have the capability to set consultation fees or accept insurance payments> |

### <7.Notifications and Communication>

| ID  | Requirement |
| :-------------: | :----------: |
| FR31 | <Automated notifications shall remind patients and doctors of upcoming appointments> |
| FR32 | <In app messaging or communication channels shall be available for doctor-patient interactions> |
| FR33 | <Alerts shall inform users about any changes in appointment status or availability of doctors> |
| FR34 | <Users shall have the option to enable notifications via email, SMS, or mobile app notifications> |
| FR35 | <Notifications shall be sent for prescription updates or changes in medical records> |

### <8.Feedback and Rating System>

| ID  | Requirement |
| :-------------: | :----------: |
| FR36 | <Patients shall be able to provide feedback and ratings to doctors after each consultation> |
| FR37 | <Aggregate ratings and reviews shall be displayed on doctor profiles> |
| FR38 | <Admin shall have the ability to moderate the inappropriate content in reviews > |
| FR39 | <Continuous improvement strategies based on user feedback analysis shall be implemented> |
| FR40 | <Encouragement for patients to leave feedback through incentives or reminders shall be facilitated> |





## Non-Functional Requirements

### <1.Scalability and Performance>

| ID  | Requirement |
| :-------------: | :----------: |
| NFR1 | <The system shall handle multiple users without performance degradation> |
| NFR2 | <Response time for appointment scheduling and database queries shall be within 2 seconds> |
| NFR3 | <The system shall adopt a scalable architecture which manages increased traffic during peak usage periods> |
| NFR4 | <Load balancing mechanisms shall distribute server load effectively> |
| NFR5 | <Regular performance testing shall optimize system efficiency> |

### <2.	Security and Compliance>

| ID  | Requirement |
| :-------------: | :----------: |
| NFR6 | <The system shall incorporate robust mechanisms for secure password hashing and encryption for login> |
| NFR7 | <All payment transactions should be encrypted to prevent fraudulent transactions> |
| NFR8 | <Compliance with healthcare data privacy laws (HIPAA, GDPR) shall be ensured> |
| NFR9 | <Role-based access control shall manage user privileges securely> |
| NFR10 | <Multi factor authentication feature shall be provided by the system during login to improve security> |

### <3.Accessibility>

| ID  | Requirement |
| :-------------: | :----------: |
| NFR11 | <The system shall feature a user-friendly interface with intuitive navigation> |
| NFR12 | <Adherence to accessibility standards (WCAG) for users with disabilities shall be ensured> |
| NFR13 | <Compatibility across multiple browsers and devices like desktop, mobile and tablet shall be maintained> |
| NFR14 | <Error handling and informative messages shall guide users effectively> |
| NFR15 | <UI/UX improvements based on user feedback shall be prioritized> |

### <Language and Localization>

| ID  | Requirement |
| :-------------: | :----------: |
| NFR16| <Multilingual support for users from diverse linguistic backgrounds shall be available> |
| NFR17| <Localization of the system to adapt to regional date formats, currencies  shall be implemented> |
| NFR18| <Easy language switching within the platform shall be facilitated> |
| NFR19| <Support for Right-to-Left (RTL) languages where applicable shall be provided> |
| NFR20| <Translation and localization of content and user interfaces shall be ensured> |


### <Optimization>

| ID  | Requirement |
| :-------------: | :----------: |
| NFR21 | <Caching mechanisms shall be implemented for faster data retrieval and loading times> |
| NFR22 | <Network latency shall be minimized for uniterrupted video calls during consultations> |
| NFR23 | <Database queries and indexing shall be optimized for improved response times> |
| NFR24 | <Regular system maintenance and performance tuning shall ensure efficiency> |
| NFR25 | <Bottlenecks in system resources shall be monitored and resolved> |




# Change management plan

<The techniques and approaches for integrating the software into the business operations are described in this section. It addresses topics including problem solving, adaption techniques, incorporation into the existing ecosystem, and training.
>

## How will you train people to use it?
We have customized training plan which is required for the our application to be successfully integrated. In order to identify the specific training necessary for administrators, doctors, and patients, our plan involves thorough requirements assessment for each role. To train the new users, we'll develop customized training modules that include video lectures, user guides, and workshops designed for particular roles. Additionally, we will conduct Hands-on Workshops which will provide interactive practice sessions and demonstrations for in-depth understanding of the functionalities of Online Doctor Appointment Application.

## How will you ensure it integrates within their ecosystem / software?
We will conduct compatibility testing to enable easy integration with existing  software and systems in order to find potential integration points and ensure APIs or data interfaces are working properly. We will be testing the application in a controlled environment to evaluate its integration and functionality, and we will use feedback received during the testing phase to address any integration and compatibility issues.For effective integration, we will design the system depending on individual business requirements and workflows. We will ensure that IT staff will supervise the integration processes and participate in system setup, configuration, and troubleshooting.

## How will you ensure that it any discovered issues are resolved?
To ensure the discovered issues are resolved ,We will maintain a detailed log of reported issues and their resolutions, which will serve as a repository for future reference. We will take the User feedback continuously as it is important for developing the  system upgrades, allowing for ongoing enhancements in system performance and user experience. To expedite issue reporting, specific channels such as tickets, emails, and hotlines will be developed, which allows users to report the discovered  issues.we will define escalation procedures to resolve critical issues efficiently.we will collaborate cross-functional groups, including IT, support, and development departments to ensure successful resolution of complex issues quickly.


# Traceability links

<The connections between various artifacts and the associated requirements are described in this section, which provides traceability throughout the software development life cycle. Links to Use Case, Class Diagram,Activity Diagram,Object diagram,and Window Navigation Diagram as well as their impact on specific requirements is listed.>

## User Use Case Diagram Traceability

| Artifact ID  | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| UseCase1 | User login | FR2 |
| UseCase2| View Doctor Availability | FR11 |
| UseCase3| Attend Video Call | FR11 |
| UseCase4 | Search Particular Specialist | FR11 |
| UseCase5 | Booking Appointment | FR6,FR9,FR26|
| UseCase6 | manage/cancel Appointment| FR6,FR28 |
| UseCase7 | edit password| FR16 |
| UseCase8 | make payment| FR22,FR23,FR24|

## Doctor Use Case Diagram Traceability

| Artifact ID  | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| UseCase1| Doctor login | FR2|
| UseCase2| Attend Video call | FR2|
| UseCase3 | View current appointment | FR18|
| UseCase4 | View patient medical record | FR17 |
| UseCase5| Update Patient information| FR18 |
| UseCase6| As an admin view/manage/cancel Appointment| FR7,FR28 |


## Doctor Activity Diagram Traceability

| Artifact ID  | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| 1 | Doctor login | FR2,NF6,NF10|
| 2 | Modify personal details | FR22,FR10|
| 3 | View patient medical record | FR17 |
| 4 | Update Patient information| FR18 |
| 5 | As an admin add doctor| FR24 |
| 5 | As an admin add Specialist to appointment| FR25|
| 6 | As assign a doctor incase of unavailability| TBD|
| 7 | As an admin delete/edit doctor details| FR24 |

## User Activity Diagram Traceability

| Artifact ID  | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| 1 | User login | FR2,NF6,NF10|
| 2 | book/reschedule/cancel the appointment | FR18,FR9,FR26,FR28|
| 3 | View bill| FR17 |

## Class Diagram Traceability----------

| Artifact ID  | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| 1 | Check Patient Report/Check Patient Condition methods in Doctor Class | FR17,FR23 |
| 2 | book Appointment/Make Payment/Check Doctor Availability/Cancel Appointment/View Profile methods in Patient Class|FR21,FR22,FR23,FR6,FR9,FR26,FR11,FR19,FR20,NFR7|
| 3 | View Patient Record/manage and delete appointment/assign doctor methods in Admin class| FR7,FR24,FR25 |
| 4 | generate payment details method in Payment class| FR21,FR22,FR23,FR24,FR25|


## User Window Navigation Diagram Traceability

| Artifact ID  | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| 1 | User registration | FR1,FR3 |
| 2 | User login|FR2,NF6,NF10|
| 3 | search and View list of doctors| FR11|

## Doctor Window Navigation Diagram Traceability

| Artifact ID  | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |

| 1 | User login|FR2,NF6,NF10|
| 2 | View list of appointments| FR21 |



# Software Artifacts

<This section contains a number of software artifacts associated with the project, offering an easy way to find the files or documents that support the SRS.>

* [Doctor_Usecasediagram](to_some_file.pdf)
* [patient_Usecasediagram](to_some_file.pdf)
* [Classdiagram](to_some_file.pdf)
* [Object_diagram](to_some_file.pdf)
* [Window_navigation_diagrams](to_some_file.pdf)
* [Database](to_some_file.pdf)
* [Project_Code](to_some_file.pdf)



