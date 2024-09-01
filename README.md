# Project 2: ATFMS - Flight Management System

This project was carried out in the **second year first semester**, where we developed a flight management system using **graphs** and the **Haversine formula** to manage and analyze flight routes and airports.

## Overview

In this project, we built a system in **C++** that models a network of flights and airports using a graph structure. The system allows for the management of flights, airports, and airlines, as well as the calculation of various metrics such as reachable destinations, the impact of airport closures, and the optimization of flight routes. The Haversine formula is used to calculate the shortest distance between two points on the earth's surface, which is crucial for determining flight distances.

## Features

### Key Features

- **Flight and Airport Management**

  - Manages a system of flights and airports represented as a graph.
  - Loads and stores information about airlines, airports, and flights from CSV files.

- **Route and Traffic Analysis**

  - Calculates the number of flights and airlines associated with specific airports or cities.
  - Determines the number of different countries reachable from a given city or airport.
  - Identifies airports with the highest air traffic and those that are essential for maintaining connectivity.

- **Flight Optimization**

  - Finds the best flights between two airports based on various criteria.
  - Filters flights by specific airlines and optimizes routes accordingly.
  - Identifies the longest possible flight itinerary and calculates the number of reachable destinations with a given number of stops.

- **Geographical Calculations**
  - Uses the Haversine formula to calculate distances between geographical coordinates.
  - Transforms city names, airport names, and geographical coordinates into airport codes for easier processing.
