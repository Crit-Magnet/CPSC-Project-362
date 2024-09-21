# ChatterBox

> An easy-to-use chat application for college students

## Product Vision

For college students who need a simple chat application, the ChatterBox is a chat tool that is integrated with college campuses LMS, such as
Canvas, and allows easy conversations with all students. Unlike other products, our product makes it easy to connect and chat with other
students in private and group messages.

## Project Requirements

### Functional Requirements

- **Access/login page:** The application must allow users to login through their school LMS or from the ChatterBox website using their school LMS credentials.
- **Notifications:** The application must be notified of new messages (and be able to turn off in settings).
- **Image/file sharing:** The application must be able to share images and attach files to messages.

### Non-functional Requirements

- **Themes:** The users can pick a color theme for the application
- **Messaging speed:** The user must experience sending and receiving of messages in real-time (no latency).

## Use Cases

- Individuals can use this app to communicate with each other. Users are prompted to type the message they want to send to another user into a chat box and once the text is ready they can click a button to send their text to the other user.
- For image and file sharing, users can click a button to browse the type of file they want to share such as an image or a file. Once they choose the type of file users will be able to browse the specific folder, choose the image or file, and click on the send button to deliver the folder.

## User Stories

### US-1
| Requirements  | Examples & Explanations|
| ------------- |:-------------:|
| ID      | US-1    |
| Name     | Login to Service     |
| Description      |   Student accesses a login page through their school's LMS or the ChatterBox website using their school's LMS credentials   |
| Primary Actor      | Student     |
| Preconditions      | Student has access to a computer, the domain, and the internet     |
| Postconditions      | Student is successfully logs into the system     |

|   MAIN SUCCESS SCENARIO |
| --------------------- |
| 1. Student opens internet browser. 
| 2. Student accesses their school's LMS or ChatterBox website.
| 3. Student logs in to their account using their school school's LMS credentials.


### US-2
| Requirements  | Examples & Explanations|
| ------------- |:-------------:|
| ID      | US-2    |
| Name     | Notification of New Messages    |
| Description      |   Students will see when they recieve a new message, as well as the sender   |
| Primary Actor      | Student     |
| Preconditions      | Student has access to a computer, internet, and is currently logged in with their credentials     |
| Postconditions      | Student can see the notification's message as well as the sender's name     |

|   MAIN SUCCESS SCENARIO |
| --------------------- |
| 1. Student logs in to their account|
| 2. Student is notified of a new message|
| 3. Student can see the message and the sender's name|


### US-3
| Requirements  | Examples & Explanations|
| ------------- |:-------------:|
| ID      | US-3    |
| Name     | Theme Selector    |
| Description      |   Students will be able to access their settings page and customize their account's colors   |
| Primary Actor      | Student     |
| Preconditions      | Student has access to a computer, internet, and is currently logged in with their credentials     |
| Postconditions      | Student can access and change the colors on their profile     |

|   MAIN SUCCESS SCENARIO |
| --------------------- |
| 1. Student logs in to their account|
| 2. Student access a settings page|
| 3. Student can view and change the theme (colors) of their profile|
| 4. Student can save changes to keep them permanently|

## Diagram

![diagram](https://github.com/Crit-Magnet/CPSC-Project-362/blob/main/Diagram_9-20-24.png?raw=true)
