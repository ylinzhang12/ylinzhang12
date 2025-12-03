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

- **extract high-fidelity vehicle trajectories from aerial videos (TGSIM, FHWA)** Developed a deep-learning pipeline (detection → tracking → stabilization → cleaning) that processed  
  14 hours of raw helicopter video into **11,000+ vehicle-kilometers** of accurate trajectories.  
  - [code](https://github.com/ylinzhang12/TGSIM-trajectory-pipeline) &nbsp; [pdf](https://journals.sagepub.com/doi/abs/10.1177/03611981241257257) &nbsp; [data](https://catalog.data.gov/dataset/?q=TGSIM&sort=views_recent+desc) 

- **validate and compare large-scale AV trajectory datasets** (e.g., Waymo Open Motion vs. a Phoenix naturalistic dataset), focusing on lane-changing, car-following, and intersection behavior  
  - [pdf](https://arxiv.org/pdf/2509.03515)

- **develop real-time perception stacks in ROS** with LiDAR segmentation, radar tracking, camera fusion, and longitudinal control evaluation on a Dataspeed drive-by-wire platform  
 
- **develop perception and analytics pipelines for autonomous driving**  
  Designed and implemented ROS modules for real-time LiDAR segmentation, radar tracking, camera fusion, and Kalman-filter-based lead-vehicle detection. In parallel, I built a unified data analysis pipeline for trajectory cleaning, interpolation, smoothing, lane assignment, kinematics estimation, and interaction feature extraction, supporting large-scale datasets.
    - [code](https://github.com/ava-share)

 
*(In several cases the code is hosted under lab or project organizations; I link to those repositories where I am a main contributor.)*

I enjoy thinking about **how to bridge rigorous traffic flow theory, data, and modern ML** – from variational theory and stochastic models to attention mechanisms, diffusion models, and world models – and applying them to real AV systems and real roads.

My academic CV is available at:

- Website: https://zhang-yanlin.github.io  
- Google Scholar: https://scholar.google.com/citations?user=qhO_nfcAAAAJ&hl=en&oi=sra  
- LinkedIn: https://www.linkedin.com/in/zhang-yanlin  

