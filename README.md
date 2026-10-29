# City Walker
This project finds the shortest path between two cities by traversing intermediate cities. It works on a dataset of 100,000+ cities, utilizing lazy loading to add only cities that are close to the starting and target cities to the graph data structure. Dijkstra's shortest path algorithm and the Bellman-Ford algorithm are both implemented and are compared after every trial. Latitude and longitude data are used to calculate distance between cities.

## Running
1) Install dependencies
`pip install -r requirements.txt`


2) Launch the GUI
`python main.py`
