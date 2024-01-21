#TaskUnityHub
TaskUnityHub is a web application that simplifies task management by providing a centralized hub for users to input tasks, manage lists, and collaborate seamlessly.

## Features

- Text Input: Users can send text messages specifying tasks, lists, or links.
- Link Preview: The application parses links and provides a preview, fetching details like title and description.
- Image Upload: Users can attach images relevant to the task.
- Task List: Maintains a list of tasks, each with details such as text, link, and attached images.
- Real-time Updates: Implements a real-time messaging system to instantly show when tasks are added.

## Technologies

- Frontend: HTML, CSS, JavaScript (React.js for dynamic UI).
- Backend: Node.js with Express.
- Database: MongoDB to store task details.
- Real-time Messaging: WebSocket (Socket.io for Node.js).
- File Upload: Multer for secure image uploads.
- Link Preview: Integrates Open Graph API.

## Getting Started

Follow these steps to set up and run the TaskUnityHub application locally:
1. Clone the Repository:
   ```bash
   git clone https://github.com/your-username/TaskUnityHub.git
