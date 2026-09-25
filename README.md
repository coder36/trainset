# Voxel Train Yard

An animated HO-scale model railway built in voxel art, seen from the eye height of someone standing at the front of the table. Everything is in one HTML file (`index.html`): Three.js loads from a CDN, and all the models, textures and sounds are made in code.

[![The layout at late afternoon, with an airliner banking over the harbour](screenshot.png)](https://coder36.github.io/trainset/)

## ▶ Open it in your browser

**[Launch the train yard](https://coder36.github.io/trainset/)**

The page is hosted on GitHub Pages. You can also click the screenshot above.

## Middlesbrough edition

A second layout, [`middlesbrough.html`](https://coder36.github.io/trainset/middlesbrough.html), uses the same engine and fills the table with Middlesbrough.

- **The Tees along the back.** The Tees Newport Bridge is in its 2014 red and silver, fixed down. A tug and a pleasure cruiser work the river, and a coaster loaded with steel is moored at Middlehaven. The north bank is lined with the Billingham and Seal Sands chemical works, whose flare stacks burn at night. The window looks out on chimneys, flare tips and the wind farm off Redcar.
- **Rail.** A Northern Class 156 (two units, four cars) calls at a Gothic sandstone station with MIDDLESBROUGH and ERIMUS boards. A DB Cargo Class 66 hauls slab, coil and container wagons. A Class 08 shunts Tees Yard. Thornaby depot has its turntable, a Class 37 wearing the kingfisher emblem, and a visiting steam engine.
- **Town.**
  - The Town Hall, with its clock tower and crocketed spire.
  - Centre Square, with the Bottle of Notes (white script outside, a blue spiral inside) and MIMA's glass front.
  - The Old Town Hall at St Hilda's, in scaffolding for its restoration.
  - Boho One, and a statue of John Vaughan.
  - Linthorpe Road shops, including a PARMO takeaway, and the Empire lit up.
  - Red-brick terraces with chimney stacks and wheelie bins.
- **Parks and hills.**
  - Albert Park, with its boating lake, Pease's fountain, the bandstand, and Brian Clough striding towards Ayresome Park with his boots over his shoulder.
  - The Cenotaph in front of the Dorman Museum's green copper dome.
  - Stewart Park, with the Captain Cook Birthplace Museum and the granite vase.
  - The Ayresome Park estate, with the old pitch marked out and Pak Doo Ik's bronze puddle.
  - Roseberry Topping, with its collapsed cliff face, and Captain Cook's Monument on Easby Moor.
- **Steel.** A blast furnace with Cowper stoves and a skip incline, hot-metal torpedo ladles, and the DORMAN LONG tower.
- **Middlehaven extension.**
  - The Riverside Stadium, with the West Stand as the tallest. BORO and MFC are spelled out in white seats, and the south-east corner is left open for the big screen. Boro play Newcastle in front of a full crowd.
  - The Ayresome Park gates, with Mannion and Hardwick facing each other, George Camsell, and the Borobrick Road.
  - The dock clock tower, with faces on only three sides.
  - Temenos.
  - The blue Transporter Bridge, with its gondola carrying a car and passengers across to Port Clarence, plus the glass viewing lift.

- **Teesside & Acklam extension** (left end).
  - Teesside International, with runway 05/23. A KLM jet pushes back, taxis, backtracks and takes off to the north, flies a circuit over the whole layout and lands again.
  - A Ryanair jet sits on the remote stand. There's also the terminal with its jet bridges, the control tower with its beacon, a hangar with a Draken Europe jet, the fire training ground and a windsock.
  - Nearer the seam is Acklam: Acklam Hall and its avenue of trees, and red-brick semis on Trimdon Avenue.
  - Foxes Wood, with its footpath, the beck and two footbridges, and foxes trotting round.
  - Acklam Grange School and its playing field, where kids play a kick-about with jumpers for goalposts.

Some things are shown as they used to be, the way model railways often mix eras. The Dorman Long tower was demolished in 2021, the Transporter has been closed since 2019, and the Riverside's roof and floodlight details are simplified.

## Running it locally

Browsers block ES-module import maps on `file://` pages, so serve the folder locally:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000/> in Chrome.

## What's on the layout

- **Main line.** A double-track loop. A steam passenger train runs one way and stops at the station on its own. A freight train with two diesels and a caboose runs the other way.
- **Yard.** Four tracks with a ladder of turnouts and parked freight cars. A small switcher shuttles back and forth.
- **Engine terminal.** A turntable that turns a tank engine, which drives into the roundhouse stalls and under the coaling tower.
- **Harbour.** A container ship, a tug circling it, and moored boats. A gantry crane moves a container between a truck and the ship. There's also a lighthouse whose beam sweeps at night.
- **Towns.** A station with a canopy and clock tower, plus a town behind it with a church and tall blocks. In front there's a road loop with cars, buses and trucks, a gas station, a market square with a fountain, shops and a fire station.
- **Industry and fun.** A factory with smoking chimneys, grain silos, oil tanks, and a lumber yard with a forklift. There's also a fairground with a turning Ferris wheel and carousel.
- **Farm and hill.** A farm with a turning windmill, crop fields and cows, and a wooded hill.
- **Airport extension.** An extra table section bolted to the right end. It has a runway and taxiways, a terminal with jet bridges, a control tower with a rotating beacon, a hangar and a parking lot. An airliner pushes back from its gate, taxis, takes off, flies a circuit over the whole layout, lands and taxis back to its gate.
- **St James' Park extension.** An extra table section bolted to the left end, modelled on Newcastle United's ground. The towering Milburn and Leazes stands share one L-shaped cantilever roof and spell out NEWCASTLE UNITED in white seats. The Gallowgate End is mid-height, with black and white striped seats and ST JAMES' PARK in lights on its facade. The low East Stand sits in front of the sandstone Leazes Terrace. Newcastle play Sunderland on the pitch in front of a full crowd, and the big screen in the corner shows the score. Away fans sit high in the Leazes Stand. Outside there are the Sir Bobby Robson memorial garden, the Alan Shearer statue, the St James' Metro entrance, a pub, flags, Leazes Park with its lake and bandstand, and a road with traffic running round the ground. At dusk the floodlights along the roof edges come on. The airliner's circuit now passes over the stadium too.
- **Day and night.** The sun and moon move, and the window shows a changing sky with stars. After dark the street lamps, house windows, headlights, fairground bulbs and runway lights come on, with a soft glow.

## Controls

The controls are physical objects on the front of the table: drag the levers, and click the switches and buttons.

| Main panel | What it does |
|---|---|
| Passenger / Freight levers | Throttle, forward and reverse, with a notch at stop |
| Switcher / Time levers | Yard switcher speed, and how fast time passes |
| Street lights, House lights, Room lamp | Turn each set of lights on or off |
| Station stop, Harbour crane, Fair rides | Turn automatic station stops, the crane and the rides on or off |
| Whistle, Horn | Sound the steam whistle or the diesel horn |
| Turntable | Start the next turntable move |
| Day / Night | Skip ahead to evening or morning |
| All stop | Stop all trains |

| Airport box | What it does |
|---|---|
| Runway lights, Auto flights | Switch the airport lighting and automatic departures |
| Depart | Send the airliner now |
| Layout view | Go back to the main view |

| Stadium box | What it does |
|---|---|
| Match day | Show or hide the players and the crowd |
| Floodlights | Switch the floodlights on the roof edges |
| Kick off | Start a new match at 0-0 |
| Howay the lads | Get the home crowd roaring and jumping |
| Layout view | Go back to the main view |

**Camera:** drag to move across the table, right-drag (or Shift+drag) to orbit and tilt, and scroll to zoom in towards the pointer, right down to street level. On a touch screen, drag with one finger, and pinch or twist with two. Arrows or WASD move, Q/E turn, and +/- zoom. **R** resets to the current view, and **V** (or the buttons at top right) steps through the preset views.

## Notes

- Moving vehicles, trains, rides and the airliner all follow paths laid out to keep clear of the scenery. Trees and buildings are kept out of areas that are in use, so nothing passes through anything else.
- A few objects are exposed on `window` for tinkering in the browser console, for example `__SIM.time = 21` to jump to night, `__FL.request = true` to send the airliner, or `__MATCH.score` to check the score.

## License

Released under the [MIT License](LICENSE).
