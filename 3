import numpy as np
import matplotlib.pyplot as plt
from queue import PriorityQueue

# ----------- Contour Plot -----------
def visualize_contour():
    x, y = np.linspace(-5, 5, 100), np.linspace(-5, 5, 100)
    X, Y = np.meshgrid(x, y)
    Z = np.sin(X) * np.cos(Y)

    plt.contourf(X, Y, Z, 20, cmap='viridis')
    plt.colorbar()
    plt.title("Contour Plot of sin(x) * cos(y)")
    plt.xlabel("X-axis")
    plt.ylabel("Y-axis")
    plt.show()

# ----------- A* Algorithm -----------
def a_star(start, goal, grid):
    rows, cols = len(grid), len(grid[0])
    open_set = PriorityQueue()
    open_set.put((0, start))
    g = {start: 0}
    came_from = {}

    while not open_set.empty():
        _, current = open_set.get()

        if current == goal:
            path = []
            while current in came_from:
                path.append(current)
                current = came_from[current]
            return [start] + path[::-1]

        for dx, dy in [(0, 1), (1, 0), (0, -1), (-1, 0)]:
            nx, ny = current[0] + dx, current[1] + dy
            if 0 <= nx < rows and 0 <= ny < cols and grid[nx][ny] == 0:
                neighbor = (nx, ny)
                new_g = g[current] + 1

                if neighbor not in g or new_g < g[neighbor]:
                    g[neighbor] = new_g
                    f = new_g + abs(nx - goal[0]) + abs(ny - goal[1])  # f = g + h
                    open_set.put((f, neighbor))
                    came_from[neighbor] = current

    return None

# ----------- Run Program -----------
if __name__ == "__main__":
    visualize_contour()

    grid = [
        [0, 0, 0, 0, 0],
        [0, 1, 1, 1, 0],
        [0, 0, 0, 1, 0],
        [1, 1, 0, 0, 0],
        [0, 0, 0, 1, 0]
    ]

    path = a_star((0, 0), (4, 4), grid)

    if path:
        print("Path Found:", path)
    else:
        print("No Path Found.")
