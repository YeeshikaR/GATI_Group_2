# Satellite Orbit Animation  

A visualization of **10 satellites orbiting Earth**, animated using real **TLE (Two-Line Element) data** collected over one month.  
The goal was to make satellite motion around Earth **interactive, accurate, and visually clear**.  

---

## Problem Statement  
Satellites orbit Earth in complex paths governed by orbital mechanics.  
To understand and analyze their motion, we need a **clear and interactive animation** that shows real trajectories instead of static plots.  

---

## My Approach  
1. Data Collection  
   - Gathered TLE data for 10 satellites from [Celestrak](https://celestrak.org/)   

2. Computation  
   - Used **Skyfield** to propagate orbits from TLE data and calculate real-time satellite positions.  

3. Visualization  
   - Plotted Earth as a 3D sphere using **Plotly**  
   - Animated 10 satellites with unique **colors, labels, and orbits** for clear differentiation  

4. Deployment  
   - Built a **Streamlit app** for interactivity and hosted it online for easy access.  

---

## Tools & Libraries  
- **Python** – Programming language  
- **Skyfield** – Precise orbital mechanics from TLE data  
- **Plotly** – 3D visualization & animation  
- **Streamlit** – Web deployment  

---

## Live Link
-  http://10.147.82.227:8501
  
