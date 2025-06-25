## 3-Month Engineering Documentation Plan

###  Month 1: Design & Planning

**Week 1: Project Start & Requirements Getting**

* **Objective**: Know the project scope, goals, and requirements needed.
* **Tasks**:

  * Know project schedule and goals (reading the rules).
  * Identify key things: Raspberry Pi, batteries (18650), camera, motor controller, distance sensors, servo motor.
  * Get software requirements: Python libraries, dependencies, and development tools.

**Week 2: System Architecture Design**

* **Objective**: Develop a system architecture.
* **Tasks**:

  * Develop block diagrams illustrating component interaction. (used MIRO)
  * Develop data flow between sensors, Raspberry Pi. (It was hard, especially with the TCS color sensor)
  * Know communication protocols (e.g., I2C, GPIO). (I had a lot of work with the PINS because I had to use multiple I2Cs)

**Week 3: Mechanical Design**

* **Objective**: Design the physical part of the robot.
* **Tasks**:

  * Design CAD models for wooden and plastic base.
  * Develop movable solutions for electronics and sensors. [so they can be easily detached]
* Plan cable management and power distribution. (but it didn't take much time)

**Week 4: Electrical Design**

* **Objective**: Electrical system design.
* **Tasks**:

  * Create wiring diagrams for motor controllers, sensors, and power.
  * Determine power requirements and battery capacity.
  * Design circuit protection systems (e.g., fuses, voltage regulators).

---

###  Month 2: Development & Integration

**Week 5: Hardware Assembly**

* **Objective**: Create robot hardware components.
* **Tasks**:

* Create and build the wood and plastic base.
* Add and wire the motor controller, Raspberry Pi, servo motor, and sensors.
* Add the power wires and battery.

**Week 6: Part 1 Software Development**

* **Goal**: Develop the initial software components.
* **Tasks**:

  * Setup the development environment on the Raspberry Pi.
* Implement basic motor control and servo steering features. (can be viewed in Motor.py, and Steer.py)
* Write sensor reading scripts for distance sensors, as well as camera. (specifically for the color sensor.)

**Week 7: Software Development - Part 2**

* **Objective**: Develop obstacle avoidance and navigation algorithms.
* **Activities**:

  * Integrate sensor data to establish real-time obstacle detection.
  * Develop path planning algorithms (e.g., reactive navigation).
* Apply motor control logic from sensor inputs.

**Week 8: System Integration**

* **Goal**: Integrate hardware and software units.
* **Tasks**:

  * Test each unit for functionality.
  * Integrate software units with hardware.

---

###  Month 3: Testing, Optimization & Deployment

**Week 9: Testing & Validation**

* **Goal**: Ensure robot performance and reliability.
* **Tasks**:

  * Perform indoor navigation tests to check obstacle avoidance.
* Test power consumption and battery life.
  * Test the accuracy of sensors and response time.

**Week 10: Optimization**

* **Objective**: Get the system faster and better.
* **Tasks**:

  * Fine-tune motor control code for smoother navigation.
  * Fine-tune sensors for accurate distance sensing.
  * Optimize code for speed and responsiveness.

**Week 11: Documentation**

* **Objective**: Document the entire development process.
* **Tasks**:

  * Get to know: design documents, schematics, and CAD models.
   *& software architecture and codebase records.
* Create user manuals and maintenance guides.

**Week 12: Final Review & Deployment**

* **Task**: Finish the project and prepare for deployment to the repo.
* **Activities**:

  * Create the final system review and verify that all objectives are met.
  * Create a plan for real-world situations.

---

## ️ Tools & Technologies

* **Programming Language**: Python
* **Hardware**: Raspberry Pi, motor driver, servo motor, sensors for distance, camera
* **Software Libraries**: RPi.GPIO, OpenCV (utilized to process the camera), NumPy, Matplotlib (utilized for graphing), but not seen in the code, since it is an older version of it.
* **Development Environment**: VS Code, Git for version control
