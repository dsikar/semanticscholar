# Literature survey Knowledge Graph
Attempt at extracting structure from semi-structured text using Knowledge Graphs, to be applied to literature surveys.

In this case, we are looking at Autonomous System Safety. We start with four papers that relate to autonomous vehicle simulation:

```
# AirSim
# https://microsoft.github.io/AirSim/
@inproceedings{airsim2017fsr,
  author = {Shital Shah and Debadeepta Dey and Chris Lovett and Ashish Kapoor},
  title = {AirSim: High-Fidelity Visual and Physical Simulation for Autonomous Vehicles},
  year = {2017},
  booktitle = {Field and Service Robotics},
  eprint = {arXiv:1705.05065},
  url = {https://arxiv.org/abs/1705.05065}
}

# Baidu Apollo
# https://github.com/ApolloAuto/apollo
@misc{fan2018autotuning,
      title={An Auto-tuning Framework for Autonomous Vehicles}, 
      author={Haoyang Fan and Zhongpu Xia and Changchun Liu and Yaqin Chen and Qi Kong},
      year={2018},
      eprint={1808.04913},
      archivePrefix={arXiv},
      primaryClass={cs.RO}
}

# Carla
# https://github.com/carla-simulator/carla
@inproceedings{Dosovitskiy17,
  title = {{CARLA}: {An} Open Urban Driving Simulator},
  author = {Alexey Dosovitskiy and German Ros and Felipe Codevilla and Antonio Lopez and Vladlen Koltun},
  booktitle = {Proceedings of the 1st Annual Conference on Robot Learning},
  pages = {1--16},
  year = {2017}
}

# LGSVL 
# https://github.com/lgsvl/simulator
@article{rong2020lgsvl,
  title={LGSVL Simulator: A High Fidelity Simulator for Autonomous Driving},
  author={Rong, Guodong and Shin, Byung Hyun and Tabatabaee, Hadi and Lu, Qiang and Lemke, Steve and Mo{\v{z}}eiko, M{\=a}rti{\c{n}}{\v{s}} and Boise, Eric and Uhm, Geehoon and Gerow, Mark and Mehta, Shalin and others},
  journal={arXiv preprint arXiv:2005.03778},
  year={2020}
}

```
We use the DOI entries or, when no DOI entry exists, the article title, to search Semantic Scholar for metadata associated with the articles:
```
AirSim: https://doi.org/10.1007/978-3-319-67361-5_40
Baidu: title search
Carla: title search
LGSVL: https://doi.org/10.1109/ITSC45102.2020.9294422 
```
We are looking for insights that could be obtained from graphical tools:
```
# DOI entry required in this case
# AirSim
https://www.citationtree.org/tree?id=10.1007/978-3-319-67361-5_40
# LGSVL
https://www.citationtree.org/tree?id=10.1109/ITSC45102.2020.9294422
```
that would give insights into the literature survey. 
