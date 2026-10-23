Space-Time Travel Planner
Overview / Description
The Space-Time Travel Planner is a terminal-based Python application designed to simulate interplanetary travel logistics across our solar system. Based on principles of gravitational physics and theoretical astrophysics, the program calculates how traveling to different celestial bodies (Mars, Jupiter, and Venus) impacts physical metrics such as effective weight, mission arrival schedules, and chronological age progression relative to Earth years.
Documentation & Proposal
Draft Proposal: See proposal.md for full project documentation, literature background, and SMART objectives.
Section / Proponent: Lyan Ezekiel P. Tolentino 
                     Ronand Jeth E. Macapañas
                     Jaden O. Yusiong
                     (Grade 8 Section 8-Camia)
Institution: Philippine Science High School - Eastern Visayas Campus
Planned Features
Interactive Destination Selection: Choose between Mars, Jupiter, and Venus with built-in input validation.
Gravitational Weight Scaling: Calculates your weight on other planets based on local gravitational multipliers (0.38g for Mars, 2.34g for Jupiter, and 0.90g for Venus).
Arrival Date Prediction: Uses Python's datetime module to calculate your estimated calendar arrival date based on mission travel duration.
Age Progression Calculation: Computes your adjusted age upon arrival at your destination.
Planned Inputs & Outputs
Category
Input Data
Generated Output / Operation
User Data
Earth Weight (lbs/kg), Current Age (years)
Validated numerical values used for scaling calculations
Destination
Selection Index (1, 2, or 3)
Sets destination parameters (Gravity Multiplier & Transit Days)
Calculations
System Current Date
Target Weight, Arrival Date, and Arrival Age

Program Logic
Pseudocode Highlights
1. Prompt user for Earth weight and age with validation loops.
2. Present destination selection menu (Mars, Jupiter, Venus).
3. Retrieve gravity multiplier and transit offset for chosen planet.
4. Calculate Target Weight = Earth Weight * Gravity Multiplier.
5. Calculate Arrival Age = Current Age + (Transit Days / 365.25).
6. Calculate Arrival Date = Current Date + Transit Days.
7. Display formatted summary and planetary metrics output.


How to Run / Requirements
Requirements
Python 3.x installed on your system.
Standard Python libraries: datetime (pre-installed with Python).
How to Run
Clone or download the project files to your local directory.
Open a terminal or command prompt in the project directory.
Run the application using Python:
python planner.py


Sample Interaction / Example Output
====================================
   SPACE-TIME TRAVEL PLANNER
====================================
Enter your weight on Earth (lbs): 110
Enter your age: 13

Choose your destination:
1. Mars
2. Jupiter
3. Venus
Enter your choice (1-3): 1

========== TRIP SUMMARY ==========
Destination: Mars
Departure Date: October 16, 2026
Travel Time: 212 days
Estimated Arrival: May 16, 2027

========== PLANETARY METRICS ==========
Your Weight on Mars : 41.80 lbs
Your Age on Mars    : 13.6 years
====================================


