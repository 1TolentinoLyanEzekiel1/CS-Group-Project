Space-Time Travel PlannerOverview / DescriptionThe Space-Time Travel Planner is a terminal-based Python application designed to simulate interplanetary travel logistics across our solar system. Based on principles of gravitational physics and theoretical astrophysics, the program calculates how traveling to different celestial bodies (Mars, Jupiter, and Venus) impacts physical metrics such as effective weight, mission arrival schedules, and chronological age progression relative to Earth years.
Features:
Interactive Destination Selection: Choose between Mars, Jupiter, and Venus with built-in input validation.
Gravitational Weight Scaling: Calculates your weight on other planets based on local gravitational multipliers ($0.38g$ for Mars, $2.34g$ for Jupiter, and $0.90g$ for Venus).
Arrival Date Prediction: Uses Python's datetime module to calculate your estimated calendar arrival date based on mission travel duration.
Age Progression Calculation: Computes your adjusted age upon arrival at your destination.

How to Run / RequirementsRequirementsPython 3.x installed on your system.Standard Python libraries: datetime (pre-installed with Python).

How to Run
Clone or download the project files to your local directory.
Open a terminal or command prompt in the project directory.Run the application using Python:
Bashpython planner.py

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
Your Weight on Mars : 41.8 lbs
Your Age on Mars : 13.6 years
====================================
