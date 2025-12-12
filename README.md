## UnBox 3D

*Simplify and convert 3D models into printable 2D layouts for pysical reconstruction.*

---

## Jira Project Link

UnBox3D Jira Board: ______________________

---

**Team: Group 1**
* Alexander Rameriz
* Vivian Casas
* Jacky Lim
* Nicholas Sisneros
* Vince Wang

---

## Formal Objective Breakdown:

UnBox3D is a desktop application that guides users through importing, simplifying, and exporting 3D models into 2D layout. Our development is structured into four Key chekpoints:

Checkpoint 1:
- Create splash screen and placeholder UI
- Add "import" button and viewport region

Checkpoint 2:
- Enable .obj model import using Assimp
- Use OpenTK to render models via OpenGL

Checkpoint 3:
- Add bounding-box filtering to remove small objects
- Integrate Blender's decimation modifier for mesh simplification

Checkpoint 4:
- Use Blender's paper model exporter via Python API to generate .svg output
- Final UI polish and edge-case handling

---

## Why UnBox3D Matters

UnBox3D bridges digital modeling and physical fabrication. It empowers user to:

- Simplify complex 3D models for easier reconstruction
- Convert 3D meshes into printable 2D layouts
- Customize model detail levels before exporting
- Leverage Blender's robust mesh tools in a streamlined workflow

Ideal for prototyping and educational visualizations.

---

## How to Download or Access UnBox3D

Take a look at UnBox3D senior project design!

Installation Steps
1. Clone the repository
    ```bash
    git clone https://github.com/lemuz37/ARL-Senior-Project
    cd UnBox3D
    ```
2. Restore project dependencies  
    ```bash
    dotnet restore
    ```

3. Build the project  
    ```bash
    dotnet build --configuration Release
    ```

4. Run UnBox3D  
    ```bash
    dotnet run
    ```
**NOTE:**
You may also open the solution in Visual Studio, which allows building and running the project with a single click.
