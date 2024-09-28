[comment]: <> (https://www.sitepoint.com/styling-the-html-and-body-elements/ for the HTML code below)
<style>
 body {
   background-color: #D3D3D3; /* Light Gray */
   color: black;
 }
 h1, h2, h3, p {
   font-family: Arial, sans-serif;
 }
</style>




# About Me
I am an IT professional with a background in applied computer science and theoretical mathematics, and I have a growing passion for software engineering and development. Currently working as an IT Operations Clerk, I manage technology acquisitions and have implemented data-driven solutions to streamline processes across multiple campuses. I am also in the process of completing my Master’s in Applied Computer Science, further building my technical skills and knowledge.




While I’m still developing my expertise, I’ve gained experience with various programming languages and tools, including Java, Python, Julia, COBOL, and Power BI. I’m eager to continue learning and expanding my skill set in software design, development, and deployment.




I thrive in collaborative environments and am passionate about contributing to innovative, impactful projects that drive efficiency and user satisfaction. I’m actively seeking opportunities to grow in the field of software development and look forward to connecting with professionals in the industry.


# Work Experience
## Grand Valley State University
### IT Operations Clerk
Full-time
Jun 2023 - Present
Allendale, Michigan
- Design and maintain advanced Power BI dashboards for Technology Acquisitions purchasing data, integrating automated data collection and cleaning through Power Automate to ensure precise, real-time analytics.
- Coordinate technology acquisitions orders for faculty and staff across Grand Valley's seven campuses, proposing and implementing new business processes to enhance procurement efficiency.
- Manage vendor relationships and communications to ensure seamless procurement and delivery.
- Collaborate with IT Services to provide updates and support to the campus community, facilitating smooth operations and addressing any issues promptly.




### Lead AV Student Technician
Part-timePart-time
Jan 2021 - Jun 2023
Allendale, Michigan
- Perform general maintenance of printers and other technology equipment.
- Provide IT support to students and faculty through phone, email, and in-person interactions.
- Troubleshoot and resolve technology issues related to connectivity, power, and physical damage or blockages.
- Deliver high-quality customer service to ensure user satisfaction.
- Maintain the organization and functionality of the assigned work area.




### Computer Science Tutoring AssistantPart-time
Aug 2020 - Dec 2020
- Educate students on foundational programming skills in Java and Python.
- Provide academic tutoring and support to help students excel in their coursework.
- Develop and deliver solutions to common Java programming challenges.
- Offer general IT support to students and faculty as needed.


## Oak Ridge National Laboratory
### High Performance Computing Research Intern
Internship
May 2022 - Aug 2022
Oak Ridge, Tennessee
- Partnered in evaluating the performance and productivity of C, C++, Java, and Python through matrix multiplication, contributing to the development of strategic insights and recommendations.
- Conducted in-depth analyses of runtime and memory usage trends on high-performance systems, supporting the design and optimization of efficient software solutions.
- Published research findings and presented at conferences and research events, showcasing advancements in high-performance computing and contributing to the academic and professional community.


## Auto-Owners Insurance
### Software Engineer Intern
Internship
May 2021 to Aug 2021
Lansing, Michigan
- Gain proficiency in the syntax and applications of COBOL.
- Write organized, clean, and professional code.
- Develop meaningful projects focused on life systems.
- Conduct thorough code reviews to ensure quality and adherence to standards.
- Perform general clerical tasks such as answering phones and scheduling meetings.




# Education
## M.S. Applied Computer Science
August 2023 - Present


## B.S. Theoretical Mathematics
August 2019 - April 2023


# Publications
## The Lights Out Game on Directed Graphs
Involve, a Journal of Mathematics · Jun 1, 2024


The Neighborhood Lights Out! game can be played on tournaments. We give each vertex a label from the set {0, 1, 2, . . . , m − 1} for m ∈ N. The game is played by toggling vertices. When a vertex is toggled, the label of that vertex and each vertex it is adjacent to increases by 1 (mod m). The game is won when every vertex has a label of 0. This paper provides a toggling strategy for simplifying the game on certain digraphs. We find that the winnability of tournaments is determined by whether or not the game is always winnable on its strongly connected components. We then attempt to generalize the winnability of the possible strongly connected components.


## Comparing Data Structures Used in Divide-and-Conquer Three-Dimensional Voronoi Diagrams
24th Annual IEEE International Conference on Electro Information Technology · May 1, 2024


Voronoi diagrams are used in a wide range of applications, and many of those applications are in three-dimensional space. Two important benchmarks you can measure for Voronoi solver algorithms are run time and memory usage. Run time is important due to the potential costs of computation, and memory usage allows for larger areas to be analyzed. Run time can be addressed via parallelization, but memory usage is dependent on data structure. In this paper we compare the run time and memory usage of a previously published 3D Voronoi solver implementation that utilized an array data structure with a new novel implementation that utilizes an oct-tree data structure.


## Language Timing for Computing Voronoi Diagrams
24th Annual IEEE International Conference on Electro Information Technology · May 1, 2024


While computing Voronoi diagrams are used in a wide variety of domains and applications, comparisons are often based on different algorithms implemented in the same programming language. However, while various algorithms have different tradeoffs, the language used to implement a single algorithm can have an effect on the overall computational time required to compute a Voronoi diagram. In this paper, we compare several different languages (Julia, Java, Python with Numba, and C++) to determine the impact of language choice. We present comparisons of timing data across these languages for a variety of inputs.


## Divide-and-Conquer Algorithms for Computing Three-Dimensional Voronoi Diagrams
23rd Annual IEEE International Conference on Electro Information Technology · May 1, 2023


While Voronoi diagrams are used in a wide range of applications, leading algorithms (e.g., Fortune’s algorithm) are limited to two-dimensional Voronoi diagrams. Problematically, many of the space-dividing applications of Voronoi diagrams exist in three-dimensional spaces rather than two-dimensional spaces. While two-dimensional Voronoi diagrams have been used in cases where three-dimensional space can be simplified to two- dimensional space with an acceptable loss of precision, such simplification is not always feasible. In this paper we extend existing work on divide-and-conquer algorithms for computing two-dimensional discretized Voronoi diagrams by introducing and comparing two novel algorithms for calculating three- dimensional discretized Voronoi diagrams. A comparison of the two algorithms is presented for a range of both space sizes and number of sites.


## Evaluating performance and portability of high-level programming models: Julia, Python/Numba, and Kokkos on exascale nodes
28th International Workshop on High-Level Parallel Programming Models and Supportive Environments. · Sep 1, 2022


We explore the performance and portability of the high-level programming models: the LLVM-based Julia and Python/Numba, and Kokkos on high-performance computing (HPC) nodes: AMD Epyc CPUs and MI250X graphical processing units (GPUs) on Frontier’s test bed Crusher system and Ampere’s Arm-based CPUs and NVIDIA’s A100 GPUs on the Wombat system at the Oak Ridge Leadership Computing Facilities. We compare the default performance of a hand-rolled dense matrix multiplication algorithm on CPUs against vendor- compiled C/OpenMP implementations, and on each GPU against CUDA and HIP. Rather than focusing on the kernel optimization per-se, we select this naive approach to resemble exploratory work in science and as a lower-bound for performance to isolate the effect of each programming model. Julia and Kokkos perform comparably with C/OpenMP on CPUs, while Julia implementations are competitive with CUDA and HIP on GPUs. Performance gaps are identified on NVIDIA A100 GPUs for Julia’s single precision and Kokkos, and for Python/Numba in all scenarios. We also comment on half-precision support, productivity, performance portability metrics, and platform readiness. We expect to contribute to the understanding and direction for high-level, high-productivity languages in HPC as the first-generation
exascale systems are deployed.




# Fun Artifacts and Hobbies
## Zelda TOTK Progress and Updates
I am currently attempting to complete all of the monster medals, and obtain all of the Korok seeds present. My next goal after this is to cook every single recipe - I am only missing a few.


### Gleeoks - They are BAD.
![Gleeok Pic](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTtpZL7X2e5xBkK8kAwFs0vMvZ0wAc1z2UvSA&s)




# Sources
In this file, I used a [Syling Website](https://www.sitepoint.com/styling-the-html-and-body-elements/) some HTML code, because I have never done any HTML before.


For most of my job position information, I used my Linkedin page, [T. Elise Dettling](www.linkedin.com/in/elisedettling-67841618a)

