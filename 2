import numpy as np
import matplotlib.pyplot as plt
from queue import PriorityQueue

# 3D Surface Plot
def plot_3d_surface():
    x = np.linspace(-5, 5, 50)
    y = np.linspace(-5, 5, 50)
    X, Y = np.meshgrid(x, y)
    Z = np.sin(np.sqrt(X**2 + Y**2))

    ax = plt.figure().add_subplot(111, projection='3d')
    ax.plot_surface(X, Y, Z, cmap='viridis')
    ax.set_title("3D Surface: sin(sqrt(x² + y²))")
    plt.show()

# Best First Search using PriorityQueue
def best_first_search(graph, start, goal):
    visited = set()
    pq = PriorityQueue()
    pq.put((0, start))

    while not pq.empty():
        _, node = pq.get()
        if node in visited:
            continue
        print(f"Visited: {node}")
        visited.add(node)

        if node == goal:
            print("Goal reached!")
            return

        for neighbor, cost in graph.get(node, []):
            if neighbor not in visited:
                pq.put((cost, neighbor))

# Main
if __name__ == "__main__":
    plot_3d_surface()

    graph = {
        'A': [('B', 1), ('C', 3)],
        'B': [('D', 1), ('E', 4)],
        'C': [('F', 2)],
        'D': [], 'E': [('G', 1)],
        'F': [], 'G': []
    }

    best_first_search(graph, 'A', 'G')
