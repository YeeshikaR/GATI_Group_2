Live link: https://generativetask2deploy-yeetv8xkdvyxr4djcxjwjzrjf.streamlit.app/

### Overview
  This project visualizes the 3D orbital trajectories of 10 satellites around Earth over the past 30 days. Using real-world Two-Line Element (TLE) data, it calculates satellite positions at regular intervals and animates their movement in an interactive 3D plot. The visualization satellites using distinct colors and shows their orbits alongside the Earth.

### Approach
-> Data Collection: 
    Selected 10 satellites from various categories (NOAA, GPS, Scientific, Communication).
    Obtained their TLE data from public sources (CelesTrak, NORAD).
    TLE data provides orbital elements required to compute satellite positions at any given time.
-> Position Calculation:
    Used the Skyfield library to parse TLE data and compute satellite positions.
    Calculated positions at 3-hour intervals over the past 30 days.  
    Converted satellite positions to 3D Cartesian coordinates (x, y, z in km).
-> 3D Visualization
    Used Plotly to create 3D scatter plots and line traces.
    Rendered Earth as a semi-transparent 3D surface using spherical coordinates.
    Satellite orbits drawn as lines, while moving satellites represented as markers.
-> Animation
    Generated frames for each time step.
    Each frame contains markers for all satellites at that timestamp.
    Added Play button for continuous animation using Plotly’s animation functionality.
-> Deployment
    Wrapped the application in a Streamlit web app for interactive deployment.
    Users can click a button to load and animate satellite trajectories.








Wrapped the application in a Streamlit web app for interactive deployment.

Users can click a button to load and animate satellite trajectories.
