### **Countdown Timer Project Overview**

The **Countdown Timer project** involves creating a web application to count down to a specific date for a giveaway (like an old iPhone). The countdown timer will dynamically display the remaining time until the deal ends.

### **Project Steps**:

1. **HTML Structure**:
   - Begin by creating the `index.html` file in the setup folder.
   - Set up a **section** with classes `section` and `center`.
   - **Image Setup**:
     - Add an image related to the giveaway within an article tagged with `gift-img`.
   - **Info Section**:
     - Create another article for additional information, which includes:
       - A heading for the giveaway title (e.g., "Old iPhone Giveaway").
       - A subheading that hardcodes the deadline (e.g., "Giveaway ends on April 24, 2020, 8:00 AM").
       - A paragraph for description text (initially set to placeholder text).
   - **Countdown Timer**:
     - Set up a div with a class of `deadline`, containing:
       - Separate divs for days, hours, minutes, and seconds, each with respective headings and spans to display values.
       - Hardcode initial values (e.g., "34" days) for testing.
       - Ensure each time unit has the appropriate class for targeting in JavaScript (e.g., `days`, `hours`, `mins`, `seconds`).
