# Company Website - Git Collaboration Lab

## Lab 1: Branching, Merging & Conflict Resolution

### Setup
- Repository: `company-website`
- Initial file: `index.html` with "Welcome to Company Website"

### Branches Created
- `feature/navbar` - Added navigation bar
- `feature/footer` - Added footer section

### Merge Conflict Simulation
1. Created `feature/navbar` from `main`
2. Created `feature/footer` from `main`  
3. Modified same file (`index.html`) differently in each branch
4. Merged `feature/navbar` → `main` (successful)
5. Merged `feature/footer` → `main` (**CONFLICT**)

