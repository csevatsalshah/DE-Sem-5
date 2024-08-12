### Efficient Doctor Patient Portal (MediBridge) Project Report

---

#### Title Page

**GUJARAT TECHNOLOGICAL UNIVERSITY**  
Chandkheda, Ahmadabad  
Affiliated

**R. N. G. PATEL INSTITUTE OF TECHNOLOGY**  
Report On  
**Efficient Doctor Patient Portal (MediBridge)**

Under subject of  
**DESIGN ENGINEERING – I – B**  
**B. E. II, Semester – IV**  
(Computer Science & Engineering Branch)

Submitted by:  
**Group ID: 493797**

| Sr. Name of Student  | Enrolment No.       |
|----------------------|----------------------|
| Nisarg Pujara        | 220840131122         |
| Vatsal Shah          | 220840131139         |
| Ridham Patel         | 220840131094         |
| Het Patel            | 230843131015         |

**Mr. Yash B. Naik**  
(Faculty Guide)

**Mr. Yash B. Naik**  
(Coordinator: Design Engg. I-B)

**Dr. Madhavi B. Desai**  
(HoD, Asso. Prof., CSE)  
**Dr. Latesh B. Chaudhari**  
(Principal)

Academic year  
(2023-2024)

---

#### Abstract

**MediBridge** is a new online portal that makes healthcare easier for patients and doctors. It provides a safe and efficient way for patients, doctors, and healthcare administrators to communicate. Patients can see their medical history, find doctors, and get hospital recommendations that suit their needs. The portal makes booking appointments simple by letting users check availability, book online, and get email reminders. It also supports important services like blood and organ donor registration and search, which helps in emergencies. With digital prescriptions and medication reminders, **MediBridge** makes it easier for patients to follow their treatment plans. The platform also allows secure online payments for medical bills, making healthcare more accessible and convenient. By offering all these features, **MediBridge** aims to create a smooth and complete healthcare system for both patients and healthcare providers.

---

#### List of Features

1. **Admin Login**
2. **User login/registration**
3. **Medical History**
4. **Doctor Search**
5. **Hospital Recommendation**
6. **Appointment availability check**
7. **Appointment booking online for date and time**
8. **Booking cancellation**
9. **Email on appointment booking**
10. **Feedback**
11. **Blood Donor Registration**
12. **Blood Donor Search (Blood Group wise)**
13. **Organ Donor Registration**
14. **Organ Donor Search**
15. **Medicine prescription and reminder (Digital Format)**
16. **Pay medical bill through App/Web**

---

#### Table of Contents

1. **Abstract**
2. **List of Figures**
3. **Acknowledgements**
4. **Introduction**
   - 1.1 Need of the system
   - 1.2 Scope of the system
   - 1.3 About system’s users
5. **Reverse Engineering**
   - 2.1 Selection and disassembling of branch-specific artefact/component
   - 2.2 Preparation of Canvases
     - 2.2.1 Mind Mapping
     - 2.2.2 AEIOU Summary Framework
     - 2.2.3 Empathy mapping canvas
     - 2.2.4 Ideation canvas
     - 2.2.5 Product development canvas
   - 2.3 Reverse Engineering Through SCAMPER
   - 2.4 Summary of the learning from Reverse Engineering
   - 2.5 Summary of findings of Prior Art Search
6. **Pre-Design & Rough Prototype**
   - 3.1 Learning Needs Matrix (LNM)
   - 3.2 LNM Canvas
   - 3.3 Rough Prototype
7. **Conceptual Plan-Layout**
8. **Conclusion**
9. **References**

---

#### Chapter 1: Introduction

**1.1 Need of the system:**

The healthcare industry faces numerous challenges in managing various operational aspects, such as patient records, appointment scheduling, doctor availability, and communication between patients and healthcare providers. Traditional methods often involve multiple disjointed systems, manual processes, and inefficient communication, leading to potential errors, delays, and suboptimal patient experiences. 

Some of the key challenges that the MediBridge Portal aims to address include:

- Inefficient appointment scheduling
- Limited patient engagement
- Operational inefficiencies
- Fragmented medical data

**1.2 Scope of the System:**

The MediBridge Portal aims to streamline and integrate various healthcare operations, including but not limited to:

- Online appointment scheduling and management
- Patient profile management and communication
- Doctor and hospital search and recommendation
- Blood and organ donor registration and search
- Digital prescription and medication reminders
- Secure online payment for medical bills

**1.3 Users of the System:**

The primary users of the MediBridge Portal include:

- Patients
- Doctors
- Healthcare administrators

---

#### Chapter 2: Reverse Engineering

**2.1 Selection and disassembling branch-specific artefact/component**

For the MediBridge Portal project, we initially examined existing healthcare management and patient portal systems to understand their strengths, limitations, and areas for improvement. We focused on dissecting popular platforms such as Practo, Zocdoc, and various hospital websites to analyze their features, user interfaces, and overall functionality.

**2.2 Preparation of Canvases**

**2.2.1 Mind Mapping**

Mind mapping is a powerful graphic technique to visually represent or outline information. It helps in organizing and understanding information faster and better. Major ideas are connected directly to the central concept, and other ideas branch out from those.

_Fig-2.1: Mind Map_

**2.2.2 AEIOU Summary Framework**

AEIOU canvas:

- **A-Activities:** Activities are goal-directed sets of actions—paths towards things people want to accomplish.
  - Booking appointments
  - Accessing medical history
  - Registering as a donor
  - Making online payments

- **E-Environment:** Environments include the entire arena where activities take place.
  - Clinics
  - Hospitals
  - Patient homes

- **I-Interactions:** Interactions are between a person and someone or something else.
  - Patient-Doctor
  - Patient-Administrator
  - Doctor-Administrator

- **O-Objects:** Objects are building blocks of the environment.
  - Medical records
  - Appointment schedules
  - Prescriptions

- **U-Users:** Users are the people whose behaviours, preferences, and needs are being observed.
  - Patients
  - Doctors
  - Healthcare administrators

_Fig-2.2: AEIOU Summary Canvas_

**2.2.3 Empathy Mapping Canvas**

**USER:**
- Patients
- Doctors
- Healthcare administrators

**STAKEHOLDER:**
- Hospital managers
- Clinic owners
- Health service investors

**ACTIVITIES:**
- Scheduling appointments
- Accessing medical records
- Providing healthcare services
- Managing patient data

**STORY BOARDING:**

_Happy Story:_
1. **Patient:** A patient uses MediBridge to easily find a doctor and book an appointment. The process is quick and efficient, providing a hassle-free experience.
2. **Doctor:** A doctor uses MediBridge to manage their appointments and access patient records effortlessly, leading to better healthcare delivery.

_Sad Story:_
1. **Patient:** A patient tries to book an appointment but faces technical issues with the portal, leading to frustration.
2. **Doctor:** A doctor encounters difficulties in accessing patient records due to slow system performance, affecting their ability to provide timely care.

_Fig-2.3: Empathy Canvas_

**2.2.4 Ideation Canvas**

An ideation canvas is a rough whiteboard where ideas can be stretched into any limits or dimensions.

**PEOPLE:**
- Patients
- Doctors
- Healthcare administrators
- Donors

**ACTIVITIES:**
- Booking appointments
- Accessing medical history
- Registering as a donor
- Making online payments

**SITUATION/CONTEXT/LOCATION:**
- Clinics
- Hospitals
- Patient homes
- Donor centers

**PROPS/TOOLS/OBJECT/EQUIPMENT:**
- MediBridge portal
- Mobile devices
- Computers
- Medical equipment

_Fig-2.4: Ideation Canvas_

**2.2.5 Product Development Canvas**

The Product Canvas is a strategic product planning tool.

**PURPOSE:**
- Enhance operational efficiency and patient experience in healthcare management through a digital platform.

**PEOPLE:**
- Patients
- Doctors
- Product development team
- Healthcare administrators
- Donors

**COMPONENTS:**
- Mobile app and web platform
- Appointment scheduling system
- User interfaces for patients and doctors
- Donor registration and search tools
- Payment gateway

**FUNCTIONS:**
- Appointment scheduling and management
- Medical history access
- Digital prescriptions
- Donor registration and search
- Online payment processing

**FEATURES:**
- User-friendly booking system
- Digital prescriptions and reminders
- Secure payment processing
- Donor registration and search

**EXPERIENCE:**
- Provide a seamless, user-friendly interface for patients and healthcare providers
- Improve the overall healthcare experience with convenient features.

**CUSTOMER REVALIDATION:**
- Regularly gather feedback from patients and doctors to ensure the product meets their needs.
- Monitor user satisfaction, adoption, and usage patterns.

**RETAIN:**
- Retain well-received features and components that enhance the healthcare management process.

_Fig-2.5: Product Development Canvas_

---

####
#### Chapter 2: Reverse Engineering (Continued)

**2.3 Reverse Engineering Through SCAMPER**

SCAMPER is a creative thinking technique that helps in exploring and improving existing products or services by looking at them from different perspectives.

- **S (Substitute):**
  - Replace traditional paper-based appointment booking with an online booking system.
  - Substitute manual medical history records with digital records accessible online.

- **C (Combine):**
  - Integrate appointment scheduling with automated reminders.
  - Combine blood and organ donor registration into a single module for ease of use.

- **A (Adapt):**
  - Adapt features from successful healthcare portals like Practo and Zocdoc to suit our specific needs.
  - Implement user feedback mechanisms to adapt the platform continuously.

- **M (Modify):**
  - Modify the user interface to be more intuitive and user-friendly.
  - Enhance security features to protect sensitive medical data.

- **P (Put to another use):**
  - Use the platform for health education by providing informative articles and resources.
  - Utilize the portal for telemedicine services in the future.

- **E (Eliminate):**
  - Eliminate unnecessary steps in the appointment booking process to streamline it.
  - Remove redundant data entry fields in user registration.

- **R (Rearrange):**
  - Rearrange the dashboard layout to highlight the most frequently used features.
  - Reorganize the workflow for better efficiency in accessing medical records and booking appointments.

**2.4 Summary of the Learning from Reverse Engineering**

Reverse engineering existing healthcare management systems provided valuable insights into their strengths and weaknesses. It highlighted the need for an integrated platform like MediBridge that addresses common pain points such as inefficient appointment scheduling, fragmented medical records, and lack of patient engagement. The SCAMPER technique further helped in identifying opportunities for innovation and improvement.

**2.5 Summary of Findings of Prior Art Search**

The prior art search revealed several existing solutions in the healthcare management domain. Key findings include:
- Many platforms focus on either appointment booking or medical records but not both.
- Few systems offer comprehensive donor registration and search functionalities.
- User experience and interface design vary significantly, affecting adoption rates.
- Security and data privacy are major concerns in existing systems.

---

#### Chapter 3: Pre-Design & Rough Prototype

**3.1 Learning Needs Matrix (LNM)**

| Learning Needs           | Sources                     | Timeline         |
|--------------------------|-----------------------------|------------------|
| Healthcare system workflow | Online resources, healthcare professionals | Week 1-2         |
| User interface design    | Online courses, design experts | Week 2-4         |
| Database management      | Online tutorials, textbooks | Week 3-5         |
| Security protocols       | Cybersecurity courses, experts | Week 4-6         |

**3.2 LNM Canvas**

_Fig-3.1: LNM Canvas_

**3.3 Rough Prototype**

A rough prototype of MediBridge was developed to visualize the system's functionality and user interface. Key components of the prototype include:
- **User Login/Registration:** Simple and secure user authentication.
- **Dashboard:** Overview of upcoming appointments, medical history, and reminders.
- **Appointment Booking:** Easy-to-use interface for scheduling, rescheduling, and canceling appointments.
- **Doctor and Hospital Search:** Filters to find doctors and hospitals based on user preferences.
- **Donor Registration and Search:** Simple forms for registering and searching blood and organ donors.
- **Digital Prescriptions and Reminders:** Interface for doctors to issue prescriptions and for patients to receive reminders.
- **Payment Gateway:** Secure payment processing for medical bills.

---

#### Chapter 4: Conceptual Plan-Layout

The conceptual plan for MediBridge includes the overall structure and layout of the platform, focusing on user experience and functionality.

_Fig-4.1: Conceptual Plan-Layout_

---

#### Chapter 5: Conclusion

**5.1 Summary**

MediBridge is designed to address critical issues in healthcare management by providing a comprehensive, integrated platform for patients, doctors, and healthcare administrators. It leverages modern technology to streamline appointment scheduling, enhance patient engagement, and improve overall healthcare delivery.

**5.2 Key Points to Remember**

- **Comprehensive Solution:** MediBridge integrates multiple healthcare services into a single platform.
- **User-Friendly Interface:** Focus on ease of use for patients and healthcare providers.
- **Enhanced Communication:** Facilitates better communication between patients and healthcare providers.
- **Secure Data Management:** Ensures the security and privacy of sensitive medical information.
- **Innovative Features:** Includes donor registration, digital prescriptions, and online payments.

---

#### References

List relevant books, articles, and online resources used for developing the MediBridge project.

---

By following the structure and content outlined above, you can create a detailed and comprehensive project report on the "Efficient Doctor Patient Portal (MediBridge)." This format ensures clarity, thoroughness, and a logical flow of information, making it accessible and informative for readers.
