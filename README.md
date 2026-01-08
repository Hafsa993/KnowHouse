# KnowHouseApp Coming Soon to the Apple App Store and Google Play Store (in 14 days)!
KnowHouse Mobile App for iOS, Android, MacOS and Web


### Organization
```
├── KnowHouseApp/househo.../lib/  # Main application code

│   ├── main.dart                 # App entry point with Firebase init and routing

│   ├── firebase_options.dart     # Firebase configuration

│   ├── signin_page.dart          # Authentication screen

│   ├── models/                   # Data models (e.g., User, Task)

│   ├── providers/                # State management (e.g., UserProvider, TaskProvider)

│   ├── screens/                  # UI screens (e.g., HomeScreen, RankingScreen)

│   ├── widgets/                  # Reusable UI components (e.g., ToDoForm)

│   └── assets/                   # Static assets (images, fonts)

├── docs/                         # documentation folder

├── test/                         # tests folder

```
## About The App

KnowHouse is a mobile app for households and families to manage shared tasks and instructions together. Users can create, assign, and track tasks, earn points for completed work, and view a family leaderboard to encourage participation.
 
### Core Features

- **Real-Time Collaboration:**
All household members see updates instantly—tasks, instructions, and points sync in real time across devices using Firebase.

- **Smart Task Assignment:**
Assign ToDos to specific users or leave them open for anyone to claim. Intelligent sorting highlights tasks that match user preferences.

- **Gamified Progress & Leaderboard:**
Earn points for completing tasks, climb the family leaderboard, and motivate everyone with friendly competition.

- **Shared Household Calendar:**
Visualize all ToDos and deadlines in a unified calendar view, making planning and coordination effortless.

- **Dynamic Instructions Library:**
Create, edit, and share household instructions (like “how to do laundry”)—searchable and filterable by category.

- **Personalized Experience:**
Users can set task preferences, customize profiles, and receive tailored task suggestions.

- **Secure Authentication:**
Robust email/password sign-in with Firebase Authentication ensures privacy and data security.

- **Modern, Intuitive UI:**
Clean, responsive design with smooth navigation and engaging animations for a delightful user experience.

### Functionality

- Join or create a household group.
- Assign ToDos to users or leave unassigned for anyone to take.
- Specify reward points, category, difficulty, name, and description for each ToDo.
- Earn points by completing ToDos.
- Shared household calendar.
- Shared list of instructions (e.g., how to do laundry), with add/edit/delete.
- Leaderboard, user profiles, and customizable preferences.


### Demo Video
Register Flow and App Demo:
(Family code is hidden for security reasons)

(the demo videos can also be found as mp4 files in the img folder)



https://github.com/user-attachments/assets/35caf832-944c-465e-81e6-7a713fc1a89f




https://github.com/user-attachments/assets/a67d2d62-c475-40e8-a109-8530854366bd





### Sign In & Registration
Users can easily register or sign in with their email and password. During registration, users can join an existing family group or create a new one, and then specify their preferred household task categories for a personalized experience.

<p align="left" width="100%">
<img height="400" src="img/images for high fi/signIn.png">
<img height="400" src="img/images for high fi/Register.png">
<img height="400" src="img/images for high fi/FamChoice.png">
</p>

### Home Page
The Home Page features a dynamic leaderboard at the top, showcasing the top three users by points. Below, users see their open ToDos—tasks assigned to them but not yet accepted.
Clicking a ToDo reveals detailed information, including deadline, reward, category, and description.
Users can accept or decline tasks, with confirmation dialogs to prevent accidental actions. Declining requires a reason.
Upon accepting a task, users receive a notification confirming the task has moved to their "My ToDos" list.

<p align="left" width="100%">
<img height="400" src="img/images for high fi/HomeScreen.png">
<img height="400" src="img/images for high fi/DisplayToDo.png">
<img height="400" src="img/images for high fi/sureAcceptToDo.png">
<img height="400" src="img/images for high fi/sureDeclineToDo.png">
<img height="400" src="img/images for high fi/declineReason.png">
<img height="400" src="img/images for high fi/Screenshot_1733313265.png">
</p>

### Menu
Navigate easily between pages using the menu.

<p align="left" width="100%">
<img height="400" src="img/images for high fi/Screenshot_1733245428.png">
</p>

### My Todos
The My ToDos page displays tasks you have accepted but not yet completed, as well as those completed in the last 30 days.
Completing a ToDo triggers a small celebratory animation for positive feedback.

<p align="left" width="100%">
<img height="400" src="img/images for high fi/Screenshot_1757811490.png">
<img height="400" src="img/images for high fi/Screenshot_1733313327.png">
<img height="400" src="img/images for high fi/myToDos.png">
</p>

### House ToDos
The House ToDos page lists all tasks in the household—assigned, unassigned, or assigned to others.

- ToDo is taken: Already accepted by a user.
- Assigned to you: Assigned but not yet accepted by you.
- Take on ToDo: Unassigned tasks, open for anyone to claim.
- Users can also take over tasks from other members if they haven't been accepted yet.
  
 ToDos are clickable throughout the app for detailed views.
Adding a ToDo requires specifying category, assignee (or leave unassigned), title, reward, due date, difficulty, and description.
Users with matching category preferences are highlighted for quick assignment.

<p align="left" width="100%">
<img height="400" src="img/images for high fi/HouseToDos.png">
<img height="400" src="img/images for high fi/assignToDo.png">
<img height="400" src="img/images for high fi/Screenshot_1733314149.png">
</p>

### Instructions

The Instructions page provides a shared library of household instructions (e.g., how to do laundry).
Users can filter by category or search for specific instructions.
Instructions are clickable for detailed viewing, editing, or deletion.
The edit screen allows users to update descriptions and categories with ease.

<p align="left" width="100%">
<img height="400" src="img/images for high fi/InstructionsA2.png">
<img height="400" src="img/images for high fi/DisplayInstr.png">
<img height="400" src="img/images for high fi/editInstr.png">
</p>

### Calendar

The Calendar page displays all household ToDos by date.
Clicking a date shows the tasks due that day.
Blue dots indicate the number of ToDos per day at a glance.
A button at the bottom allows users to quickly add new ToDos.

<p align="left" width="100%">
<img height="400" src="img/images for high fi/Calendar.png">
<img height="400" src="img/images for high fi/CalendarToDos.png">
</p>

### Ranklist, Options and Profile

- Ranklist: View all users ranked by points.
- Options: Manage permissions and edit task preferences.
- Profile: View and update your profile picture (via camera or gallery, based on permissions), see your family id, preferred task categories, task distribution, and access sign out or delete account options.


<p align="left" width="100%">
<img height="400" src="img/images for high fi/Ranklist.png">
<img height="400" src="img/images for high fi/Options.png">
<img height="400" src="img/images for high fi/Screenshot_1757811511.png">
</p>
