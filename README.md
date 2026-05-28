# StreetSmart GIS Application

## Overview

StreetSmart GIS Application is a C++ based Geographic Information System (GIS) designed for interactive map exploration, navigation, and route planning in urban environments.

The application processes real-world geographic data and renders large-scale street networks into an interactive graphical interface. Users can search locations, explore intersections, and compute routes between destinations through a responsive map interface.

> [!NOTE]
> This project was developed as part of a university-level software engineering course.  
> The source code is not publicly available due to academic integrity restrictions.

---

## Key Features

- Interactive map showing streets, intersections, and geographic features  
- Mouse controls for zooming, panning, and selecting locations  
- Search for streets and intersections with partial name matching  
- Highlighted routes between selected start and destination points  
- Zoom-based street and Point of Interest (POI) visualization  
- Multiple colour modes including light mode, dark mode, and a red-green colourblind accessibility mode  
- Help button for understanding map symbols and interface icons  
- Clean interface designed for exploring large city-scale maps  

---

## Map Visualization System

The application represents a city as a graph structure where:

- **Nodes** represent intersections  
- **Edges** represent street segments  

Each street segment stores information such as:

- Street name  
- Length  
- Speed limit  

This graph-based representation allows efficient traversal, rendering, and route computation across large datasets.

The rendering system supports:

- Scalable drawing of map features  
- Dynamic updates based on user interaction  
- Efficient redraw operations for smooth navigation  

---

## Pathfinding & Route Planning

Routes between intersections are calculated using graph search methods:

- **Dijkstra’s Algorithm** for shortest path calculation  
- **A\*** search to speed up route finding using a heuristic toward the destination
  
---

## Screenshots

### StreetSmart
<img width="500" alt="map1" src="https://github.com/user-attachments/assets/699bc673-52e8-4604-9e81-5f2a14097dcd" />

### Click-to-select locations on the map 
<img width="400" alt="map3" src="https://github.com/user-attachments/assets/3a043a26-ccf8-4d42-b68f-95ac0bb7e21a" />
<img width="400" alt="map4" src="https://github.com/user-attachments/assets/a347b06b-e6e0-444f-8df5-c6dff66065bd" />

### Directions between two intersections
<img width="500" alt="map5" src="https://github.com/user-attachments/assets/18a540e6-c73c-4aa5-95e7-ab8148eb9208" />

### Dark mode, light mode and red-green colourblind mode
<img width="400" alt="map7" src="https://github.com/user-attachments/assets/c7558bbb-d065-43fa-930f-c75956b5e933" />
<img width="400" alt="map8" src="https://github.com/user-attachments/assets/ada6b281-a4ec-4bbc-ac82-bb98eea9fd3a" />
<img width="400" alt="map9" src="https://github.com/user-attachments/assets/3e9bcb19-c0f1-4f68-a92a-f8324046c839" />

### Zoom-based street view
<img width="400" alt="map10" src="https://github.com/user-attachments/assets/cdd19d32-dd8c-4a05-8842-6b01f3814b06" />
<img width="400" alt="map11" src="https://github.com/user-attachments/assets/a9920d01-73bd-423c-824a-79b1cc0ce94c" />
<img width="400" alt="map12" src="https://github.com/user-attachments/assets/3ca1d03f-c3f0-4969-9672-7c34869f0894" />
<img width="400" alt="map14" src="https://github.com/user-attachments/assets/8de281ed-276c-41d3-aabb-5680135e69f6" />

### Points of Interest
<img width="500" alt="map15" src="https://github.com/user-attachments/assets/c3ebe844-3b4d-4591-80ce-c56a21ee208f" />

### Pathfinding
<img width="600" alt="map16" src="https://github.com/user-attachments/assets/67fe3687-423e-4f1c-b5b9-77d9aed1177b" />
