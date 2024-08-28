Name: Bhumika Pawar
<br>
Company: CODETECH IT SOLUTIONS
<br>
ID: CT08DS5798
<br>
Domaitn: SOFTWARE DEVELOPMENT
<br>
Duration: July to Aug 2024
<br>
Mantor: Neela Santosh Kumar
<br>
# Social Networking Site

## Introduction

The Social Networking Site is a project developed using Node.js and MongoDB. It is designed to facilitate building a social network for your local community, featuring essential functionalities such as user authentication, post creation, and real-time chat. Node.js, a fast and easy-to-learn backend server language, is paired with MongoDB, a schema-less database that allows for easy scaling and flexibility.

This project includes a basic version that can be set up locally. Detailed instructions are available in the "How to install.txt" file within the source files. For any issues during setup, feel free to contact me.

## Requirements

- Node.js: [Download Node.js](https://nodejs.org/en/)
- MongoDB: [Download MongoDB](https://www.mongodb.com/download-center)
- MongoDB Compass: [Download MongoDB Compass](https://www.mongodb.com/download-center/compass)

## Features

### 1. Login and Registration
   - Secure user authentication with encrypted passwords stored in MongoDB.
   - JSON Web Token (JWT) is used for secure information transmission between client and server.
   - Users can update their profile picture and cover photo, with files stored in the Node.js server.

### 2. Post with Caption, Image, and Video
   - Users can create posts with text, images, or video, visible only to friends.
   - Features include liking, commenting, replying, and sharing posts on timelines.
   - Notifications for likes, comments, and replies are displayed on the homepage.

### 3. Search Functionality
   - Search for people, groups, and pages by name, username, or email address.
   - Results are categorized into users, pages, and groups.

### 4. Email Verification
   - Email verification is required during registration.
   - Unverified users cannot log in.

### 5. Reset Password
   - Password reset functionality via email.
   - Users receive a link to reset their password, ensuring secure access.

### 6. Create Friends
   - Send and respond to friend requests.
   - View each other’s posts once the request is accepted.

### 7. Create Pages
   - Create pages with a name, cover photo, and description.
   - Users can view and like pages, with posts appearing in their timeline.

### 8. Create Groups
   - Create groups with a name, cover photo, and description.
   - Admins manage group membership, and members can post within the group.

### 9. Realtime Chat
   - Secure real-time chat between friends using Sockets.
   - Chat messages are stored in MongoDB.

### 10. People Who Viewed Your Profile
   - View a list of people who have visited your profile, along with timestamps.

### 11. Edit and Delete Posts
   - Edit or delete your posts across the social network.
   - MongoDB ensures consistency of updates and deletions.

### 12. Load More Posts
   - Load additional posts without reloading the page.
   - The first 30 posts are fetched initially, with more posts loaded on demand.

### 13. Share Posts
   - Share posts on your timeline, pages, or groups you’ve joined.

### 14. Send Images and Videos in Chat
   - Send and preview high-quality images and videos in chats.
   - Attachments are stored in the Node.js file system.

### 15. View Post Likes and Shares
   - View a list of people who liked and shared your posts.

## Additional Features

### 1. Message Encryption
   - Encrypt chat messages during transmission for added security.

### 2. Customer Support
   - Users can create support tickets, with admin responses facilitated via a WYSIWYG editor.

### 3. Ban & Delete User
   - Admins can ban or delete users, restricting or removing their access.

### 4. Filter Bad/Abusive Words
   - Posts are checked for abusive language and prevented from saving if detected.

### 5. Adult Image Validation
   - Images are validated to prevent adult content from being uploaded.

### 6. Ban Post
   - Admins can ban posts instead of deleting them, with reasons visible to the user.

### 7. 24-Hour Stories
   - Users can upload stories that disappear after 24 hours or can be deleted earlier.

### 8. Audio Files
   - Upload audio files with posts, with waveforms displayed using “wavesurfer.”

### 9. Events
   - Create and join events, with notifications for upcoming occasions.

### 10. YouTube Links
   - Embed YouTube videos in posts by pasting the video URL.

### 11. Advertisement (Boost Post)
   - Users can boost posts for increased visibility, paying via Stripe.

### 12. Emoji Comments
   - Add emojis to comments, stored and displayed as emojis in MongoDB.

### 13. Like, Dislike, and Comment on Stories
   - Interact with stories by liking, disliking, or commenting on them.

### 14. People Nearby
   - Discover people living in your city and expand your friend circle.

### 15. Group Chat
   - Create groups with QR codes for easy joining and secure group chats.


## Installation

To clone this repository and set up the project on your local machine, use the following command:

```bash
git clone https://github.com/bhumikap1/CODETECH-Task2.git
```

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---
