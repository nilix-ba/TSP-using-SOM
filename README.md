# TSP using SOM

TSP using Self-Organizing Map (SOM) is a Python-based project aimed at solving the Traveling Salesman Problem (TSP) efficiently. This algorithm creates random points and updates neurons using the SOM algorithm. Neurons' weights are adjusted using a Gaussian-based neighborhood function to determine how the winning neuron influences others in the adaptive process, ultimately optimizing the TSP route.

## Introduction

The Traveling Salesman Problem (TSP) is a classic optimization challenge where the goal is to find the shortest possible route that visits a set of cities exactly once and returns to the starting city. TSP has numerous real-world applications, including logistics, circuit design, and DNA sequencing.

## How it Works

1. **Random Point Generation**: The algorithm starts by generating random points representing cities.

2. **SOM Algorithm**: It then applies the Self-Organizing Map (SOM) algorithm, where neurons are updated based on the input data.

3. **Neighborhood Function**: A neighborhood function, often based on the Gaussian function, determines how the winning neuron influences its neighbors in the adaptive process.

4. **Winner Selection**: The algorithm finds the winner neuron that best represents the current city.

5. **Weight Updates**: The weights of neurons are updated based on their proximity to the winner neuron and the neighborhood function.

## Libraries Used

This project relies on several Python libraries for its implementation:

- [NumPy](https://numpy.org/): NumPy is used for efficient numerical computations, including vectorized operations and mathematical functions.

- [Pandas](https://pandas.pydata.org/): Pandas is employed for creating and manipulating data frames, making data handling more convenient.

- [Matplotlib](https://matplotlib.org/): Matplotlib is used for data visualization, including plotting city and route maps.

## Project Structure

- `tsp_som.py`: Python script containing the implementation of the TSP using SOM algorithm.
- `input_files/`: Directory containing example TSP input files.
- `ir.csv`: Data file containing latitude and longitude coordinates for Iranian cities, used for real-world TSP optimization.
- `output_images/`: Directory where output images of city and route plots are saved.

## Test Cases

The project includes test cases using example TSP instances to demonstrate the algorithm's effectiveness. Additionally, a real-world TSP optimization for Iranian cities is provided.

## Conclusion

TSP using SOM offers an efficient approach to solving the Traveling Salesman Problem by utilizing the Self-Organizing Map algorithm. It provides a versatile tool for optimizing routes in various applications and can be further customized and extended as needed.

Feel free to explore and experiment with this project to find optimal solutions for your own TSP instances.
