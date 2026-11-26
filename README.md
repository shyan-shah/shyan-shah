# Shyan Shah

MEng Mechanical Engineering at the University of Bath (graduating 2028). Most of my work sits where hardware meets code: a physical thing gets designed, built and simulated, then made to talk to software.

## Robotics and hardware

**[Vita](https://github.com/shyan-shah/leukerbad-hack)**. Turns an off the shelf, force sensing robot arm (Flexiv Rizon 4) into an arm rehabilitation station. The arm acts as an elastic band at four resistance levels, counts every rep and measures force and range. A physio follows each session remotely. FastAPI server with a 30 Hz WebSocket feed, a 100 Hz control loop, a single safety layer as the only code that touches the robot, and a custom end effector designed in Inventor and printed on site. Built in 48 hours by a team of five at the Leukerbad Robot Carnival (Nov 2026). Research prototype, team tested only. [vitarehab.org](https://vitarehab.org)

**[Robot penguin](https://github.com/shyan-shah/robot-penguin)**. A 23 cm desk robot that waddles, talks, dances and reacts to people. Seven servos, an ESP32-S3 and a 580 g printed shell. The physics simulation is built from the CAD, and the firmware's motion tables are generated from the simulation, so what gets printed is what was tested. Parametric CAD, print ready STLs, MATLAB/Simulink stability analysis and a full build log. Designed and simulated, physical build in progress.

**[Cold plate factory](https://github.com/shyan-shah/coldplate-factory)**. Agent run manufacturing and test pipeline for data centre liquid cooling cold plates. Six agents take a request from intake to a planned, verified and scheduled test campaign, stopping at an engineer release gate. The agents decide; the numbers come from deterministic Python: thermal network, convection and pressure drop models, DFM and QA checks. Rigs and robot cell are mocked and labelled as such.

## Software

**[Training Intelligence](https://github.com/shyan-shah/training-intelligence)**. Readiness, training load, recovery, body composition and habit streaks for one athlete, with every number traceable to a formula. Ingests Garmin, Strava and Evolt scans into Supabase, with a Python analytics engine, a Next.js dashboard and scheduled jobs.

**[Lecture Vault](https://github.com/shyan-shah/lecture-vault)**. Watches Panopto, pulls captions or transcribes the audio, syncs slides, tutorial sheets and past papers from Moodle, and writes revision notes that compare what was said with what is on the slides. Includes spaced repetition practice cards and Anki export.

**[FlowLocal](https://github.com/shyan-shah/flowlocal)**. Offline voice to text on Windows built on Whisper. Push to talk or hands free, a cleanup engine for fillers and self corrections, voice command editing and per app writing styles.

**[Engineering shorts](https://github.com/shyan-shah/engineering-shorts)**. Pipeline for short explainer videos on how everyday things work. Each video is scripted with sourced facts, animated as code in SVG, voiced with ElevenLabs, rendered frame by frame in headless Chrome and posted by script.

## Elsewhere

- LinkedIn: [shyanshah](https://www.linkedin.com/in/shyanshah)
