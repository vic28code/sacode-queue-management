# Project External Resources

## 🎨 Figma Prototype

## Kiosk Interface in case of Success
[Click here](https://www.figma.com/proto/I3SqsK6MvMDjZkn7mkqLnU/interfaz-kiosko?node-id=58-543&p=f&t=oxBD8jshv7nlKSfw-1&scaling=min-zoom&content-scaling=fixed&page-id=58%3A207&starting-point-node-id=58%3A543)  

The touchscreen kiosk welcomes the user to start, then lets them select a service area and choose to create or retrieve a turn. Depending on the setup, they may enter personal info or generate a turn directly. Finally, the system shows the turn number, wait time, and a QR code for tracking.  

![Screen 1](../assets/success/tk-screen1.JPG)
![Screen 2](../assets/success/tk-screen2.jpg)
![Screen 3](../assets/success/tk-screen3new.jpg)
![Screen 4](../assets/success/tk-screen4.JPG)
![Screen 5](../assets/success/tk-screen5.jpg)  

If a customer loses their turn, they can tap “I lost my turn”, enter the lost turn ID, and press “Request”. If the conditions are met, the system confirms the recovered turn, shows the new turn number, estimated wait time, and a QR code for tracking.  
![Screen 1](../assets/success/tk-screen1.JPG)
![Screen 2](../assets/success/tk-screen2.jpg)
![Screen 3](../assets/success/tk-screen3lost.jpg)
![Screen 4](../assets/success/tk-screen4recover.jpg)
![Screen 5](../assets/success/tk-screen4-1.jpg)  

## Kiosk Interface in case of Failure
[Click here](https://www.figma.com/proto/I3SqsK6MvMDjZkn7mkqLnU/interfaz-kiosko?node-id=72-218&p=f&t=eP7yZHYaWutBXm4e-1&scaling=min-zoom&content-scaling=fixed&page-id=72%3A107&starting-point-node-id=72%3A218&show-proto-sidebar=1)  
This flow shows what happens when the user leaves required fields empty during the turn generation or recovery process. After attempting to continue with incomplete information, the system displays an error screen notifying the user that there are empty fields and prompting them to try again.

![Screen 1](../assets/failure/tkf-screen1.JPG)
![Screen 2](../assets/failure/tkf-screen2.jpg)  
The flow keeps the same for both cases:  

![Screen 3 Register](../assets/failure/tkf-screen3new.jpg)
![Screen 4](../assets/failure/tkf-screen4-1.jpg)  
![Screen 3 Lost](../assets/failure/tkf-screen3lost.jpg)
![Screen 4](../assets/failure/tkf-screen7.JPG)  
This screen would be shown:  
![Screen 5](../assets/failure/tkf-screen6.JPG)  

This flow represents the scenario when the user enters invalid or incorrect information, such as an invalid ID number. When the system detects invalid data, it redirects the user to an error screen that explains the issue and offers an option to re-enter the information correctly.  
![Screen 1](../assets/failure/tkf-screen1.JPG)
![Screen 2](../assets/failure/tkf-screen2.jpg)  
The flow keeps the same for both cases:  
![Screen 3 Register](../assets/failure/tkf-screen3new.jpg)
![Screen 4](../assets/failure/tkf-screen4.JPG)  
![Screen 3 Lost](../assets/failure/tkf-screen3lost.jpg)
![Screen 4](../assets/failure/tk-screen4recover.jpg)  
This screen would be shown:  
![Screen 5](../assets/failure/tkf-screen5.JPG)  

## Administrator Pannel
[Click here](https://www.figma.com/proto/I3SqsK6MvMDjZkn7mkqLnU/interfaz-kiosko?node-id=182-42&p=f&t=8ZmT78y9XS4Yw5q3-1&scaling=contain&content-scaling=responsive&page-id=86%3A121&starting-point-node-id=182%3A42)  

This page shows the administrator’s desktop software provided with the queue management system. Through this interface, the administrator can fully manage and customize the system according to their needs: they can create and assign branches, kiosks, and screens; configure which advertising content will be displayed on customer-facing TVs; and adjust the kiosk settings to handle turn generation as desired. The software also allows them to add and manage other administrative users, assign roles and permissions, and oversee all queue operations, ensuring that the entire system is tailored to their specific business logic and customer service flow.  
![Admin Screen 1](../assets/admin/admin-screen1.JPG)
![Admin Screen 2](../assets/admin/admin-screen2.JPG)
![Admin Screen 3](../assets/admin/admin-screen3.JPG)
![Admin Screen 4](../assets/admin/admin-screen4.JPG)
![Admin Screen 5](../assets/admin/admin-screen5.JPG)  
Here we have three different flows shown, this is the first one for kiosks:  

![Admin Screen 6](../assets/admin/admin-screen6.JPG)
![Admin Screen 6-1](../assets/admin/admin-screen6-1.JPG)
![Admin Screen 6-2](../assets/admin/admin-screen6-2.JPG)  
Then we return to the branch page to see the next flow for screens:  

![Admin Screen 6 Screen](../assets/admin/admin-screen6-screen.jpg)
![Admin Screen 6 Screens](../assets/admin/admin-screen6screens.JPG)  

Then we return to the branch page to see the next flow for administrative users:  
![Admin Screen 6 Users](../assets/admin/admin-screen6-users.jpg)
![Admin Screen 6-2-2](../assets/admin/admin-screen6-2-2.JPG)
![Admin Screen 6-2-2-3](../assets/admin/admin-screen6-2-2-3.JPG)  

## TV interface
[Click here](https://www.figma.com/proto/I3SqsK6MvMDjZkn7mkqLnU/interfaz-kiosko?node-id=125-35&p=f&t=nuzWrON6DwYqYt2I-1&scaling=scale-down&content-scaling=fixed&page-id=93%3A9&starting-point-node-id=125%3A35&show-proto-sidebar=1)  

This page shows the TV display used to present the current and upcoming queue numbers to customers, alongside advertising content configured by the administrator.  

![TV Screen 1](../assets/tv/tv-screen1.JPG)  
The screens illustrate different scenarios: one where individual turns are called sequentially,  
![TV Screen 2](../assets/tv/tv-screen2.JPG)  
another where multiple turns are called simultaneously across different areas or categories depending on business logic  
![TV Screen 4](../assets/tv/tv-screen4.JPG)  
and an example of a simple error case in which the advertising content fails to load correctly.  
![TV Screen 3](../assets/tv/tv-screen3.JPG)  

## User interface QR
[Click here](https://www.figma.com/proto/I3SqsK6MvMDjZkn7mkqLnU/interfaz-kiosko?node-id=164-364&p=f&t=3hRM1usET0jUnCPn-1&scaling=scale-down&content-scaling=fixed&page-id=133%3A122&starting-point-node-id=164%3A364&show-proto-sidebar=1)  
This page shows what a user sees after scanning the QR code printed on their ticket when they take a turn. Through this view, the user can check the real-time status of their queue position at any moment, including dynamic alerts indicating whether their turn is approaching, still has a long wait time, or has already been called but they are late. It also displays an estimated time, the designated area to report to, and a list of helpful reminders to ensure they are prepared when their turn comes up, giving them full control and clear instructions throughout the process.  

