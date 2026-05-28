# CS Learning

CS Learning is a long-term project for systematically studying computer science, artificial intelligence, and embodied intelligence. It will organize courses and learning tracks across computer vision, reinforcement learning, embodied AI and robotics, diffusion models, VLA, world models, video generation, and related frontier topics.

The goal is not only to collect resources, but to build a traceable, reviewable, and extensible learning system. Over time, this repository will grow into a high-quality public record of notes, implementations, paper reviews, experiments, and course projects.

## Vision

- Build strong theoretical and engineering foundations across modern AI and robotics.
- Organize every course with clear notes, assignments, papers, projects, and reflections.
- Track learning progress through a consistent changelog.
- Turn the full learning journey into a reusable and influential CS/AI study repository.

## Learning Tracks

Planned tracks include:

- Computer Vision: image understanding, detection, segmentation, 3D vision, and multimodal vision.
- Reinforcement Learning: MDPs, dynamic programming, policy gradients, actor-critic methods, and offline RL.
- Embodied AI & Robotics: perception, control, planning, simulation, and real-world deployment.
- Diffusion Models: generative modeling, conditional generation, image diffusion, and video diffusion.
- VLA: vision-language-action models, robotic foundation models, and embodied task execution.
- World Models: environment modeling, predictive learning, and internal representations for agents.
- Video Generation: temporal consistency, controllable generation, and multimodal video synthesis.

## Suggested Structure

Each course or topic can live in its own folder with a consistent internal structure:

```text
CS Learning/
├── README.md
├── CHANGELOG.md
├── computer-vision/
│   ├── README.md
│   ├── notes/
│   ├── assignments/
│   ├── papers/
│   └── projects/
├── reinforcement-learning/
│   ├── README.md
│   ├── notes/
│   ├── assignments/
│   ├── papers/
│   └── projects/
├── embodied-ai-robotics/
├── diffusion-models/
├── vla/
├── world-models/
└── video-generation/
```

## Course Folder Convention

Each course folder should generally include:

- `README.md`: course goals, resources, study plan, and completion status.
- `notes/`: chapter notes, lecture notes, and weekly summaries.
- `assignments/`: homework, implementations, and experiment writeups.
- `papers/`: paper notes, summaries, and key references.
- `projects/`: course projects, reproductions, demos, and final reports.

## Changelog

Project progress is tracked in [CHANGELOG.md](./CHANGELOG.md). Add an entry whenever a course is created, a study milestone is completed, an experiment is reproduced, an important note is added, or the repository structure changes.

## Git Workflow

Recommended workflow:

```bash
git status
git add README.md CHANGELOG.md .gitignore
git commit -m "Initialize CS learning project"
git remote add origin <github-repository-url>
git push -u origin main
```

## Current Status

- Project initialization: root README, changelog, and base ignore rules have been created.
- Course folders: pending.
- GitHub repository: pending remote connection.

