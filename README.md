# Archetyping NBA Players With A Gaussian Mixture Model
This project explores the use of probabilistic clustering to identify interpretable player archetypes (e.g., off-the-dribble scorers, stretch bigs, elite wing defenders) from 2024–2025 NBA player statistics.

## Goals
- Cluster NBA players based on statistical profiles to uncover player archetypes
  - Helps teams identify players suited for specific roles to aid team-building  
  - Can be extended to project college players’ potential roles in the NBA  
  - Highlights overlooked players by revealing their play style  
  - Gives fans a clearer picture of the different player types in the league
- Implement a Gaussian Mixture Model (GMM) for clustering
  - Enables soft clustering, allowing players to partially belong to multiple archetypes rather than forcing hard assignments  
  - Models clusters with different distributions and shapes, capturing more complex, realistic patterns in player data  
  - Offers greater interpretability than methods like KMeans by providing full statistical profiles for each cluster
- Extend to a Dirichlet Process Gaussian Mixture Model (DPGMM) to automatically infer the number of clusters  
  - The exact number of NBA player archetypes is unknown and likely fluid across seasons  
  - Allows the data to determine the appropriate number of clusters rather than setting it manually

## Current Progress
- ✅ Data collection and preprocessing
- ✅ Initial GMM implementation
- 🔄 Currently evaluating cluster quality
- 🔜 Planning to implement DPGMM for more flexible modeling
- 🔜 Adding mathematical derivations and formal explanation

## Example Output
<img width="313" alt="Screenshot 2025-07-09 at 4 40 17 PM" src="https://github.com/user-attachments/assets/d7a5b921-c7d9-47ce-8a50-55cf6aadb5a3" />
<img width="299" alt="Screenshot 2025-07-09 at 4 40 34 PM" src="https://github.com/user-attachments/assets/e388632d-d234-4d3c-a4ee-9686a1aa44ba" />

## Notes
This project is a work in progress
