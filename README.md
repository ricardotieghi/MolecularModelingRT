# Molecular Modeling Lab

Welcome to the Molecular Modeling class repository! This repository contains all the materials, assignments, and resources you will need for the course. 

Note that I used ChatGPT to format and summarize materials within the repository.

## Table of Contents

- [Course Overview](#course-overview)
- [Class Schedule](#class-schedule)
- [Assignments](#assignments)
- [Projects](#projects)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)

## Course Overview

### Instructor

**Name:** Alexander Tropsha, PhD
**Office Location:** 331 Beard Hall
**Office Hours:** Fixed time on Zoom
**Phone:** 919-966-2955
**Email:** alex_tropsha@email.unc.edu

### Teaching Assistant

**Name:** Enes Kelestemur
**Office Hours:** Zoom by Appointment
**Email:** enesk@email.unc.edu

### Course Description

This introductory course focuses on Molecular Modeling, cheminformatics, and data science approaches to computational drug discovery. It covers topics such as QSAR, molecular simulations, and virtual screening, alongside key data science principles. The course includes both lectures and interactive laboratory sessions, utilizing various software tools to explore and analyze chemical and biological data. This repository primarily aims to contain lab materials for the course.

### Learning Objectives

By the end of this course, students will be able to:

1. Understand and apply major Molecular Modeling and cheminformatics techniques.
2. Utilize various software tools for Computer-Aided Drug Discovery.
3. Execute QSAR workflows and virtual screening campaigns.
4. Generate and investigate data-driven hypotheses.
5. Effectively communicate scientific results through presentations.

## Class Schedule

<table>
  <tr>
    <th>Date</th>
    <th>Lecture/Lab Topic</th>
    <th>Assignments/Exams</th>
  </tr>
  <tr>
    <td>M 8/19/24</td>
    <td>NO CLASS</td>
    <td rowspan="3">HW 1: RDKit Practice</td>
  </tr>
  <tr>
    <td>W 8/21/24</td>
    <td>Introduction to Class: Data Science and Drug Discovery</td>
  </tr>
  <tr>
    <td>Th 8/22/24</td>
    <td>Introduction to Python and RDKit</td>
  </tr>
  <tr>
    <td>M 8/26/24</td>
    <td>Databases for Life Sciences</td>
    <td rowspan="3">HW 2: Databases</td>
  </tr>
  <tr>
    <td>W 8/28/24</td>
    <td>Chemical data representation: molecular descriptors</td>
  </tr>
  <tr>
    <td>Th 8/29/24</td>
    <td>Databases</td>
  </tr>
  <tr>
    <td>M 9/2/24</td>
    <td>NO CLASS: Labor Day</td>
    <td rowspan="3">HW 3: Similarity Search<br>QUIZ 1: Databases and Representations</td>
  </tr>
  <tr>
    <td>W 9/4/24</td>
    <td>Chemical Similarity</td>
  </tr>
  <tr>
    <td>Th 9/5/24</td>
    <td>Molecular Representations</td>
  </tr>
  <tr>
    <td>M 9/9/24</td>
    <td>SMACC and Importance of Curated Databases</td>
    <td rowspan="3">HW 4: Curate Your Data</td>
  </tr>
  <tr>
    <td>W 9/11/24</td>
    <td>Chemical and Biological Data Curation</td>
  </tr>
  <tr>
    <td>Th 9/12/24</td>
    <td>Chemical Data Curation</td>
  </tr>
  <tr>
    <td>M 9/16/24</td>
    <td>Introduction to QSAR modeling</td>
    <td rowspan="3">HW 5: QSAR Modeling</td>
  </tr>
  <tr>
    <td>W 9/18/24</td>
    <td>Machine learning methods</td>
  </tr>
  <tr>
    <td>Th 9/19/24</td>
    <td>Machine Learning with SciKit Learn and PyCaret; Intro to QSAR Models</td>
  </tr>
  <tr>
    <td>M 9/23/24</td>
    <td>NO CLASS – Wellbeing Day</td>
    <td rowspan="3">HW 6: QSAR Modeling<br>QUIZ 2: Data Curation and QSAR Modeling</td>
  </tr>
  <tr>
    <td>W 9/25/24</td>
    <td>Guest Lecture</td>
  </tr>
  <tr>
    <td>Th 9/26/24</td>
    <td>Deep Learning with Keras and DeepChem</td>
  </tr>
  <tr>
    <td>M 9/30/24</td>
    <td>Model Validation Analysis and Interpretation</td>
    <td rowspan="3">HW 7: Virtual Screening<br>MIDTERM</td>
  </tr>
  <tr>
    <td>W 10/2/24</td>
    <td>Model Applicability domain and Ligand Based Virtual screening</td>
  </tr>
  <tr>
    <td>Th 10/3/24</td>
    <td>Ligand Based Virtual Screening Summary</td>
  </tr>
  <tr>
    <td>M 10/7/24</td>
    <td>Generative Modeling and Chemical Language Models</td>
    <td rowspan="3">HW 8: MD Simulation</td>
  </tr>
  <tr>
    <td>W 10/9/24</td>
    <td>Intro to Molecular Mechanics</td>
  </tr>
  <tr>
    <td>Th 10/10/24</td>
    <td>MD Simulation with OpenMM and MDAnalysis</td>
  </tr>
  <tr>
    <td>M 10/14/24</td>
    <td>Intro to Molecular Dynamics and Free Energy Simulations</td>
    <td rowspan="3">HW 9: Docking<br>QUIZ 3: Structure-Based Methods</td>
  </tr>
  <tr>
    <td>W 10/16/24</td>
    <td>Intro to Structure Based Drug Design</td>
  </tr>
  <tr>
    <td>Th 10/17/24</td>
    <td>NO LAB – Fall Break</td>
  </tr>
  <tr>
    <td>M 10/21/24</td>
    <td>Molecular docking pharmacophores structure-based virtual screening</td>
    <td rowspan="3">HW 10: Propose Project Topics</td>
  </tr>
  <tr>
    <td>W 10/23/24</td>
    <td>Machine learning methods in structure-based drug discovery</td>
  </tr>
  <tr>
    <td>Th 10/24/24</td>
    <td>Molecular Docking and Pharmacophores</td>
  </tr>
  <tr>
    <td>M 10/28/24</td>
    <td>Beyond bioactivity prediction: modeling of chemical toxicity</td>
    <td rowspan="3">HW 10: Propose Project Topics</td>
  </tr>
  <tr>
    <td>W 10/30/24</td>
    <td>ADME Modeling</td>
  </tr>
  <tr>
    <td>Th 10/31/24</td>
    <td>Demo of a Cheminformatics Project</td>
  </tr>
  <tr>
    <td>M 11/4/24</td>
    <td>Biomedical data translator and knowledge graphs</td>
    <td rowspan="3">Review</td>
  </tr>
  <tr>
    <td>W 11/6/24</td>
    <td>Mining Clinical and Adverse Outcome Pathways</td>
  </tr>
  <tr>
    <td>Th 11/7/24</td>
    <td>Project worktime / Questions</td>
  </tr>
  <tr>
    <td>M 11/11/24</td>
    <td>Guest Lecture: Pharmaceutical drug development</td>
    <td rowspan="3">Review</td>
  </tr>
  <tr>
    <td>W 11/13/24</td>
    <td>Modeling of Drug Delivery</td>
  </tr>
  <tr>
    <td>Th 11/14/24</td>
    <td>1:1 Check-in</td>
  </tr>
  <tr>
    <td>M 11/18/24</td>
    <td>Guest lecture: Chemical databases and chemical safety assessment</td>
    <td rowspan="3">Review</td>
  </tr>
  <tr>
    <td>W 11/20/24</td>
    <td>QSAR without Borders</td>
  </tr>
  <tr>
    <td>Th 11/21/24</td>
    <td>1:1 Check-in</td>
  </tr>
  <tr>
    <td>M 11/25/24</td>
    <td>Drug discovery: case studies</td>
    <td rowspan="3">NO CLASS – Thanksgiving Break</td>
  </tr>
  <tr>
    <td>W 11/27/24</td>
    <td>NO CLASS – Thanksgiving Break</td>
  </tr>
  <tr>
    <td>Th 11/28/24</td>
    <td>NO CLASS – Thanksgiving Break</td>
  </tr>
  <tr>
    <td>M 12/2/24</td>
    <td>Student presentations</td>
    <td rowspan="2">Mock Final</td>
  </tr>
  <tr>
    <td>W 12/4/24</td>
    <td>Class review for Final Exam</td>
  </tr>
</table>

## Assignments

Weekly homework and quizzes will reinforce lecture and lab materials. Key assessments include midterm exams, lab demonstrations, and a final project with a presentation.

### Final Project

The course features a comprehensive Molecular Modeling project, where participants will demonstrate their skills in data processing, software usage, QSAR workflow, virtual screening, hypothesis generation, and result presentation.

## Resources

- **Software Tools**: KNIME, MOE, Dragon, Schrodinger, RDKit, PyCaret, OpenMM, DeepChem
- **Suggested Reading**:
  - "An Introduction to Cheminformatics" by Andrew Leach
  - "Molecular Modeling: Basic Principles and Applications" by Hans-Dieter Holtje
  - "Data Analysis with Open Source Tools" by Phillip Janert
- **Online Tutorials**:
  - [TeachOpenCADD](https://github.com/volkamerlab/teachopencadd/tree/master)

## Contributing

We welcome contributions to improve the course materials. If you would like to contribute, please follow these guidelines:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a new Pull Request.
