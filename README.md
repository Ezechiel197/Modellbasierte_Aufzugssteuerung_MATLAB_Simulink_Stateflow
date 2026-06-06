## :sparkles:**Function**
**Simulation Elevator Control System | MATLAB, Simulink und Stateflow**

This project demonstrates the complete development cycle of a 3-floor elevator control system (G, 1st, 2nd). 
It combines a physical simulation of cabin dynamics with complex discrete-event state logic and an interactive Graphical User Interface.

---

## **Core Components**

**Graphical User Interface (MATLAB GUI / HMI)**

  :white_check_mark: The system is controlled via a custom-built app that serves as the interface between the user and the simulation.
  
  :white_check_mark: Interaction: Hall call buttons ("up"/"down") on each floor and car station buttons for destination selection.
  
  :white_check_mark: Real-Time Coupling: Implementation of set_param commands to manipulate Simulink runtime variables directly from the UI.

---

## **Supervisory Control (Stateflow)**
The "brain" of the system is a hierarchical Finite State Machine (FSM) designed in Stateflow.

  :white_check_mark: State Management: Clear separation between "Travel," "Floor Stop," and "Door Operation."
  
  :white_check_mark: Request Prioritization: Intelligent queue processing to determine the most efficient path between floors.
  
  :white_check_mark: Safety Logic: Integrated limit switch logic (e.g., Endsch_EG_u, Endsch_2_o) to ensure the cabin stays within the physical boundaries of the shaft.

---

## :man_technologist: **Autor**
**Ezechiel Tonkeme**


    <img width="708" height="720" alt="image" src="https://github.com/user-attachments/assets/8a309e54-e0cf-45c0-8b4d-3917211373c2" />



  
