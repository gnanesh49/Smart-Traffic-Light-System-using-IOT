------------------------------------------------------------
SMART TRAFFIC LIGHT SYSTEM USING IoT (Web Simulation)
------------------------------------------------------------

PROJECT DESCRIPTION:
--------------------
This project simulates a Smart Traffic Light Control System using IoT concepts.
It is a browser-based simulation that shows how a 4-way traffic junction can
automatically control signals and give priority to an approaching ambulance.

The simulation is created using only HTML, CSS, and JavaScript (no external
libraries required).

------------------------------------------------------------
PROJECT FILE:
------------------------------------------------------------
1. traffic.html  - The main and only file of the project.
                   Contains HTML structure, CSS styling, and
                   JavaScript logic for the simulation.

------------------------------------------------------------
SYSTEM REQUIREMENTS:
------------------------------------------------------------
- Any modern web browser (Google Chrome, Microsoft Edge, Mozilla Firefox)
- No software installation required
- Internet connection (optional, only for downloading repository)

------------------------------------------------------------
HOW TO EXECUTE THE PROJECT:
------------------------------------------------------------

1. **Download or Clone the Repository**
   - Open your terminal or Git Bash and run:
     git clone https://github.com/gnanesh49/Smart-Traffic-Light-System-using-IOT.git

   OR

   - Click the green **“Code”** button on the GitHub page and select **“Download ZIP”**.
   - Extract the ZIP file to any folder on your computer.

2. **Locate the File**
   - Open the extracted folder.
   - Find the file named **traffic.html**.

3. **Run the Simulation**
   - Double-click on `traffic.html`.
   - It will automatically open in your default web browser.

4. **Simulation Controls**
   - You will see input fields for:
     - Number of vehicles (North, East, South, West)
     - Ambulance presence (select direction or "No ambulance")
     - Ambulance distance (in meters)
   - Press **"Start Simulation"** to begin.
   - Press **"Reset"** to stop and clear the simulation.

5. **Observe the Output**
   - The canvas displays a 4-way intersection.
   - Vehicles are shown as blue (cars) and purple (bikes).
   - The traffic light turns GREEN for one direction based on traffic load.
   - When an ambulance (yellow) approaches within 1000 meters,
     that direction immediately gets priority (green light).
   - Once the ambulance passes, the system returns to normal operation.

------------------------------------------------------------
HOW IT WORKS:
------------------------------------------------------------
- The simulation dynamically creates vehicles for each direction
  based on the input values.
- JavaScript controls traffic light logic and movement.
- The ambulance’s distance reduces with time, simulating motion.
- When the ambulance is detected within 1000 meters, its lane
  receives a green signal for immediate clearance.
- Once the ambulance passes, the system automatically restores
  normal traffic flow by selecting the busiest direction.

------------------------------------------------------------
EXPECTED OUTPUT:
------------------------------------------------------------
- Dynamic 4-way traffic light simulation on screen.
- Real-time vehicle and ambulance movement.
- Priority signal switching for ambulance detection.
- Smooth transition back to normal signal operation.

------------------------------------------------------------
PROJECT COMPLETED SUCCESSFULLY!
------------------------------------------------------------
