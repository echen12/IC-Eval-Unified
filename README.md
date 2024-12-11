# A Unified Solution of the Two IC Evaluations

**Frontend**: [https://github.com/echen12/IC-Eval-FE](https://github.com/echen12/IC-Eval-FE)  
**Backend**: [https://github.com/echen12/IC-Eval-Backend](https://github.com/echen12/IC-Eval-Backend)

## To Run:

1. Clone the project.
2. Navigate to the Project Directory

After cloning the repository, navigate to the project directory:

```bash
cd IC-Eval-Unified
```

3. Initialize Submodules

the project uses git submodules (e.g., the frontend or backend is in separate repositories),

```bash
git submodule update --init --recursive
```

4. Open the IC-Eval-Unified.sln file in Visual Studio

5. Right click on the solution -> Configure Startup Projects -> Multiple Startup Projects -> Put Backend in front of the Frontend and have both set to Start.

6. Start the project. 
