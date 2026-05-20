## ToDo-LiST-Drive 

Welcome to ToDo-LiST-Drive, a simple yet powerful cloud-based task management application. This project is designed to help users organize their daily tasks efficiently with the benefit of cloud accessibility.

## Features
 
Cloud Storage: Your tasks are saved in the cloud, ensuring you can access them from any device.

Task Management: Easily add new tasks and remove completed ones to stay organized.

Clean UI: A minimalist and user-friendly interface for a distraction-free experience.

Fully Responsive: Optimized for use on both mobile devices and desktops.

## Technology Stack

Frontend: HTML5, CSS3, JavaScript.

Deployment: GitHub Pages.

## How to Use (Docker-only)
1. Clone the repository:

```bash
git clone https://github.com/Majib-39/ToDo-LiST-Drive.git
cd ToDO-LiST-Drive
```

2. Build the Docker image and run the container (bind port 3000):

```bash
docker build -t todolist-drive .
docker run --rm -p 3000:3000 todolist-drive
```

3. Open the app in your browser at http://localhost:3000. Use the Upload panel to add any file. Files are stored in the `uploads/` folder inside the container and served from `/uploads`.

##  Project Status
This project is currently undergoing more development. Future updates may include user authentication and category-based task filtering.

##  Contributing
Contributions are welcome! If you have suggestions for improvements or want to add new features, feel free to fork the repository and submit a **Pull Request**.

---
