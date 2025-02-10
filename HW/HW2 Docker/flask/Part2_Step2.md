# **Goal & Non-Goal**  
**Goal:** Deliver a SnickerSync diff tool that integrates humor ("snickering") into the syncing process.  
**Non-Goal:** Redesign the underlying diff/merge algorithms for performance improvements.  

### **Non-Functional Requirements**  

1. **Control Access to Configuration**  
   - **Functional Requirements**
     - PMs shall have exclusive access to an admin dashboard to define and modify snicker configuration.  
     - Only PMs can change who has access and grant admin privilages as necessary.

2. **Create a Valid Study**  
   - **Functional Requirement**
     - Randomly select a user base for study, including people from all positions, use cases, and experience level.
     - Randomly assign these users into groups, spreading the accross controls and variables.
     - Keep users within groups for the duration of the study to prevent contamination between groups.
