
# Development Notes – Interactive Dashboard Project

## Author
**Rejoice Kaulumah-224061135**

---

## Overview
This project is an interactive dashboard built with **HTML, CSS, and JavaScript**, featuring:  
- Sliders with live value updates  
- Chips that can be activated, deactivated, or removed  
- Accordions for expandable content  
- Modals for pop-up interactions  
- Toast notifications for feedback  
- Tabs, dropdowns, and navigation  
- Customizable themes, fonts, and border radius  
- Clock (digital and analog)  
- Mini-calendar  
- Mood tracking  

This document highlights my **development process**, what I implemented, and the parts I found challenging.

---

## Key Features Implemented

### 1. Sliders
- Updated values in real-time next to each slider.
- Adjusted opacity of page sections based on slider input.

### 2. Chips
- Can be toggled active/inactive.
- Can be removed individually with toast notifications confirming actions.

### 3. Accordion
- Expandable and collapsible sections.
- Only one section can be open at a time.
- Dynamically changes icon based on expanded/collapsed state.

### 4. Modals
- Open and close modals programmatically.
- Clicking outside closes the modal.

### 5. Toast Notifications
- Shows feedback for user interactions like:
  - Chip activation/deactivation
  - Theme changes
  - Form submissions
  - Mood tracking

### 6. Tabs and Dropdowns
- Tabs switch content sections without page reload.
- Dropdowns toggle visibility, close when clicking outside.

### 7. Switches and Form Handling
- Toggle switches with toast feedback.
- Form submissions show confirmation and reset the form.

### 8. Table Actions
- Edit and delete table rows.
- Sort table columns with notifications.

### 9. Alerts
- Closeable alerts with types: success, warning, info.
- Alerts display as toast messages.

### 10. Progress Bars & Pagination
- Progress bars animated via JS.
- Page navigation simulated with toast messages.

### 11. Breadcrumb & Navigation
- Active navigation highlighting.
- Breadcrumb navigation shows feedback.

### 12. Customization Panel
- Theme switching: light, dark, blue, green.
- Change font size and border radius dynamically.
- Reset styles to default.
- Supports opening/closing with swipe gestures on mobile.
- Keyboard shortcut (`Escape`) closes panel.

### 13. Clock & Calendar
- Digital and analog clocks.
- Mini-calendar highlights current date.

### 14. Mood Tracking
- Select an emoji to track mood.
- Displays personalized response with toast confirmation.

---

## Challenges Faced

During development, I found the following parts particularly difficult:  

1. **Accordion functionality**  
   - Ensuring only one section is open at a time and icons update correctly.  

2. **Cards & responsive layouts**  
   - Making cards flexible and visually appealing across different screen sizes.  

3. **Responsiveness overall**  
   - Adjusting elements like sliders, modals, and calendars to fit small and large screens.  

---

## Lessons Learned

- Manipulating DOM elements dynamically requires careful planning for event listeners.  
- Modular JavaScript functions make interactive components easier to manage.  
- Toast notifications greatly improve user feedback and interaction clarity.  
- Mobile support (touch gestures) is essential for modern web applications.  

---

## Conclusion

This project provided hands-on experience with **interactive UI components**, responsive design, and user experience enhancements using vanilla JavaScript. Despite the challenges, I gained a deeper understanding of **DOM manipulation, event handling, and CSS customization**.

# GITHUB REPOSITORY LINK 
https://github.com/RejoiceKaulumah/starting-code.git
