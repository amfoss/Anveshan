---
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
---

# Track Specific Tasks

### **TASK 05: Frontend Development**

The front end of a website is the part that users interact with directly. It involves implementing the designs to build the user interface (UI), which includes everything from the layout and design to the buttons and forms. A well-crafted front end also ensures a seamless and enjoyable user experience (UX).&#x20;

[React.js](https://react.dev/) is a popular JavaScript library used to build fast, scalable, and interactive web applications.

#### Objectives:

Create a front end for the music streaming web application, MeloFi, using React.&#x20;

* Implement a **user authentication** system (login/signup).&#x20;
* Build a **dashboard** that displays music recommendations, recently played songs, and user history.&#x20;
* Develop a **playlist section** where users can create, edit, and manage playlists by adding or removing songs.&#x20;
* Enable **search functionality** so that users can find songs, albums, or artists.

#### Outcomes:

* Acquire practical skills in building a complete front-end web application using React.&#x20;
* Develop the ability to create a responsive and interactive user interface (UI) that enhances user experience (UX).&#x20;
* Gain experience in preparing and structuring the front end to seamlessly integrate with dynamic data and APIs.&#x20;

#### Important things to note:

* Music and cover should be fetched from an API. An Example is given [here](https://github.com/kiranugale2o/free-music-api)
* **Track Hard coded Values**: Make a list of all the fields where you're using hard coded values during the front-end development. This will help you know exactly where to replace them with API data during the backend integration.&#x20;
* **Prepare for Integration**: Ensure that the front-end structure is flexible and ready to accommodate dynamic data, making the integration process smoother and more efficient.&#x20;
* This approach ensures that the front-end development is aligned with future backend integration, leading to a cohesive and functional final product.&#x20;

#### Optional Features

* Dark/Light mode toggle
* Audio controls (shuffle playlist, repeat track)
* Progress Bar: Enable users to jump to a specific point in a song.
* **Offline Mode:** Cache songs locally for playback without internet.

<mark style="color:$danger;">Deadline: 10 days</mark>

### TASK 06: Backend Development

The backend is a server-side codebase that handles and manages all your data behind the scenes.&#x20;

Now, you need to build a backend for the MeloFI app you're developing using [Flask](https://flask.palletsprojects.com/en/3.0.x/) and [REST APIs](https://www.ibm.com/topics/rest-apis). This includes implementing all the necessary endpoints, as well as managing the application logic. When used together, Flask can serve as the web framework to handle requests, while REST APIs can be implemented to manage data interactions. This combination provides a robust foundation for creating flexible and scalable backends.&#x20;

#### Objectives:

The main objectives of this task are:&#x20;

* Develop a backend using Flask and REST APIs.&#x20;
* Focus on building essential endpoints and managing application logic.&#x20;
* Upon completion, upload all the necessary files to your repository. &#x20;

#### Outcomes:

* Gain practical experience in building a backend with Flask, enhancing skills in server-side development.&#x20;
* Understand how Flask serves as a web framework for handling requests, while REST APIs facilitate data interactions.&#x20;
* Learn to implement RESTful principles for creating, reading, updating, and deleting (CRUD) operations within the application.&#x20;
* Develop the ability to manage application logic effectively, ensuring efficient data handling and processing.&#x20;

<mark style="color:$danger;">Deadline: 12 days</mark>

### **TASK 07: Mobile App Development**

#### **Overview**

The mobile application represents the user-facing part of the music streaming platform, MeloFi. It allows users to seamlessly browse, play, and manage their favorite music directly from their mobile devices. The focus of this task is to design and develop a fully functional and visually engaging **Android app** using **Kotlin** and **Jetpack Compose** (or XML UI if required). A well-built mobile frontend ensures smooth performance, intuitive navigation, and a great user experience across devices.

#### **Objectives**

1. **Develop a mobile frontend for** MeloFi **using Kotlin.**
2. **Implement a music player** that supports play, pause, next, and previous controls.
3. **Create a user authentication interface** (login and signup screens) to simulate user access.
4. **Design the main dashboard**, displaying recommended songs, recently played tracks, and playlists.
5. **Search option:** Allows users to search for songs or artists.
6. **Enable playlist management**, allowing users to view, like, and manage songs.

**Expected Screens**

1. Login / Signup Screens – For user authentication.
2. Home Screen – Displays recommended and recently played songs.
3. Player Screen – Shows song details, album art, and playback controls.
4. Playlist / Liked Songs Screen – Users can view and manage their playlists.
5. Bottom Navigation Bar – For switching between Home, Search, and Playlist sections.

#### **Important Things to Note**

* Music and cover should be fetched from an API. An Example is given [here](https://github.com/kiranugale2o/free-music-api)
* **Hard-Coded Values:** Make a list of all fields using hard-coded values (like song titles, artists, or URLs) during development. This will make it easier to replace them with real API data during backend integration.
* **Player Implementation:** Use **ExoPlayer** for managing music playback efficiently.
* **Local Storage:** Implement saving of liked songs or playlists using **Room** or **DataStore**.
* **Testing:** Ensure smooth playback and transitions between screens.

#### Optional Features

* Follow **MVVM (Mode-View-ViewModel)** for clean and maintainable code.
* Dark/Light mode toggle
* Audio controls (shuffle playlist, repeat track)
* Progress Bar: Enable users to jump to a specific point in a song.

#### **Outcomes**

By the end of this task, you should be able to:

* Acquire **hands-on experience** in building an Android app using **Kotlin** and **Jetpack Compose**.
* Understand how to design and develop a **responsive, interactive, and user-friendly mobile UI**.
* Learn to fetch and handle **dynamic data** from APIs or mock JSON files.
* Prepare the mobile frontend for **future backend integration** with Flask REST APIs.

<mark style="color:$danger;">Deadline: 12 days</mark>

### **TASK 08:  Build a Simple Shell**

Develop a basic Unix shell using C to understand how command-line interfaces work. The goal is to gain hands-on experience with systems programming by developing a command-line interface (CLI) that interacts with the operating system. This project is designed to be an introduction to the inner workings of operating systems and the role of system calls in managing hardware resources and processes.

#### **Objectives:**

1. Implement a command-line interface that displays a prompt, reads user input and executes commands.
2. **Parse user input into a command and arguments -** Break the input into a command and its arguments. This involves tokenizing the input string based on spaces and other delimiters.
3. Execute Unix commands - Use system calls like `fork()` to create a new process and `execvp()` to replace the child process’s memory space with a new program. This is the core of command execution.
4. Handle built-in commands like `cd`, `exit`, and `pwd`.
5. Implement basic error handling to manage invalid inputs.
6. Support background execution.
   * Allow commands to run in the background using `&` at the end of the command.
   * The shell should continue accepting new commands while background processes execute.
7. Implement signal handling.
   * Handle Ctrl+C to print list of all background processes started by this shell with their PIDs
   * Handle Ctrl+Z to suspend currently running foreground processes.
   * Maintain the shell prompt even after signals are sent.

#### **Outcomes:**

* Gain a fundamental understanding of how a shell works.
* Learn how to execute external programs from a C program.
* Learn about system calls and how they act as a bridge between your application and the OS kernel.
* Develop an understanding of process management in Unix.
* Get comfortable working with signals, signal handling, and background process management.
* Develop skills in C programming, debugging, and building interactive CLI applications.

#### Optional Functionalities

* **Command History**: Allow users to use arrow keys to navigate through previously entered commands.
* **Aliases**: Let users define custom command shortcuts (e.g., ll for ls -la).

#### **Resources:**

* [C Programming, A Modern Approach](https://archive.org/details/c-programming-a-modern-approach-2nd-ed-c-89-c-99-king-by)
* [What Is A Shell? - OSDev](https://wiki.osdev.org/Introduction#What_is_a_shell?)
* [Creating A Shell - OSDev](https://wiki.osdev.org/Creating_A_Shell)
* [What is a System Call? - Wiki](https://en.wikipedia.org/wiki/System_call)
* [Signals in c](https://www.geeksforgeeks.org/c/signals-c-language/)

<mark style="color:$danger;">Deadline: 7 days</mark>
