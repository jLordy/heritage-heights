

![logo](https://i.ibb.co/bRKh0rn/hg-text.png)

# Overview 
The **Heritage Heights Ticketing System** streamlines ticket purchasing through a virtual queue system. Users select their desired tickets and are directed to a queue tab, where they can monitor their position in real time. This system reduces the hassle of on-site purchases, providing a smooth and efficient experience.![logo](https://i.ibb.co/9qf64qx/hh-logo.png)

## System Specifications  
- **Queue Management**: The system uses a virtual queue with a fixed capacity of 10. A **Queue object** ensures that users are served in a First-In, First-Out (FIFO) manner.  
- **Real-Time Updates**: A **Timeline object** periodically updates the queue, recalculating user positions and automatically removing individuals from the front.  
- **Dynamic Interaction**: The **LobbyController** updates the user interface, including enabling the Proceed button when users reach the front of the queue.  
- **"New Person" Feature**: Simulates real-world unpredictability by randomly inserting a new user into the queue between the 5th and 10th positions.

## Key Features  
- **Real-Time Tracking**: User positions in the queue are updated dynamically on the GUI.  
- **Efficient Queue Management**: Built with a circular array for optimal space utilization, supporting frequent additions and removals.  
- **Interactive Buttons**: Provides intuitive controls for navigation, including transitioning between scenes (e.g., home, rides, and promos).  
- **Event Handling**: Robust methods like `handleActionButton` ensure smooth transitions and confirm actions using a helper class, `AlertHandler`.

## Implementation Highlights  
- **Queue Operations**:  
  - **Enqueue**: Adds users to the rear of the queue.  
  - **Dequeue**: Removes users from the front and updates positions.  
  - **Random Enqueue**: Introduces a "New Person" into the queue at a calculated random position.  
- **Dynamic Updates**: The Timeline triggers updates every second, ensuring the system remains responsive and synchronized.  
- **Graphical Interface**: Built using JavaFX, with clear visual feedback for user actions and queue status.

## Conclusion  
The **Heritage Heights Ticketing System** delivers an efficient and user-friendly solution for ticket purchasing. By integrating real-time updates, innovative queue behavior, and robust user interaction features, the system provides a seamless and engaging experience. Its thoughtful design, adaptability, and technical excellence make it a reliable tool for handling high-demand ticketing scenarios.

**Thank you for exploring the system!**
