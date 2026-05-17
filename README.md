# Intelligent Route Finding System

A web-based AI route finding system developed using **SWI-Prolog** and a **HTML/JavaScript frontend**.  
The system uses the **A\* search algorithm** to compute the shortest path between locations in a graph-based model of Bahir Dar city.

---

## Features

- A* search algorithm implemented in SWI-Prolog  
- Graph-based city model with multiple locations  
- REST API communication between frontend and backend  
- Google Maps integration  
- Shortest path and total cost display  
- GPS-based location detection  

---

## Technologies Used

- SWI-Prolog  
- HTML  
- CSS  
- JavaScript  
- Google Maps API  
- Browser Geolocation API  

---

## How to Run

1. Start the Prolog Server
-Open SWI-Prolog and run:

```prolog
swipl
['server.pl'].
server(8080).
2.Run the Frontend
-Open the project folder and double-click:

index.html

-Or open it in your browser (Chrome recommended).

3. Test the System
-Select a start location
-Select a destination
-Click Find Route
-View the optimal path and total cost on the map
-Project Structure
--server.pl → SWI-Prolog backend implementing A* search
--index.html → Web interface for route selection and visualization

Repository

GitHub Repository:
https://github.com/bezawitdires121/route-finder

Purpose

This project was developed to demonstrate:

-AI search techniques (A* algorithm)
-Graph-based modeling
-Integration between SWI-Prolog backend and web frontend
-Real-world route optimization system
