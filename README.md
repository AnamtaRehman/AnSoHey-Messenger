## AnSoNet_messenger
AnSoNet_messenger is a real-time messaging application built with React that enables fast, secure, and seamless communication between users. Designed with a modern, intuitive UI, it allows individuals to connect instantly and share media files.

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

### Navigation Flow
Unauthenticated Users → Login/Signup/Forgot Password. <br>
Authenticated Users → Chats List → Chat Room → Media/Search/Profile.
