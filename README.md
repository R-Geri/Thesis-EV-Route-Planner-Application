# Thesis: EV Route Planner Application

This repo contains the abstract and the presentation of my thesis work on a route planner application for electric vehicles. Please find the presentation in this repo as "***EV_Route_Planner_Presentation.pdf***" or under this link [EV_Route_Planner_Presentation.pdf](https://github.com/R-Geri/Thesis-EV-Route-Planner-Application/blob/main/EV_Route_Planner_Presentation.pdf).

## Main technologies used:
- Backend: ***C#***, ***.NET Core***
- Frontend: ***React*** with ***JavaScript***
- ***Neo4j*** graph database
- ***REST API*** for internal communication
- ***Python*** (Jupyter Notebook) for processing OSM geospatial data and populating the database
- ***Cypher*** for managing and querying data from the Neo4j database

## Abstract
In today's world, one of the most pressing issues we face is pollution and climate change on Earth. Road transportation contributes approximately 10% of all greenhouse gas emissions worldwide. While this might not initially seem significant, transitioning to electric vehicles (EV) can significantly reduce pollution on a large scale. However, EVs face challenges due to their limited range and the scarcity of electric charging points. This thesis introduces a route planning application to address these issues, encouraging people to choose electric vehicles over internal combustion engine cars, thus supporting the transition to renewable energy sources. The application can generate a route between two points and select necessary electric charging stations to ensure that users reach their destination while keeping the vehicle's battery charged. To implement this, gathering information on the EV's battery range, current charge level, weather conditions, vehicle speed along the route and other factors is crucial. Time is also a significant parameter, depending on distance, average velocity, and charging rates of available sockets compatible with the vehicle. Additionally, user preferences can be considered for the shortest route in time or distance. These various factors make the route generation process complex, demanding precision in calculations and operational logic to provide optimal results meeting individual user expectations. In order to ensure that the application performs optimally and operates quickly, I have chosen to use a graph database to store the road system of large areas. Specifically, I use the Neo4j Database Management System, which provides me with useful built-in functions, such as the Dijkstra or the A* pathfinding algorithms. To further increase the speed of these algorithms, I use a simplified version of the original data structure of the road system by representing intersections as nodes and road segments as relationships, thus reducing the number of nodes the algorithms must interact with. By using this approach, the application can generate an optimized route plan at a fast pace and with customizability, which includes necessary charging stations between two addresses.  
<br/>
<br/>
> [!NOTE]
> Please note that concrete implementation of the application is not included in this repository as it holds valuable content and potential for future development.
