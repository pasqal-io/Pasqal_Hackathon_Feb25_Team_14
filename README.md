**The Blaise Pascal Quantum Challenge**
# :space_invader: Challenge n°5 : Climate and Biodiversity (SDG 13, SDG 14 & SDG 15) - Team Feynman Prodigies 

  - [Project Description](#Projectdescription)
- [ Setup Instructions](#SetupInstructions)
-  [Team Introduction](#team-introduction)
- [Acknowledgement](#Acknowledgement)







## Project Description 

This project leverages quantum computing and graph-based optimization to revolutionize CO₂ hydrogenation, a critical process for carbon capture and sustainable fuel production. By converting CO₂ into valuable chemicals like methanol and methane, it directly supports global climate action (SDG 13), clean energy solutions (SDG 7), and circular economy practices (SDG 12). Catalysts such as Cu/ZnO/Al₂O₃, Ni-based, and precious metals (Ru, Pd) drive this transformation by enhancing reaction efficiency, stabilizing intermediates, and suppressing undesired byproducts. By encoding the process as a Max-Cut problem, quantum algorithms can uncover optimal catalytic pathways, minimize energy barriers, and accelerate breakthroughs in green chemistry, paving the way for a cleaner, more sustainable future.



# Setup Instructions
```bash
# Clone the repository
git clone https://github.com/pasqal-io/Pasqal_Hackathon_Feb25_Team_14.git
cd Pasqal_Hackathon_Feb25_Team_14

# Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install notebook

# Run the notebook containing the Hydrogenation 
cd test
jupyter notebook CO2_Hydrogenation.ipynb

# For Machine learning test case
cd test
jupyter notebook GCN.ipynb
jupyter notebook MDP_Planning_graph_1.ipynb
jupyter notebook MDP_Planning_toy_graph.ipynb
```
## Usage of the Project
- `TOY1.ipynb`, `TOY2.ipynb`  - Contains notebook for testing toy model
## References

[1] Zhang et al., J. Catal., 2020, DOI: 10.1016/j.jcat.2020.02.004.

[2] Sun et al., Appl. Catal. B, 2019, DOI: 10.1016/j.apcatb.2019.04.017.

[3] Studt et al., Nature Chem., 2015, DOI: 10.1038/nchem.2205.

[4] Kattel et al., Science, 2017, DOI: 10.1126/science.aal3443.

[5] Sabatier and Senderens, Comptes Rendus, 1902.

[6] Xu et al., J. Catal., 1989, DOI: 10.1016/0021-9517(89)90246-X.

[7] OSTI Report, "Theoretical assessments of CO2 activation and hydrogenation pathways", U.S. Department of Energy, Office of Scientific and Technical Information, 2017, DOI: 10.2172/1406902.

----------------------

## Acknowledgement
We would like to extend our heartfelt gratitude to Pasqal for organizing and hosting the The Blaise Pascal Quantum Challenge. This event provided a remarkable platform for innovation, collaboration, and the exchange of ideas in the quantum computing community.

Thank you for the opportunity to participate in this event, which has not only enriched our knowledge and skills but also connected us with a network of like-minded professionals and enthusiasts.

