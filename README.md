# LingotoReact
React Native Application for the Lingoto Project

## Developer Setup
- Install Node 8+
- Execute `npm install` from the project directory

## Start application on local server
- Execute `npm start` from the project directory

## Running on Mobile Device
Install the Expo client app on your iOS or Android phone and connect to the same wireless network as your computer. On Android, use the Expo app to scan the QR code from your terminal to open your project. On iOS, follow on-screen instructions to get a link.

## TODO List:
1. Create main page with teach & learn buttons.
2. Create teach page
    - Select video or image
    - input box for translation
        - autocomplete for foreign characters
        - digital keyboard for selected language
    - Invite option (enter email or multiple email addresses to invite to lingoto app)
    - Student list (option to select 1 or more students to send lesson to, default to previous entry)
3. Create learn page
    - If teacher invited student, provide two options
        - Translation request
            - Select video or image
            - "Please translate into [drop down box for language]"
                - "Please translate into ... " will fade into translated language 
        - Lesson plan
            - Opens to lesson plan if only one teacher invited student
            - If more than one teacher invited student, provide teacher list for student to select from
