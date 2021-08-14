# SNHU-CS-360

**Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?**

*The InventoryApp I developed was designed to keep an inventory and display them in a grid on a mobile device. The app needed to require a secure login process, add and remove items from the inventory, change the number of items in the inventory, and send a user notification when an item's inventory dropped to zero. The app also needed to request the user's permission to access the device's SMS text function for the notification. If the user declined permission, the app still needed to function correctly.*

**What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?**

*The app needed a login screen, a notification permission screen and at least one inventory grid screen. My design kept the user in mind by making all of the functions available on one screen without being too crowded. There is no need to keep changing screens to manage the inventory. The designs were successful because I followed the official Android Developer's guidelines in multiple areas of the app including accessibility, user interface, navigation, and visual quality.*

**How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?**

*My approach to coding the app was to implement small sections at a time and focus on the basic app functions first. Once these were completed, I could move to enhancing the functionality and adding in more features. This is a solid fundamental way to approach any coding project and I will continue to apply these skills in the future. I will also be open to new coding strategies and implement them when appropriate.*

**How did you test to ensure your code was functional? Why is this process important and what did it reveal?**

*I tested to ensure the code was functional by addressing any errors that were returned when compiling the project. Many times these pointed out syntax errors of incomplete code modules. The next way I tested was using the Android simulator to run the app on virtually. I would input various test cases and verify the app would function correctly based on my input. These methods revealed many coding bugs and other details that needed addresses throughout the project. They were great tools that helped produce the final working product.*

**Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?**

*The biggest change I had to make mid-development was changing the way a user could increase or decrease the number of items in the inventory. My initial plan was to have individual buttons to increase or decrease the number by one and also have a text field that displayed the current number where the user could edit the number freely. I struggled getting all of the buttons and the text field to update the database and found it was making too many database calls and becoming overly complex. I settled on having an EDIT button re-populate the item fields at the top of the screen and allow the user to edit the name or quantity then resubmit the item to the database. The end result works quite well and I was satisfied with the decision to change.*

**In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?**

*I feel like the EDIT function component was a successful showing of my skills and experience. I recognized that my initial idea, while good, wasn't oing to work with the amount of time and mobile coding experience I had at that point. I quickly developed a new solution and was able to successfully implement it in the project. I am proud of the fact that I found an alternative solution that still met the customer's needs and was able to deliver that experience.*
