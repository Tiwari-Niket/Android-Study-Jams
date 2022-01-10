# Android-Study-Jams

Covid-19 Vaccine Finder

<b> Problem Statement: </b>

The process for scheduling a COVID-19 vaccine has been challenging across India. With ever-changing eligibility information, incredibly high demand, and a limited supply of information and resources, the vaccine rollout process has come with a growing list of difficulties. This approached us with a new COVID-19 challenge: Creating an app that would source nation-wide COVID-19 vaccine locations, detail and availability.

<b> Proposed Solution : </b>

This project proposes a “Covid-19 Vaccine Finder” that made finding vaccine locations and available appointments easier. Its features include location of vaccine centres near the user, age limit and availability of slots. It accepts user to enter their pincode and choose the date for which they want the data. This application uses Cowin's API to track vaccine upon entering the pincode.Co-WIN Public APIs allow any third-party application to access certain un-restricted information, that can be shared with its users. The project's future scope is to book slots as well.

<img width="891" alt="sample images" src="https://user-images.githubusercontent.com/91416542/148789970-ac112736-6097-411f-a9ec-14f8431df4e6.png">
    	  	
<b> Functionality & Concepts used : </b>

- The App has a very simple and interactive interface which helps the user to enter their pincode and chose the date for which they want to view the vaccine. Following are few android concepts used to achieve the functionalities in app : 
- Constraint Layout : Most of the activities in the app uses a flexible constraint layout, which is easy to handle for different screen sizes.
- Easy to use Design : Use of familiar audience EditText with hints and interactive buttons made it easier make it easier for user to enter pincode and date to check the slot without any written instructions. The app also uses App Navigation to switch between different screens.
- RecyclerView : To present the calendar we used the efficient recyclerview.
Cowin API : We are also using the Cowin API to provide user all the information they need related to vaccine
- The app clearly depicts the types of COVID-19 vaccines available (also whether its paid or free), detailed location of centre with hours of operation and age limit.

<b> Application Link & Future Scope : </b>

You can access the app here: [https://github.com/Tiwari-Niket/Android-Study-Jams.git]

The future scope shall include the tool showing walk-in options, district tracker and a link to register and schedule an appointment. If there are no slots available, users can choose to be notified by the app of when a slot opens up and then users can select a date and will be taken to the Co-WIN website / app to book their appointment.
The application will focus in a manner that it tallies and converges real time data from the government vaccination digital platform CoWIN.
