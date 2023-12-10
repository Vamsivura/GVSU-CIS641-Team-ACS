# Overview

The purpose of this Software Requirements Specification (SRS) document is to provide a comprehensive understanding of the requirements for the development of Online Doctor Appointment Application. The main purpose of this SRS is to provide deatils of the functional and non-functional requirements, change management plan, traceability links, and artifacts associated with the development process

# Software Requirements

The two primary sections of this section, Functional Requirements and Non-Functional Requirements, outlines the fundamental requirements for developing the Online Doctor Appointment Application

## Functional Requirements

### 1.	User Registration and Login 

| ID  | Requirement |
| :-------------: | :----------: |
| FR1 | <Users shall be able to create/Register accounts with unique usernames and passwords> |
| FR2 | <Users shall be able to login with valid credentials> |
| FR3 | <Users shall be required to verify their email address or phone number to complete the account creation> |
| FR4 | <Password reset and recovery options shall be available for users> |
| FR5 | <The System shall lock the accounts after multiple invalid login agttempts> |


### 2.Appointment Management

| ID  | Requirement |
| :-------------: | :----------: |
| FR6 | <Patients shall have the capability to schedule, reschedule, and cancel appointments> |
| FR7 | <Admin shall have the authority to view, modify, or cancel appointments upon request> |
| FR8 | <Time conflicts or overlapping appointments shall trigger notifications to users> |
| FR9 | <The system shall send confirmations and reminders for scheduled appointments> |
| FR10| <Doctors shall be able to update their availability and modify appointment slots> |

### 3.Search and Selection of Doctors

| ID  | Requirement |
| :-------------: | :----------: |
| FR11 | <Users shall be able to search for doctors based on specialties, locations, and availability.> |
| FR12 | <Real time availability updates based on doctor schedules shall be provided> |
| FR13 | <Doctor profiles shall include qualifications, experience, and patient reviews> |
| FR14 | <Filtering options shall be available for doctors based on insurance acceptance or payment methods> |
| FR15 | <Users shall have the ability to save the preferred doctors for future appointments> |

### 4.User Profile and Medical Records

| ID  | Requirement |
| :-------------: | :----------: |
| FR16 | <Patients shall have access to view and update personal information and medical history> |
| FR17 | <Doctors shall securely access patient records during consultations> |
| FR18 | <Users shall attend the appointment from video call option> |
| FR19 | <Users shall have access to their prescription history and previous consultations> |
| FR20 | <Profile updates made by both doctors and users shall reflect immediately in appointment scheduling> |

### 5.Admin and Doctor Profile
| ID  | Requirement |
| :-------------: | :----------: |
| FR21 | <Doctors shall attend the appointment from video call option> |
| FR22 | <Doctor can change their personal details and password> |
| FR23 | <Doctors shall  view the list of appointments and update the patient medical record after consultation> |
| FR24 | <Admin shall add a new doctor and delete and edit the existing doctor's details> |
| FR25 | <Admin shall add specialist to appointment upon patient's request> |

### 6.Payment

| ID  | Requirement |
| :-------------: | :----------: |
| FR26 | <Integration of multiple payment gateways shall facilitate seamless billing> |
| FR27 | <Patients shall have the capability to view and settle bills for appointments online> |
| FR28 | <Invoicing and receipt generation shall be provided for paid consultations or services> |
| FR29 | <Automated payment reminders shall be sent for pending bills> |
| FR30 | <Doctors shall have the capability to set consultation fees or accept insurance payments> |

### 7.Notifications and Communication

| ID  | Requirement |
| :-------------: | :----------: |
| FR31 | <Automated notifications shall remind patients and doctors of upcoming appointments> |
| FR32 | <In app messaging or communication channels shall be available for doctor-patient interactions> |
| FR33 | <Alerts shall inform users about any changes in appointment status or availability of doctors> |
| FR34 | <Users shall have the option to enable notifications via email, SMS, or mobile app notifications> |
| FR35 | <Notifications shall be sent for prescription updates or changes in medical records> |

### 8.Feedback and Rating System

| ID  | Requirement |
| :-------------: | :----------: |
| FR36 | <Patients shall be able to provide feedback and ratings to doctors after each consultation> |
| FR37 | <Aggregate ratings and reviews shall be displayed on doctor profiles> |
| FR38 | <Admin shall have the ability to moderate the inappropriate content in reviews > |
| FR39 | <Continuous improvement strategies based on user feedback analysis shall be implemented> |
| FR40 | <Encouragement for patients to leave feedback through incentives or reminders shall be facilitated> |





## Non-Functional Requirements

### 1.Scalability and Performance

| ID  | Requirement |
| :-------------: | :----------: |
| NFR1 | <The system shall handle multiple users without performance degradation> |
| NFR2 | <Response time for appointment scheduling and database queries shall be within 2 seconds> |
| NFR3 | <The system shall adopt a scalable architecture which manages increased traffic during peak usage periods> |
| NFR4 | <Load balancing mechanisms shall distribute server load effectively> |
| NFR5 | <Regular performance testing shall optimize system efficiency> |

### 2.	Security and Compliance

| ID  | Requirement |
| :-------------: | :----------: |
| NFR6 | <The system shall incorporate robust mechanisms for secure password hashing and encryption for login> |
| NFR7 | <All payment transactions should be encrypted to prevent fraudulent transactions> |
| NFR8 | <Compliance with healthcare data privacy laws (HIPAA, GDPR) shall be ensured> |
| NFR9 | <Role-based access control shall manage user privileges securely> |
| NFR10 | <Multi factor authentication feature shall be provided by the system during login to improve security> |

### 3.Accessibility

| ID  | Requirement |
| :-------------: | :----------: |
| NFR11 | <The system shall feature a user-friendly interface with intuitive navigation> |
| NFR12 | <Adherence to accessibility standards (WCAG) for users with disabilities shall be ensured> |
| NFR13 | <Compatibility across multiple browsers and devices like desktop, mobile and tablet shall be maintained> |
| NFR14 | <Error handling and informative messages after/during updates shall guide users effectively to perform correct actions> |
| NFR15 | <UI/UX improvements based on user feedback shall be prioritized> |

### 4.Language and Localization

| ID  | Requirement |
| :-------------: | :----------: |
| NFR16| <Multilingual support for users from diverse linguistic backgrounds especially for elder patients shall be available> |
| NFR17| <Localization of the system to adapt to regional date formats, currencies  shall be implemented> |
| NFR18| <Easy language switching within the platform shall be facilitated> |
| NFR19| <Support for Right-to-Left (RTL) languages where applicable shall be provided> |
| NFR20| <Translation and localization of content and user interfaces shall be ensured> |


### 5.Optimization

| ID  | Requirement |
| :-------------: | :----------: |
| NFR21 | <Caching mechanisms shall be implemented for faster data retrieval and loading times> |
| NFR22 | <Network latency shall be minimized for uniterrupted video calls during consultations> |
| NFR23 | <Database queries and indexing shall be optimized for improved response times> |
| NFR24 | <Regular system maintenance and performance tuning shall ensure efficiency> |
| NFR25 | <Bottlenecks in system resources shall be monitored and resolved> |




# Change management plan

The techniques and approaches for integrating the software into the business operations are described in this section. It addresses topics including problem solving, adaption techniques, incorporation into the existing ecosystem, and training.

## How will you train people to use it?
We have customized training plan which is required for the our application to be successfully integrated. In order to identify the specific training necessary for administrators, doctors, and patients, our plan involves thorough requirements assessment for each role. To train the new users, we'll develop customized training modules that include video lectures, user guides, and workshops designed for particular roles. Additionally, we will conduct Hands-on Workshops which will provide interactive practice sessions and demonstrations for in-depth understanding of the functionalities of Online Doctor Appointment Application.

## How will you ensure it integrates within their ecosystem / software?
We will conduct compatibility testing to enable easy integration with existing  software and systems in order to find potential integration points and ensure APIs or data interfaces are working properly. We will be testing the application in a controlled environment to evaluate its integration and functionality, and we will use feedback received during the testing phase to address any integration and compatibility issues.For effective integration, we will design the system depending on individual business requirements and workflows. We will ensure that IT staff will supervise the integration processes and participate in system setup, configuration, and troubleshooting.

## How will you ensure that it any discovered issues are resolved?
To ensure the discovered issues are resolved ,We will maintain a detailed log of reported issues and their resolutions, which will serve as a repository for future reference. We will take the User feedback continuously as it is important for developing the  system upgrades, allowing for ongoing enhancements in system performance and user experience. To expedite issue reporting, specific channels such as tickets, emails, and hotlines will be developed, which allows users to report the discovered  issues.we will define escalation procedures to resolve critical issues efficiently.we will collaborate cross-functional groups, including IT, support, and development departments to ensure successful resolution of complex issues quickly.


# Traceability links

The connections between various artifacts and the associated requirements are described in this section, which provides traceability throughout the software development life cycle. Links to Use Case, Class Diagram,Activity Diagram,Object diagram,and Window Navigation Diagram as well as their impact on specific requirements is listed.

## User Use Case Diagram Traceability

| Artifact ID  | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| UseCase1 | User login (https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/patient_Usecasediagram.pdf) | FR2,FR5 |
| UseCase2| View Doctor Availability(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/patient_Usecasediagram.pdf) | FR11,FR12,FR33,FR14 |
| UseCase3| Attend Video Call(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/patient_Usecasediagram.pdf) | FR11,FR32 |
| UseCase4 | Search Particular Specialist(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/patient_Usecasediagram.pdf) | FR11 |
| UseCase5 | Booking Appointment(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/patient_Usecasediagram.pdf) | FR6,FR9,FR26|
| UseCase6 | manage/cancel Appointment(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/patient_Usecasediagram.pdf)| FR6,FR28 |
| UseCase7 | edit password(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/patient_Usecasediagram.pdf)| FR16,FR4,FR20,FR34 |
| UseCase8 | make payment(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/patient_Usecasediagram.pdf)|FR26, FR27,FR28,FR29|

## Doctor Use Case Diagram Traceability

| Artifact ID  | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| UseCase1| Doctor login(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Doctor_Usecasediagram.pdf) | FR2,FR5 |
| UseCase2| Attend Video call (https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Doctor_Usecasediagram.pdf)| FR21,FR32,FR30|
| UseCase3 | View current appointment (https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Doctor_Usecasediagram.pdf)| FR10,FR23,FR31,FR33|
| UseCase4 | View patient medical record(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Doctor_Usecasediagram.pdf) | FR17 |
| UseCase5| Update Patient information(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Doctor_Usecasediagram.pdf)| FR23,FR35 |
| UseCase6| As an admin view/manage/cancel Appointment(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Doctor_Usecasediagram.pdf)| FR7,FR33 |


## Doctor Activity Diagram Traceability

| Artifact ID  | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| 1 | Doctor login (https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Doctor_Activity%20diagram.pdf)| FR2,FR5,NFR6,NFR10,NFR9|
| 2 | Modify personal details(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Doctor_Activity%20diagram.pdf) | FR22,FR10,FR20,FR24|
| 3 | View patient medical record(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Doctor_Activity%20diagram.pdf) | FR17 |
| 4 | Update Patient information(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Doctor_Activity%20diagram.pdf)| FR23,FR35,NFR14|
| 5 | As an admin add doctor(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Doctor_Activity%20diagram.pdf)| FR24 ,FR13|
| 5 | As an admin add Specialist to appointment(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Doctor_Activity%20diagram.pdf)| FR25,FR13|
| 6 | As assign a doctor incase of unavailability(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Doctor_Activity%20diagram.pdf)| TBD|
| 7 | As an admin delete/edit doctor details(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Doctor_Activity%20diagram.pdf)| FR24 ,NFR14|

## User Activity Diagram Traceability

| Artifact ID  | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| 1 | User login (https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/User_Activity%20diagram.pdf)| FR2,FR5,NFR6,NFR9,NFR10|
| 2 | book/reschedule/cancel the appointment(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/User_Activity%20diagram.pdf) | FR6,FR12,FR33|
| 3 | View bill(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/User_Activity%20diagram.pdf)| FR27,FR29,FR19|

## Class Diagram Traceability

| Artifact ID  | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| 1 | Doctor Class(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Classdiagram.pdf) | FR10,FR13,FR17,FR20,FR21,FR22,FR23,FR30,FR31,FR32,FR36,FR37,NFR6,NFR8,NFR9,NFR10 |
| 2 | Patient Class(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Classdiagram.pdf)|FR1,FR2,FR3,FR6,FR11,FR15,FR8,FR18,FR19,FR20,FR33,FR34,FR36,FR39,NFR1,NFR6,NFR9,NFR10,NFR11,NFR12,NFR14,NFR15,NFR16|
| 3 | Admin class(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Classdiagram.pdf)| FR7,FR24,FR25,FR38|
| 4 | Payment class(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Classdiagram.pdf)| FR14,FR26,FR29,FR30,NFR7|
| 5 | Appointment class(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Classdiagram.pdf)| FR6,FR7,FR8,FR9,FR10,FR16,FR18,FR20,FR21,FR23,FR25,FR27,FR31,FR33,NFR2|
| 6 | Specialist class(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Classdiagram.pdf)|FR25|


## User Window Navigation Diagram Traceability

| Artifact ID  | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| 1 | User registration(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/HCI-Window%20Navigation%20Diagrams/Window_navigation_diagrams.pdf) | FR1,FR3 |
| 2 | User login(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/HCI-Window%20Navigation%20Diagrams/Window_navigation_diagrams.pdf)|FR2,FR5,NFR6,NFR9,NFR10 |
| 3 | search and View list of doctors(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/HCI-Window%20Navigation%20Diagrams/Window_navigation_diagrams.pdf)| FR11,FR14 |

## Doctor Window Navigation Diagram Traceability

| Artifact ID  | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |

| 1 | User login(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/HCI-Window%20Navigation%20Diagrams/Window_navigation_diagrams.pdf)|FR2,FR5,NFR6,NFR9,NFR10|
| 2 | View list of appointments(https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/HCI-Window%20Navigation%20Diagrams/Window_navigation_diagrams.pdf)| FR23 |



# Software Artifacts

This section contains a number of software artifacts associated with the project, offering an easy way to find the files or documents that support the SRS.

* [Doctor Usecasediagram](https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Doctor_Usecasediagram.pdf)
* [patient/User Usecasediagram](https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/patient_Usecasediagram.pdf)
* [Classdiagram](https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Classdiagram.pdf)
* [Object_diagram](https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Object_diagram.pdf)
* [CRC document](https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/TeamACS_OnlineDoctorAppointment_crc.pdf)
* [Window navigation diagrams](https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/HCI-Window%20Navigation%20Diagrams/Window_navigation_diagrams.pdf)
* [Database Tables](https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/docs/Database/List_of_db_tables.pdf)
* [Project Code](https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/docs/code/OnlineDoctorAppointment.zip)
* [Doctor Activity Diagram](https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/Doctor_Activity%20diagram.pdf)
* [User Activity Diagram](https://github.com/Vamsivura/GVSU-CIS641-Team-ACS/blob/main/Artifacts/User_Activity%20diagram.pdf)




