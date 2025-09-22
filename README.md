# Integration and Automation Flow: OnceHub → Zapier → Keap → Teachworks

---

## 📌 Project Description

This project demonstrates an **automation flow between OnceHub, Zapier, Keap (formerly Infusionsoft), and Teachworks** to streamline scheduling, CRM management, and education management.  
It captures **OnceHub booking events**, passes them through **Zapier Zaps**, and syncs customer/student data into **Keap CRM** for tagging and automation. The data is then pushed to **Teachworks** to manage classes, enrollments, and lesson tracking.  

---

## ⚙️ Tools and Platforms Used

- **OnceHub** → Online scheduling tool for customer/student appointments.  
- **Zapier** → Middleware automation platform connecting OnceHub, Keap, and Teachworks.  
- **Keap (Infusionsoft)** → CRM system for customer records, tagging, and automation workflows.  
- **Teachworks** → Education management system for lessons, scheduling, and student records.  

---

## 🔄 Integration Workflow

1. **Customer Books via OnceHub**  
   - Booking creates an event with customer/student details (name, email, service booked).  

2. **Zapier Automation**  
   - Zapier captures the OnceHub booking event.  
   - Key data extracted: customer name, email, booked service, time slot.  
   - Data is transformed and mapped into Keap and Teachworks fields.  

3. **Keap CRM Actions**  
   - Contact is created or updated in Keap.  
   - Appropriate tags applied (e.g., *New Student*, *Booked Service X*).  
   - Automation campaigns triggered (reminders, onboarding emails, follow-ups).  

4. **Teachworks Actions**  
   - Student profile is created or updated in Teachworks.  
   - Booking data mapped to lessons/schedules.  
   - Ensures accurate record-keeping for classes and attendance.  

---

## 📸 Screenshots & Walkthrough

### Zapier Setup
![Zapier Setup](https://i.imgur.com/Duo5YjN.png)

### OnceHub → Zapier Trigger
![OnceHub Trigger](https://i.imgur.com/1l2Vn6f.png)

### OnceHub Booking Confirmation
![OnceHub Booking Confirmation](https://i.imgur.com/Upd0210.png)

### OnceHub Upcoming Meetings
![OnceHub Upcoming Meetings](https://i.imgur.com/fGihNZW.png)

### Keap → Zapier Action
![Keap Zapier Action](https://i.imgur.com/cpYCBHd.png)

### Keap Contact Record Created
![Keap Contact Record](https://i.imgur.com/eIy2uo1.png)

### Keap Automation Triggered (Follow-up & Nurturing)
![Keap Automation Trigger](https://i.imgur.com/bUgBNey.png)

### Teachworks → Zapier Action
![Teachworks Zapier Action](https://i.imgur.com/1izxqAO.png)

### Teachworks Calendar Lesson and Schedule Created
![Teachworks Lesson Created](https://i.imgur.com/o55WbA2.png)

### Teachworks Calendar List View
![Teachworks Calendar List](https://i.imgur.com/UWN3Klr.png)

---

## 🗂️ Integration Overview
Here’s the list of all **integration and automation flows** I’ve created and maintained for this client.  
![Integration Overview](https://i.imgur.com/K80Ovd8.png)

---

## ⚡ Reliability and Dependencies
I ensured that all Zaps are set up correctly since many are interconnected and trigger based on the success of other Zaps.  
![Zap Dependency Overview](https://i.imgur.com/tlv5c4d.png)

---

## 🛠️ Troubleshooting Example
[▶️ Watch Zap troubleshooting explanation (Loom Video)](https://www.loom.com/share/a4d72c1b0ca7475ab645f356c6b0dde6?sid=697a5a63-aada-42a8-924c-a6e2625b1fbb)

---

## ✅ Key Benefits

- Automates customer/student syncing between **OnceHub, Keap, and Teachworks**.  
- Eliminates manual data entry.  
- Ensures students are properly onboarded and enrolled in the right schedules.  
- Scales for multiple services, courses, or recurring lessons.  

---

## 🚀 How to Reproduce

1. Set up a **OnceHub account** with at least one booking form.  
2. Create a **Zapier account** and connect OnceHub + Keap + Teachworks.  
3. Build a Zap:  
   - **Trigger** → "New Booking in OnceHub"  
   - **Action 1** → "Create/Update Contact in Keap"  
   - **Action 2** → "Create/Update Student in Teachworks"  
4. Map OnceHub booking fields (email, name, service) to Keap and Teachworks.  
5. Test the Zap and confirm data flows correctly.  
6. Set up **Keap automation campaigns** (e.g., onboarding, reminders, class notifications).  

---

✨ *This project is part of my Marketing Technology portfolio, showcasing real-world CRM and education automation use cases.*  
