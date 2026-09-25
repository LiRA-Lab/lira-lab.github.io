---
layout: courses
permalink: /courses/
title: Courses

description:
nav: true
nav_order: 5

courses:
  - title: "CS449/599 — Learning for Robotics"
    blurb: >
      Each semester, students put together a final project using the tools introduced
      in this course. The examples shown below represent a small, curated sample that
      captures the diversity of approaches explored.

    semesters:
      - title: "Spring 2026"
        projects: 
        - title : "ToolMind: VLM-Guided Spatial Reasoning for Robotic Tool Use"
          students: [Suleyman Talha Belen, Yunus Emre Kok, Yusuf Bugra Yazicioglu, Mehmet Emin Yaksi]
          link: "https://stalhabelen.github.io/toolmind/"
          summary: > 
            ToolMind combines vision-language models with depth-based geometric reasoning and KOMO trajectory optimization to enable open-world robotic tool use. The system predicts task-relevant grasp, contact, and waypoint keypoints from RGB-D observations without task-specific VLM fine-tuning.

        - title : "Learning to Play Jenga: Decision Making and KOMO Motion Planning for Block Extraction"
          students: [Artun Balta,  Orhun Altay, Emre Can Yologlu]
          link: "https://drive.google.com/file/d/1-Fx9bB9z26O463cmllxYZOMydi-ZcknN/view?usp=drive_link"
          summary: >
            Combining deep reinforcement learning with KOMO-based trajectory optimization for autonomous Jenga block extraction, where a learned policy selects stable blocks for removal and a multi-stage motion planner executes contact-rich pushing and collision-aware retraction with a Franka Emika Panda robot.

      - title: "Fall 2024"
        projects:
          - title: "Tower Builder Robot"
            students: [Muhammet Hikmet Simsir, Giray Akyol]
            link: "https://www.youtube.com/watch?v=VlDilpLVrOo"
            summary: >
                Constructing tall and stable structures through sequential robotic manipulation using optimization-based planning that combines nonlinear programming with heuristic configuration search.

          - title: "Robotic Throwing and Catching via Trajectory Optimization and RRT"
            students: [Tuna Saygin, Muhammad Shayan Usman, Betul Dogrul]
            link: "https://drive.google.com/file/d/1ZXdbwR_ZdUGmh5I4mJWJoniot5_y_utp/view?usp=sharing"
            summary: >
                Developing an optimization-based robotic system that accurately throws objects into dynamically placed bins by combining trajectory optimization with RRT-based path planning.
          - title: "Target Object Retrieval from Cluttered Environments"
            students: "Ozan Oğuztüzün, Görkem Salman"
            link: "https://drive.google.com/file/d/1xlWTT1IEfe55Pd9wWuL2vJEPS5PtYz7z/view?usp=sharing"
            summary: >
              Retrieving a target object from densely cluttered environments using a perception-driven manipulation pipeline. A multi-camera RGB-D system constructs a unified 3D point cloud, which is segmented and analyzed to prioritize object removal based on stability and hierarchy, enabling efficient grasping and placement through motion optimization.
---
