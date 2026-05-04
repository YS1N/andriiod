# Bus Transit Management App

## How to navigate through the app:

### 1) Login Screen
- Sign in with Google

<img width="200" alt="login" src="https://github.com/user-attachments/assets/39499b65-912e-4b4f-87e9-ea758cbb6b22" />

### 2) Role Selection Screen
- Select either **Admin**, **Driver** or **Passenger**
- You can enable **Remember my choice** option so the app remembers your role

<img width="200" alt="role" src="https://github.com/user-attachments/assets/73292294-a3fe-4c5f-b3b4-b53ad4730fb8" />


### 3) Administrator Panel
- As an admin you can add a new bus route
- You can enter the **Route Name**
- Also, you can add a **Support Phone Number**
- You can tap on the map to add multiple **Bus Stop** for the route
- Once you're done you can **Save Route to Firebase**

<img width="200" alt="admin" src="https://github.com/user-attachments/assets/e15d7d72-7162-4705-97b8-742deb7fe256" />

### 4) Driver Panel
- As a driver you can **Select your Route**
- You can see the **Passengers** that registered for a route and their location on the map 
- You can **Start Tracking** to share your location with the passengers
- You can **Stop Tracking** to stop sharing your location

<img width="200" alt="driver" src="https://github.com/user-attachments/assets/760f05db-42ae-4c02-a6f5-a9a2dca10c39" />


### 5) Passenger Panel
- As a passenger you can select one of the **Routes** available to register for it
- You can select which **Stop** you want the bus to pick you at
- Change your status from **Waiting** to **On My Way** or **On Bus**
- You can also **Share Location** with the driver
- You can view the **Driver's Location** on the map
- A **Proximity Alert** will trigger when the bus is within 500m of your stop

<img width="200" alt="passenger" src="https://github.com/user-attachments/assets/729c2b5d-3c60-47ff-9e58-de52d38f83b1" />

### 6) Additional Features
- Floating button that allows you to change the language **(AR/EN)**
- When turning on **Airplane Mode** or when **Battery Percentage** is low a snackbar appears
- A notification will appear when the bus is within 500m of the passenger

## Firebase Database Structure


- **rides/**: Stores live bus locations and passenger statuses.
- **routes/**: Stores static bus stop coordinates.
