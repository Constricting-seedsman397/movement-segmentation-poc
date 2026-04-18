# 🧩 movement-segmentation-poc - Track movement with image masks

[![Download the app](https://img.shields.io/badge/Download%20Release-purple?style=for-the-badge)](https://github.com/Constricting-seedsman397/movement-segmentation-poc/releases)

## 📌 What this does

movement-segmentation-poc is a proof of concept for movement analysis with dense instance segmentation masks. It helps you compare motion with object shape and position in a scene.

Use it to:

- load movement data
- view segmentation masks on top of frames
- inspect spatial interaction between tracked subjects
- work with animal behavior and movement data
- export results for later review

## 🖥️ Windows download and setup

This app is made for Windows users who want to run it without writing code.

### 1. Open the download page

Visit this page to download the app:

[Go to the releases page](https://github.com/Constricting-seedsman397/movement-segmentation-poc/releases)

### 2. Download the Windows file

On the releases page, look for the latest version.

Download the file that matches Windows, such as:

- `*.exe`
- `*.msi`
- `*.zip`

If you download a `.zip` file, extract it first.

### 3. Run the app

If you downloaded an `.exe` or `.msi` file:

- double-click the file
- follow the on-screen steps
- wait for the setup to finish

If you downloaded a `.zip` file:

- right-click the file
- choose Extract All
- open the folder
- double-click the app file inside

### 4. Open the program

After setup, look for the app in:

- your Desktop
- the Start menu
- the folder where you extracted it

## 🧭 First run

When you open the app for the first time, it may ask you to choose files or a folder.

A typical workflow looks like this:

1. open the app
2. load your movement dataset
3. load the matching image or video data
4. load segmentation masks if needed
5. start the analysis view

If Windows shows a security prompt, choose the option that lets you continue only if you trust the file source and release page.

## 🎯 What you can do with it

This proof of concept focuses on movement analysis with segmentation data. That means you can use it to:

- compare paths with object masks
- inspect where subjects move in a scene
- check how motion lines up with visible regions
- analyze interactions in a space
- review changes over time

This fits work in:

- animal behavior
- kinematics
- movement detection
- movement analysis
- computer vision research
- instance segmentation workflows

## 🧱 What you need

For the best experience on Windows, use a system that meets these basic needs:

- Windows 10 or Windows 11
- at least 8 GB of RAM
- enough free disk space for your data files
- a mouse for easy viewing and selection
- a screen with 1366×768 resolution or better

For larger datasets, 16 GB of RAM or more helps.

## 📂 Supported data types

This app is built around common research file types and structured data.

It may work with:

- image folders
- video files
- tracked movement data
- xarray datasets
- zarr stores
- mask files from segmentation tools
- results from instance segmentation models

It is useful when your data comes from systems like:

- SAM
- SAM2
- movement tracking tools
- custom computer vision pipelines

## 🛠️ How the workflow fits together

The app links movement data with dense instance masks.

A simple flow looks like this:

1. detect or load movement
2. create or import segmentation masks
3. align masks with frames
4. inspect the scene
5. measure spatial interaction

This helps you see not just where a subject moves, but how that movement relates to objects and regions in the frame.

## 🪟 If the file does not open

If Windows does not run the file right away, try these steps:

- make sure the download finished
- extract the file if it is inside a zip archive
- check that you downloaded the Windows release
- move the file to a simple folder like `Downloads`
- run the file again
- restart Windows and try once more

If the app opens but the window stays blank, wait a moment while it loads your data.

## 🔍 Main features

- load movement data from structured files
- overlay dense segmentation masks on frames
- inspect motion and spatial context
- support research-style analysis views
- handle larger data with tools built for batch processing
- use outputs that fit later review in Python-based workflows

## 📁 Example use case

A user studying animal behavior may want to know where a tracked animal moves inside a pen.

With this app, they can:

- load the tracking data
- view the animal over time
- add segmentation masks for the animal or objects in the scene
- compare movement with space use
- check interaction with zones in the frame

That makes it easier to review behavior without moving between many tools.

## 🧰 Technical background

This project uses tools and ideas often found in data and vision work:

- Python
- Dask for larger workloads
- xarray for labeled arrays
- zarr for chunked data storage
- instance segmentation for object masks
- kinematics for motion analysis

You do not need to know these tools to run the app on Windows. They are part of how the project works behind the scenes.

## 📦 File layout after download

If you download a zip release, you may see files like:

- `app.exe`
- `data/`
- `models/`
- `config/`
- `README.txt`

Keep the files together in the same folder. Moving only one file can stop the app from starting.

## 🔐 Trusted source

Download the release only from the project release page:

[https://github.com/Constricting-seedsman397/movement-segmentation-poc/releases](https://github.com/Constricting-seedsman397/movement-segmentation-poc/releases)

## 🧪 Tips for smooth use

- close other large apps before you start
- keep your data in one folder
- use short folder names
- avoid spaces and special characters if the app asks for file paths
- start with one small dataset before using a large one
- keep the release file and data files in separate folders

## 🧭 Common tasks

### Open a dataset

1. start the app
2. choose your movement file
3. choose your image or video source
4. load the masks
5. review the result

### Compare frames

1. open the dataset
2. move through time or frames
3. check how the mask changes
4. compare the view across the sequence

### Review spatial interaction

1. load the full scene
2. place the masks over the objects
3. check where the subject enters or leaves areas
4. inspect overlap and movement path

## ❓ Questions people may have

### Does this need Python?

No. The Windows release is meant to run as an app.

### Can I use it without research data?

Yes. You can test it with sample files or your own movement and image data.

### Does it work with large datasets?

Yes, but larger datasets need more memory and can take longer to load.

### Can I use it for computer vision work?

Yes. It fits workflows that use instance segmentation and movement analysis.

## 🧾 Topics covered by this project

- animal behavior
- computer vision
- dask
- gsoc
- instance segmentation
- kinematics
- movement analysis
- movement detection
- poc
- python
- sam
- sam2
- xarray
- zarr

## 🗂️ Project name

movement-segmentation-poc

## 📍 Release download

Use the release page below to download and run the Windows file:

[Download from Releases](https://github.com/Constricting-seedsman397/movement-segmentation-poc/releases)