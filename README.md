
---

# ME 206 Statics and Dynamics - Experiments Repository

## Repository Description
This repository contains the code, documentation, and experimental reports for the five experiments conducted as part of the ME 206: Statics and Dynamics course at IIT Gandhinagar. Each experiment explores core principles of statics and dynamics through real-world applications, using various tools like MSC Adams, Arduino, and MATLAB for analysis and simulation. The experiments were designed to reinforce theoretical concepts by bridging them with practical applications, providing insights into mechanical system behavior, and introducing modern engineering tools for dynamic analysis.

---

## Experiment 1: Tensegrity Table

### Objective
- Construct a tensegrity table with a load-bearing capacity of up to 3kg.
- Measure cable tensions and compare them with analytical results.
- Experimentally determine the frequency of torsional oscillations under varying loads.

### Materials Used
- **Acrylic Sheets**: Used for the top and bottom plates and struts.
- **Plastic Strings**: Act as the tensioning elements.
- **Supplementary Materials**: Scissors, glue, and a spring for tension measurements.

### Software and Tools
- **Autodesk Inventor**: For design and planning.
- **Laser Cutting Machine**: For precise cutting of acrylic sheets.
- **MATLAB**: For analyzing oscillation data and processing video frames.

### Key Learnings
- Tensegrity structures balance tension and compression.
- Real-world deviations from theoretical results were observed due to material properties and friction.

### Tags
`#Tensegrity`, `#StaticalBalance`, `#StructuralDynamics`, `#AutodeskInventor`, `#MATLAB`


---

## Experiment 2: Coriolis Effect on Rotating Frame

### Objective
- Investigate the velocity and acceleration of a moving particle in a rotating frame.
- Quantify the impact of the Coriolis effect on the observed motion.

### Materials Used
- **3D Printing Materials**: PLA filament for model components.
- **Arduino UNO**: Used to control the stepper motor.
- **Stepper Motor**: Imparts rotational force for the experiment.
- **MDF Board**: For building the rotating frame structure.

### Software and Tools
- **MATLAB**: For image processing and calculating position vectors.
- **Arduino IDE**: To program and control the stepper motor.

### Key Learnings
- The Coriolis effect was successfully demonstrated.
- Errors in velocity measurements were minimal, but acceleration calculations had significant deviations due to small time intervals.

### Tags
`#CoriolisEffect`, `#RotationalDynamics`, `#Arduino`, `#MATLAB`

[![Experiment 2](https://img.youtube.com/vi/lvvoyN_ugX8/0.jpg)](https://youtu.be/lvvoyN_ugX8?si=ef8_cAMdtJ1jw1T8)

[![Experiment 2](https://img.youtube.com/vi/XeLLp6lNIOM/0.jpg)](https://youtube.com/shorts/XeLLp6lNIOM?si=zArRIvy1IBjOeC6p)


---

## Experiment 3: Newton’s Second Law in Inertial and Non-Inertial Frames (Atwood Machine)

### Objective
- Demonstrate the application of Newton’s Second Law in inertial and non-inertial frames.
- Analyze the behavior of an Atwood machine inside a moving lift (elevator).

### Materials Used
- **3D Printed Pulleys**: For the Atwood machine setup.
- **Weights and Hanger**: Used as the mass for the Atwood machine.
- **MDF Board**: For back support.

### Software and Tools
- **MATLAB**: For analyzing the experimental data.
- **Image Processing**: Used to calculate velocity and acceleration of the masses.

### Key Learnings
- Newton’s Second Law holds true in inertial frames but fails in non-inertial frames, where pseudo-forces come into play.

### Tags
`#NewtonSecondLaw`, `#AtwoodMachine`, `#InertialFrames`, `#MATLAB`

---

## Experiment 4: Planar Four-Bar Linkage Mechanism

### Objective
- Design and analyze a four-bar mechanism with constant angular velocity applied to one link.
- Measure the velocity and angular velocity of the coupler link experimentally, analytically, and through simulation.

### Materials Used
- **MDF Board**: For constructing the linkage.
- **Chopsticks**: Used to create revolute joints.

### Software and Tools
- **MSC ADAMS**: For simulating the four-bar mechanism and comparing it with experimental data.
- **MATLAB**: For image processing and kinematic analysis.
- **Arduino UNO**: To control the crank's constant angular velocity.

### Key Learnings
- The experiment provided a clear understanding of linkage kinematics, with practical challenges related to joint alignment and system efficiency.

### Tags
`#FourBarLinkage`, `#Kinematics`, `#ADAMS`, `#Arduino`

[![Experiment 4](https://img.youtube.com/vi/Q4cXk2k-fpo/0.jpg)](https://youtu.be/Q4cXk2k-fpo?si=aaM133MdyB96XTHx)

---

## Experiment 5: Center of Percussion (CoP)

### Objective
- Identify the Center of Percussion (CoP) of an equilateral triangular plate oscillating about a vertex.
- Compare experimental CoP findings with theoretical predictions.

### Materials Used
- **MDF Board**: For creating the triangular plate.
- **Graph Paper**: To facilitate precise measurements on the triangular plate.
- **Laser Cutter**: For fabricating the experimental setup.

### Software and Tools
- **MATLAB**: For data analysis and calculating vibration amplitudes at various impact points.

### Key Learnings
- The experimentally determined CoP closely matched the analytically derived CoP, reinforcing the validity of theoretical models.

### Tags
`#CenterOfPercussion`, `#Oscillations`, `#MATLAB`, `#MechanicalVibrations`

[![Experiment 5](https://img.youtube.com/vi/CGrbidE2N-U/0.jpg)](https://youtu.be/CGrbidE2N-U?si=qfNO3ZPwgEGLO1SI)

---

## How to Use the Repository
1. **Clone the Repository**:  
   Use the following command to clone the repository:  
   ```bash
   git clone https://github.com/username/ME206-Statics-Dynamics.git
   ```

2. **Accessing the Experiment Reports**:  
   Each experiment folder contains:
   - A detailed `README.md`
   - Code and scripts used for analysis
   - Data files for experimental results and observations
   - Simulation models and CAD files

3. **Running MATLAB Scripts**:  
   MATLAB code is provided for analyzing the data from each experiment. Follow the instructions in each `README.md` file to set up the required environment and execute the code.

---

## A Note on Plagiarism

As a senior who has taken the ME 206 Statics and Dynamics course at IIT Gandhinagar, I want to remind fellow students to be mindful of the importance of academic integrity. While I’ve shared these projects and resources to help others, it's essential that you do not copy or plagiarize this work when submitting your own assignments.

Please remember to adhere to the plagiarism policy of the course, and ensure that any work you submit is your own. Referencing and learning from shared resources is encouraged, but make sure to do so responsibly by citing appropriately and contributing your own original ideas. This applies not only to ME 206 but to all your courses at IITGN.

Let’s all maintain the high standards of academic honesty and encourage a culture of integrity!


