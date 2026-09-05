# THE GREAT EASTERN

An endless night drive through the Western Australian wheatbelt.

You are on the highway east of Perth at some hour past midnight, and the road
runs dead straight through wheat stubble and salt lakes for as far as the
headlights reach. There is no finish line and no score to chase. There is a
tank of fuel, a radio, and however far you feel like going.

Drive.

---

## What it is

A first-person driving game with one verb. No combat, no upgrades, nothing to
collect. The road is procedurally generated and never ends, and every run is a
different road — the game prints its seed to the console when you start, so if
you find one you like you can drive it again.

The tone is the point. It should be calm, then briefly not calm, then calm
again. What unease there is comes from emptiness and from things being slightly
wrong, never from something jumping out at you.

## Driving

Top speed is 169 km/h and the tank holds 46 litres. The limits are posted and
they are real: 110 on the open road, 90 at the town edge, 50 through it.

Off the tarmac there is gravel, and gravel costs you grip, speed and a plume of
dust — but the shoulder is wide and it is a legitimate place to be. Locals use
it to duck oncoming traffic at the last moment, and the game is built expecting
you to.

Two things end a run: the fuel, and the car. Fuel comes from roadhouses. The
car repairs itself slowly if you pull over onto the verge and wait.

## The police

Parked on the verge every ten kilometres or so with their lights off. Pass one
over the limit and it comes after you, and you will hear the siren well before
you see anything in the mirror.

The rule that decides every pursuit is simple enough to read off the speedo:

- **Above 120 km/h** they sit five km/h behind you and cannot touch you. You
  are always being chased and always getting away — about a hundred metres a
  minute, which is slow enough to keep the mirror full.
- **Below 120** they are faster than you, and they will run you off the road.

So a pursuit is a decision about the next corner, the next town, the next road
train. Anything that makes you lift is what gets you caught.

They read the road too. They will overtake traffic on the wrong side if it is
clear, and on the gravel if it is not — but they take about half a second to
commit to the gravel, which is long enough for you to have put something
oncoming in the gap. It still works. It just has to be timed.

## The road

Everything is generated from the seed, so it is the same road every time for a
given one and a new one otherwise.

- **Towns** every forty kilometres or so, with main streets, shopfronts, grain
  silos floodlit from three kilometres out, roadhouses, and speed limits that
  the traffic obeys.
- **Traffic** in both directions. The oncoming stream is deliberately uneven —
  mostly steady, with occasional long clear runs that are your chance to pass a
  whole queue.
- **Avenues** where old planted gums close over the road, and your lights stop
  reaching into paddocks and start raking along trunks two metres away.
- **Canola** in flower alongside, one paddock in and the next in stubble.
- **Rest areas, level crossings, fence lines, side roads** and a lot of dark.

## Weather

Always one of four things — clear, cloudy, raining, or a thunderstorm — and it
changes roughly every five kilometres. It moves along a ladder rather than
jumping: a clear sky clouds over before it rains and rains before it storms,
and it leaves the same way.

Cloud, rain and lightning are three separate amounts, because they do not
arrive together. It clouds over before it rains and stays overcast long after
it stops.

Rain wets the road, and a wet road throws your headlights back at you.

Thunder is not a bang. A lightning channel is kilometres long, so the sound
from the far end arrives seconds after the near end, and what you hear rolls:
it swells, drops back, swells again, and takes a long while to give up. How
long it takes to reach you after the flash is the only clue you get about how
far away it was.

## Things that happen

Some are part of the road's furniture and turn up every few kilometres. Others
are set pieces and take turns, so two never land on top of each other.

**Every few kilometres**

- **Kangaroos.** About two thirds cross. The rest stop dead in your lane, turn
  side on, and watch you come — and when their nerve goes, two in five bolt
  back the way they came, which is the wrong thing to do and exactly what they
  do.
- **Road trains.** Forty metres of it, and at night mostly a constellation of
  amber clearance lights that resolves into a shape about a second before it
  reaches you. They shove you sideways as they pass. Nothing on this road moves
  one: not you, not the police.
- **Somebody else pulled over.** A car on the verge with a police car behind
  it, lights going, someone standing between them with a torch. Nothing happens
  to you. That is the event.

**Rarer**

- **A wide load.** A header on a low loader with the comb riding crossways in
  front of it, nine and a half metres across a seven-metre road, and a pilot
  vehicle out ahead carrying the sign. Everything in front of you pulls onto
  the gravel one at a time as it reaches them, and that wave coming back down
  the road towards you is the real warning. You will need the shoulder, and you
  will need to mean it.
- **Fireballs.** Not a shooting star — a bolide, crossing a quarter of the sky
  over two to four seconds, brightening in steps as it comes apart. Then, about
  four seconds after the light has gone, the bang.
- **The aurora australis.** Rare, and rarer than anything on the road.
- **Something in a paddock.** It is over before you get there. What you meet is
  what it left behind.

## The radio

Seven real Perth stations — Triple J, Nova 93.7, Gold FM, 6IX, Curtin FM,
Country and 6PR — plus **EWE FM**, which plays a folder of your own music that
you point it at in the settings.

Reception is a property of where you are, not how long you have been listening.
It comes and goes over tens of kilometres, and the way you know a station is
going is that the hiss comes up underneath it first. Parking does not fix it.
Driving on does.

Your own music is exempt: it is coming off the seat beside you, not out of the
air, so it does not fade and it does not hiss.

Everything the game synthesises goes through an FM broadcast chain — 50 µs
pre-emphasis, heavy compression and a soft clip — so it sounds like it came out
of a dashboard rather than a computer. The real stations arrive already
sounding like radio, because they are.

## Sound

There are no samples. Every sound in the game is synthesised as it plays.

The one worth listening for is the traffic. Each nearby vehicle has its own
voice, with the Doppler computed from the closing rate between you, level
falling off with distance squared, and tyre noise that depends on how fast it
is passing *you* rather than how fast it is going. Your own engine ducks
slightly as one goes by — yours is the constant you stop hearing, theirs is the
event.

## Settings

Four tabs.

- **General** — paint, steering, arms on the wheel, touch controls
- **Sound** — volume, radio level and static as sliders, and the EWE FM folder
- **Visuals** — graphics, brightness, street lighting, mirrors, film stock,
  dithering, frame rate
- **Extra** — how often the rare things happen, and a preview mode that brings
  them all out at once if you want to look at them

## Controls

    W / S      throttle, brake        A / D    steer
    Q / E      look left, right       H        headlight beam
    R          radio                  M        mute
    P          pause

On a phone, two rows of buttons across the bottom, with drag, button or tilt
steering.

## Looks

PS1-era rendering under a Kodak Vision3 500T grade: ordered dithering, film
grain, bloom, and a vignette. The headlights use a projection pattern solved
from the physics of a real dipped beam, with the kerb-side kick-up that keeps
the verge lit without dazzling anyone coming the other way.

The interface is sodium amber and bone on a blue-black night, because those are
the only two colours on that road — street lighting and your own headlights.
Signs in the world are set in a Highway Gothic derivative, which is what
Australian road signs are actually lettered in.

---

*Theft Machine Games*
