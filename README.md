## Hi there 👋

I'm a researcher working at the intersection of **autonomous driving, traffic flow theory, and machine learning**.  
My work aims to better understand and improve how **autonomous vehicles (AVs) and human-driven vehicles (HVs)** interact in real traffic, using **large-scale trajectory datasets, perception systems, and data-driven models**.

I am a PhD candidate in **Transportation Engineering & Computational Science and Engineering at the University of Illinois Urbana–Champaign (UIUC)** (expected graduation: 2026). Before that, I completed my M.Sc. in Transportation Systems Analysis and Planning at **Northwestern University**, and my B.Eng. in Traffic Engineering (Highest Honors) at **Tongji University**.   

Over the past years, I’ve led or co-led research on multiple projects funded by **FHWA (TGSIM), USDOT (AVA), Illinois DOT (SER), and Argonne National Laboratory (ENACT)**, focusing on:

- 🛰️ extracting high-fidelity **trajectory data from aerial videos**,  
- 🚗 building **perception stacks** combining LiDAR, radar, and camera in ROS,  
- 📊 modeling **multi-agent interactions** using large-scale naturalistic datasets, and  
- 🧠 applying **deep learning and attention-based models** to driving behavior and AV–HV interaction.

Most of my work is documented in papers and technical reports; wherever possible, **code and instructions to reproduce key results are (or will be) open-sourced on GitHub**. Below is a more detailed list of ongoing and completed lines of work, where we:

- **validate and compare large-scale AV trajectory datasets** (e.g., Waymo Open Motion vs. a Phoenix naturalistic dataset), focusing on lane-changing, car-following, and intersection behavior  
  - [pdf](https://arxiv.org/pdf/2509.03515)

- **develop real-time perception stacks in ROS** with LiDAR segmentation, radar tracking, camera fusion, and longitudinal control evaluation on a Dataspeed drive-by-wire platform  
  - [code](https://github.com/ava-share)
 
*(In several cases the code is hosted under lab or project organizations; I link to those repositories where I am a main contributor.)*

I enjoy thinking about **how to bridge rigorous traffic flow theory, data, and modern ML** – from variational theory and stochastic models to attention mechanisms, diffusion models, and world models – and applying them to real AV systems and real roads.

My academic CV is available at:

- Website: https://zhang-yanlin.github.io  
- Google Scholar: https://scholar.google.com/citations?user=qhO_nfcAAAAJ&hl=en&oi=sra  
- LinkedIn: https://www.linkedin.com/in/zhang-yanlin  

---

### Other interesting repositories I have made public include:

- **[AerialTrajectoryExtraction](#)**  
  Deep-learning-based pipeline (detection → tracking → stabilization → cleaning) to extract accurate vehicle trajectories from aerial video (TGSIM-related).  
  <!-- TODO: replace # with actual repo link, or point to org repo + note your role -->

- **[ROS-Perception-Stack-AV](#)**  
  ROS packages for radar–camera–LiDAR fusion, Kalman filtering, and lead-vehicle tracking, tested on a full-scale AV platform (AVA / ENACT projects).  

- **[WaymoPHX-Validation-Toolkit](#)**  
  Tools to compare behavior distributions (lane-changing, car-following, intersection operations) between Waymo Open Motion and a real-world Phoenix dataset.  

- **[SER-Image-Segmentation-and-Safety](#)**  
  Image segmentation + roadway/vegetation feature extraction + crash severity modeling for self-enforcing roadways (SER, Illinois DOT).  

- **[TrajectoryKinematicsToolkit](#)**  
  Scripts for cleaning, smoothing, interpolating, and deriving kinematics (speed, acceleration, lateral measures) from raw trajectory data.  

- **[Teaching-and-Utilities](#)**  
  Small utilities, examples, and teaching material for Python, ML, and data analysis in transportation.

*(Several of these repositories are collaborative; ownership may reside with my lab or collaborators. I link them here to provide an overview of the methods and tools I helped develop.)*

---
