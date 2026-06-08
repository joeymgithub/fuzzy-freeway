# Fuzzy Freeway

Fuzzy Freeway is a simple browser driving game built in a single `index.html` file. You guide Fuzzy down a three-lane freeway, dodge traffic, and try to reach the highest speed before crashing.

## How It Works

- The game runs on an HTML canvas with no build step or extra dependencies.
- Your speed starts at 20 MPH and gradually climbs toward 200 MPH.
- Traffic spawns ahead of you in different vehicle types, including cars, vans, trucks, buses, and bikes.
- The game gets harder as the road speed increases.
- Weather changes as you drive: clear conditions give way to rain, puddles, storms, and lightning at higher speeds.
- Sound effects include the engine, lane swerves, horns, crashes, and a mute button.
- Your best speed is shown during the run and on the crash screen.

## How To Play

1. Open `index.html` in a web browser.
2. Press **Drive** to start.
3. Move left and right to avoid traffic.
4. Survive as long as possible while your speed keeps climbing.
5. When you crash, press **Drive Again** to restart.

## Controls

- **Left Arrow** or **A**: move left
- **Right Arrow** or **D**: move right
- **Space** or **S**: honk
- **Click/tap left side of the road**: move left
- **Click/tap right side of the road**: move right
- **Speaker button**: mute or unmute audio

## Running Locally

Because the game is plain HTML, CSS, and JavaScript, you can run it by opening `index.html` directly in your browser.

You can also serve it locally:

```bash
python3 -m http.server
```

Then open `http://localhost:8000`.
