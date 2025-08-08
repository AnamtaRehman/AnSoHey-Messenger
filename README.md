<img width="90" height="90" alt="Logo" src="https://github.com/user-attachments/assets/40e6649b-a9ad-4116-b941-6a1f96b5e0f4" /> <br> 
# AnSoHey-Messenger
AnSoHey-Messenger is a real-time messaging application built with React that enables fast, secure, and seamless communication between users. Designed with a modern, intuitive UI, it allows individuals to connect instantly and share media files.

## UML Diagrams & System Design:

### ER Diagram:
<img width="auto" height="400" alt="ER_Diagram" src="https://github.com/user-attachments/assets/d8fe6754-8bbb-401f-88b6-be0657996b35" /> <br>
### Sequence Diagram:
<img width="auto" height="400" alt="Sequence_Diagram" src="https://github.com/user-attachments/assets/bff7d6ee-ad1b-4405-8b36-05307d9fa835" /> <br>
### System Architecture:
<img width="auto" height="400" alt="System_Architecture" src="https://github.com/user-attachments/assets/a0ab56d3-d220-47e1-a6ea-a1a5e94d4abf" />


## Features & Pages:
### 1️. Authentication & User Management
Login Page – Email/username + password authentication. <br>
Signup Page – New user registration. <br>
Forgot Password Page – Request password reset via email. <br>
Profile Setup Page – Upload avatar/DP, set display name after signup.

### 2️. Core Chat Experience
Chats List Page - Shows all private and group conversations. <br>
Search bar to find chats or users. <br>
"New Chat" button to start a conversation. <br>
Chat Room Page (Dynamic Route: /chat/:chatId) -Real-time messages. <br>
Typing indicator. <br>
Message status (sent/delivered/read). <br>
Media sharing (images, videos, audio). <br>
Scrollable chat history. <br>
Group Chat Creation Page - Select multiple users. <br>
Set group name & avatar.

### 3️. User Profile & Settings
My Profile Page - Edit name, avatar/DP, email, password. <br>
Account Settings Page - Notification preferences. (optional) <br>
Privacy settings (e.g., read receipts on/off). (optional) <br>
Blocked users list.

### 4️. Misc.
Media Gallery Page (per chat) - View all shared images, videos, and audio files. <br>
Search Results Page - Search messages, users, or groups. <br>
Error/404 Page – For invalid URLs/paths.

## Navigation Flow
Unauthenticated Users → Login/Signup/Forgot Password. <br>
Authenticated Users → Chats List → Chat Room → Media/Search/Profile.

## Brand Palette
### 1. Primary Colors
Turquoise Blue: #00B6D6 <br>
Deep Teal: #007A91

### 2. Secondary Colors
White: #FFFFFF <br>
Light Cyan: #DFF9FB


### 3. Accent Colors
Online Green: #2ECC71 <br>
Typing Yellow: #F1C40F <br>
Error Red: #E74C3C

## Color Usage by Page
### Login / Signup Page
Background: Light Cyan (#DFF9FB) <br>
Form Cards: White (#FFFFFF) <br>
Buttons: Turquoise Blue (#00B6D6) with hover Deep Teal (#007A91) <br>
Error Text: Error Red (#E74C3C)

### Chat Page
Header Bar: Turquoise Blue (#00B6D6) <br>
Chat Background: Light Cyan (#DFF9FB) <br>
User Messages: White (#FFFFFF) with text in Deep Teal (#007A91) <br>
Friend Messages: Light Cyan (#DFF9FB) with border in Deep Teal (#007A91) <br>
Typing Indicator: Typing Yellow (#F1C40F) <br>
Online Dot: Online Green (#2ECC71) <br>

### Settings Page
Background: White (#FFFFFF) <br>
Save Button: Turquoise Blue (#00B6D6) <br>
Cancel Button: Deep Teal (#007A91) <br>
Alerts: Error Red (#E74C3C) or Typing Yellow (#F1C40F) depending on context

## Development Plan
### Phase 1 – Setup
Repo setup, environment config. <br>
Install dependencies. <br>
Routing structure. <br>
UI theme setup. <br>

### Phase 2 – Authentication
Implement signup/login. <br>
Profile setup after signup. <br>
Forgot password.

### Phase 3 – Core Chat
Chats list page.  <br>
Real-time chat rooms (Socket.IO/Firebase). <br>
Typing indicators & message status. <br>
Media upload and preview.

### Phase 4 – Extra Features
Group chats. <br>
Media gallery. <br>
Search functionality.

### Phase 5 – Final Touch
Privacy settings. <br>
Error handling. <br>
Mobile responsiveness. <br>
Deployment.
