# HealthyVichar
SERVICES

• Blood Donation: This App will use Google location services. The donors will register to the App with their blood group. (Also the App can make use of Emitra API for fetching any useful information like Address etc). The App will have a broadcast request option where any user can request for a specific blood type. The App will match the donors in the nearby vicinity (Google location) and send out a broadcast SMS to these donors to donate blood at a nearby govt hospital.  

• Book Doctor Appointments:  Here users can check the schedule of relevant govt hospital doctors and book an appointment with them. To make it easier for uneducated people having trouble to use the App, there will be an alternate IVR using which they can schedule appointments.

• Digitize Health Records:  Many a times, we travel out of station and we end up falling sick too. The doctors there ask for various medical reports and scans to be performed. Wouldn't it be very useful if we could upload these medicals records on cloud. As a result we can prevent lot of redundant tasks and speedup up medication process.

Project Description
Objective- Extending E-MITRA for healthcare. Rajasthan's e-governance ecosystem is well enhanced with frameworks like E-Mitra and Bhamashah. We wanted to take this forward and implement it as a kind of "emergency service" to connect donors of blood and their recipients in realtime. We imagined that in a locale with both rural and urban populace, one would need to extend services in such a way that they are accessible to people at any point. Thus, we chose to send requests out as SMSs, which will reach the donors without requirement of internet on the donor end. We plan to improve this by adding further useful functionalities such as allowing one to book a doctors appointment through the portal and performing analytics on the information received as well.

INSTRUCTIONS TO RUN
The entire hack was coded using HTML,CSS,JS,PHP & Python.

Some of the significant APIs used: Google Maps Geocode TwilioSMS API-Currently a trial version is being used in the POC.

In order to execute this hack locally, we should install an Apache2 server + MySQL+ PHP. There should also be a provision to set up a CRON task.

Further since we are using a trial version of Twiliofor relaying SMSs , the application will not be able to use the TwilioSMS gateway unless the phone number is verified manually. Currently we have verified 3 phone numbers manually for twillio(8867251005,9743106514,9566863955), so incase you are interested in the live demo then please contact us and we can use these 3 verified numbers to simulate a donor-requestor scenario.

This setup was prepared on a VM (Google Cloud) running on Ubuntu.

The hack is hosted live at -http://130.211.202.132. For best experience, pls use Google chrome.

PRESENTATION
https://he-s3.s3.amazon...9/c7bba59Flowchart.pptx


