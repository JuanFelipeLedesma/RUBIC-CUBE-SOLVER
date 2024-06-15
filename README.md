# Rubik's Cube Solver

## Description

The **Rubik's Cube Solver** is an application that allows users to input the current state of a 3x3 Rubik's Cube through a graphical user interface and provides the quickest sequence of moves to solve it. The application uses the Kociemba algorithm to find the solution.

## Features

- User-friendly graphical interface to input the cube's state.
- Solves the cube using the Kociemba algorithm.
- Displays the sequence of moves needed to solve the cube.

## Screenshots

<!-- Include some screenshots of the application's interface here (TO-DO)-->

## Requirements

- Python 3.x
- Tkinter
- kociemba

## Installation

1. Clone this repository to your local machine.
    ```bash
    git clone https://github.com/your_username/rubiks-cube-solver.git
    cd rubiks-cube-solver
    ```

2. Create and activate a virtual environment (optional, but recommended).
    ```bash
    python -m venv rubik_env
    source rubik_env/bin/activate  # On Windows use `rubik_env\Scripts\activate`
    ```

3. Install the dependencies.
    ```bash
    pip install tkinter kociemba
    ```

## Usage

1. Run the application.
    ```bash
    python rubik_solver.py
    ```

2. Enter the current state of the cube in the graphical interface.

3. Click on "Save State" to record the cube's state.

4. Click on "Solve Cube" to get the sequence of moves needed to solve the cube.

## Project Structure

rubiks-cube-solver/
├── README.md
├── rubik_solver.py
├── cubo_rubik.py
├── requirements.txt
└── ...

## Contributing

Contributions are welcome. Please follow these steps:

1. Fork this repository.
2. Create a branch with a new feature (`git checkout -b feature/new-feature`).
3. Make your changes and commit (`git commit -am 'Add new feature'`).
4. Push your changes to your fork (`git push origin feature/new-feature`).
5. Create a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Credits

This project was developed by Juan Felipe Ledesma. Special thanks to all contributors and the Python community.

