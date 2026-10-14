# 🌐 NetSync — Live Inventory Synchronization Visualizer

**Making Computer Networks visible, interactive, and easier to understand.**

NetSync is a browser-based Computer Networks project that demonstrates how multiple client computers can synchronize inventory data through a centralized server. It provides an interactive network topology where users can explore packet movement, simulate network conditions, perform inventory transactions, and observe synchronization behavior in real time.

Instead of learning networking concepts only from diagrams and theory, NetSync lets you experiment with a visual simulation.

## ✨ Key Features

### 🖥️ Interactive Network Topology
- Add multiple client PCs and servers.
- Drag devices around the network canvas.
- Edit device details and manage the layout.
- Automatically arrange or reset the network layout.
- Visualize connections and animated packet movement.

### 📦 Centralized Inventory Synchronization
- View and manage products in a central inventory.
- Add products and simulate inventory transactions.
- Observe stock updates on the central server.
- Watch connected clients synchronize their inventory state.
- Follow transaction activity through the live activity feed.

### 📡 Network Simulation
- Switch between TCP and UDP simulation modes.
- Adjust network latency from **0 to 1000 ms**.
- Configure simulated packet loss from **0% to 50%**.
- Change animation speed to inspect communication flows.
- Observe packet delivery, loss, retransmission, and transaction statistics.

### 📊 Live Network Monitoring
- Monitor online devices and server counts.
- Track packet activity and synchronization status.
- Inspect network details and individual packets.
- View transaction events and status updates.

### 🎨 Responsive User Interface
- Dark, modern network-dashboard design.
- Animated connections and packet visualization.
- Interactive device cards and information panels.
- Responsive layout for desktop and mobile screens.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Styling, animations, and responsive layout |
| Vanilla JavaScript | Application logic and interactions |
| SVG | Network connections and packet visualization |
| Canvas / browser rendering | Visual network workspace and animations |

**No external framework or backend server is required to run the basic demonstration.**

## 🚀 Getting Started

### Option 1: Run Locally

1. Clone this repository:

   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Open the downloaded project folder.
3. Open `index.html` in a modern web browser.
4. Start exploring the network simulation.

### Option 2: Run with VS Code

1. Open the project folder in Visual Studio Code.
2. Open `index.html`.
3. Launch it in your browser, or use the Live Server extension if preferred.

### Option 3: Deploy with GitHub Pages

1. Upload the HTML file to your GitHub repository.
2. Open **Settings → Pages**.
3. Under the build and deployment settings, select **Deploy from a branch**.
4. Choose your main branch and the root folder.
5. Save the settings and wait for deployment.

Your repository's GitHub Pages URL will be displayed in the Pages settings once the site is published.

## 🧠 Computer Networks Concepts Demonstrated

NetSync provides a visual way to explore these concepts:

- **Client–Server Architecture:** A central server manages the authoritative inventory.
- **Network Topology:** Devices and their connections are represented visually.
- **Packet Transmission:** Animated packets illustrate communication between devices.
- **TCP and UDP:** Compare the application's simulated protocol modes.
- **Latency:** Observe how configured delays affect the simulation.
- **Packet Loss:** Experiment with simulated communication failures.
- **Retransmission:** Observe retransmission statistics in the simulation.
- **Data Synchronization:** Understand how clients receive inventory updates.
- **Network Monitoring:** Track communication and transaction activity.

These concepts are represented through a simulation; the project does not implement a complete real-world TCP/IP networking stack.

## 🔄 Example Workflow

1. A client PC initiates an inventory transaction.
2. A request is represented through animated packets.
3. The central server processes the simulated transaction.
4. The server's inventory is updated.
5. Connected clients receive simulated synchronization updates.
6. The activity feed and network statistics reflect the resulting events.

This workflow illustrates the relationship between client requests, centralized data management, and inventory synchronization.

## ⚠️ Important Limitations

NetSync is an **educational, browser-based simulation**.

- Packet transmission, latency, and packet loss are simulated in the application.
- TCP and UDP modes demonstrate selected protocol behaviors; they do not create actual TCP or UDP socket connections.
- Inventory synchronization occurs within the running browser application. It does not synchronize independent computers over a real network.
- A backend, database, and real network transport layer would be needed for production-grade multi-computer synchronization.

These limitations keep the project lightweight and easy to run while providing a useful visual learning environment.

## 🎯 Project Goals

- Make Computer Networks concepts easier to visualize.
- Connect networking theory with practical software development.
- Explore interactive UI design and JavaScript event-driven programming.
- Demonstrate centralized inventory management and synchronization logic.
- Build a foundation for future experiments with real network communication.

## 🔮 Future Improvements

Potential extensions include:

- Real-time communication between separate computers.
- A backend server and shared database.
- Visual OSI and TCP/IP layer breakdowns.
- Routing algorithm visualization.
- Network failure detection and recovery.
- More detailed packet inspection and protocol analysis.
- Advanced congestion-control demonstrations.

## 📸 Demo

Add a screenshot or a short demonstration video here after uploading it.

**Live Demo:** Add your GitHub Pages URL after deployment.

**Project Repository:** This repository.

## 👨‍💻 Author

**Mihir Trivedi**

B.Tech Information Technology Student | Aspiring Software Developer

I'm exploring the intersection of Computer Networks and web development by building interactive projects that turn theoretical concepts into practical visual experiences.

- **LinkedIn:** https://www.linkedin.com/in/mihir-trivediit/
- **GitHub:** https://github.com/trivedi-mihir

## ⭐ Support

If you find this project useful for learning Computer Networks, consider giving the repository a star ⭐ and sharing your feedback or ideas for future improvements.

**Built to learn. Designed to visualize. Created to explore.**
