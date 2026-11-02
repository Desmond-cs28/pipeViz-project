HOW TO RUN:
pipeline_sim.py — the pipeline simulation logic
app.py — Flask server that runs the simulation and sends results to the browser
templates/visualizer.html — the webpage that displays the results
How to run
1. Install Flask (one time only):

pip install flask
2. Start the server:

python app.py
3. open your browser and go to

http://localhost:5000
Use Next / Previous to step through each cycle. Turn forwarding on/off to see how stall counts change.
