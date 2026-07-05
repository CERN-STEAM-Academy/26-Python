# 26-Python

Material for the Efficient Python course at the CERN STEAM Academy 2026.

This repository will be updated during the course. Some materials may appear only shortly before the corresponding lecture or practical session. Please update your local copy before each class.

## Repository structure

```text
Examples-for-lectures/
Lecture-notes/
  Lecture_01/
  Lecture_02/
  ...
Practical-sessions/
  Exercises_01/
  Exercises_02/
  ...
```

* `Lecture-notes/` contains slides and additional materials discussed during lectures.
* `Examples-for-lectures/` contains examples linked directly from the lecture notes.
* `Practical-sessions/` contains notebooks and files for hands-on exercises.

## Getting the repository

Clone the repository once:

```sh
git clone <repository-url>
cd <repository-name>
```

If you already cloned the repository, update it before each session:

```sh
cd <repository-name>
git pull
```

## Working with practical notebooks

Before starting a practical session, make a personal copy of the relevant exercise folder or notebook. For example:

```sh
cd <repository-name>
git pull
cp -r Practical-sessions/Exercises_01 Practical-sessions/Exercises_01_work
```

Then open and edit the notebooks in `Exercises_01_work/`, not in the original `Exercises_01/` folder.

This keeps your own solutions safe and reduces the risk of local conflicts when the repository is updated later. You can also make the copy from the Jupyter file browser by duplicating the folder or notebook and renaming it, for example to `Exercises_01_work`.

## Running notebooks

The course uses Jupyter notebooks. Please use the NGT notebook environment prepared for the Academy.

Instructions for accessing notebook and GPU resources are available in the STAC documentation:

<https://stac.docs.cern.ch/ngt/gpu-resources/>

