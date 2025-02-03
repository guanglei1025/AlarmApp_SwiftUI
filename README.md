# Alarm App

## Overview
The Alarm App is a well-crafted iOS application built using SwiftUI and SwiftData, offering users a seamless way to manage their alarms. The app allows users to fetch alarms from a backend, add alarms locally with custom times and sounds, and stop the alarm once it goes off. Leveraging Swift Concurrency (async/await) ensures smooth performance, while the app runs efficiently in the foreground when alarms trigger.


## Technologies Used
- **SwiftUI**: Used to build the user interface, ensuring a declarative and responsive design for the alarm app.
- **SwiftData**: Utilized for local data storage, enabling the app to manage user preferences and alarm data efficiently.
- **Swift Concurrency (async/await)**: Implemented for asynchronous data fetching from the backend and handling alarm scheduling without blocking the main thread.
- **Backend API**: A mock or real API endpoint is used to fetch the alarm list, with alarms marked as "saved" visually when fetched.

## Screenshots
|Home|Add Alert|
|-|-|
|<img width="400" alt="Screenshot 2023-08-30 at 11 02 48 PM" src="https://github.com/user-attachments/assets/773fcf75-d990-4a46-a52f-074a70d82dad">|<img width="400" alt="Screenshot 2023-08-30 at 11 02 48 PM" src="https://github.com/user-attachments/assets/c8d72e31-ab4c-4848-9dce-b3a09056a9a3">|
