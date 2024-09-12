# Nebula
**Nebula** will be a **lightweight desktop environment** designed specifically to run on top of the **ToroWM window manager** in **ToroOS**. Its goal is to provide a simple and functional graphical environment that allows users to launch applications, manage windows, and perform common operations efficiently. Although **Nebula** will be a separate project from **ToroWM**, both will be closely integrated to offer a cohesive user experience.

---

## **Project Objectives**
The main objective of **Nebula** is to create a **minimalist desktop environment** that complements the lightweight and efficient nature of **ToroWM**. Key goals include:
- Providing a simple and user-friendly graphical environment.
- Maintaining low resource consumption, optimizing performance on systems with limited resources.
- Offering essential desktop functionalities, such as window management, a workspace, and basic user interaction.
- Ensuring a **seamless integration** with **ToroWM** for window management.

---

## **Main Features of Nebula**

### **Window Management**
**Nebula** will rely on **ToroWM** to handle basic window operations such as opening, moving, resizing, and closing windows. **Nebula** will provide a graphical interface that facilitates user interaction with the window system without taking over the internal management of windows.

### **Basic Workspace**
- **Single workspace**: **Nebula** will provide a workspace where applications can open their windows.
- **Icon management**: It may include basic icon management on the desktop for quick access to essential applications.

### **Simple Taskbar**
**Nebula** will include a basic taskbar that allows the user to view open applications, switch between them, and close them as necessary.

### **Application Menu**
The application menu will be simple, allowing the user to launch available applications within **ToroOS**.

### **Basic Customization**
**Nebula** will allow basic customization of the graphical environment, such as setting a wallpaper and changing the color scheme, to suit user preferences.

---

## **Technical Architecture**

### **Independence from ToroWM**
While **Nebula** will be designed to work alongside **ToroWM**, it will remain an **independent project**, allowing it to evolve separately and potentially be used with other lightweight window managers in the future.

### **Communication with ToroWM**
**Nebula** will communicate with ToroWM using the established **IPC** protocol, allowing the desktop environment to control windows and manage user events. **Nebula** will provide a graphical interface for users to interact with **ToroWM** without compromising system efficiency.

### **Programming Language**
Like **ToroWM**, **Nebula** will be developed in **Object Pascal**, ensuring compatibility and consistency in resource management and codebase integration.

---

## **Development Plan**

### **Development Phases**
1. **Initial Phase**:
   - Develop the workspace and taskbar.
   - Implement basic communication between **Nebula** and **ToroWM**.
   - Test the integration of **Nebula** with **ToroWM** for window creation and management.

2. **Intermediate Phase**:
   - Add desktop icon functionality.
   - Develop the application menu and basic desktop tools.

3. **Final Phase**:
   - Optimize performance.
   - Implement basic customization (wallpapers, color schemes).
   - Conduct extensive testing and fine-tune the user experience.

---

# **Project Future**
The initial development of **Nebula** will focus on providing a functional and lightweight graphical environment. In the future, it could expand with more features, such as support for multiple workspaces, basic widgets, or enhanced customization. **Nebula** will be modular, allowing other developers to contribute new functionalities without compromising its core philosophy of being a **lightweight and efficient environment**.
