---
label: Past Models of Our Universe
layout: default
icon: ":globe_with_meridians:"
order: -2
author:
  - name: Matthew Sung
    email: matthew.sung20@sps.nus.edu.sg
    link: https://sps.nus.edu.sg/user/matthew.sung20/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/ultimatemember/171/profile_photo-190x190.jpg?1658781280
description: "Chapter 1 : Discovering our Universe"
---

## 1.2 Past models of our Universe

### 1.2.1 Mapping the Stars

Humans have been mapping out the stars for a very long time. Several
ancient architecture, artifacts and drawings were designed with reference
to the positions of celestial objects. These objects could be made
to record and study the seasons (to optimize agriculture activities),
for navigation, or even for religious and political purposes. A few
examples are listed below. 

![**Nebra sky disk.** A bronze disk depicting the Sun, Moon, and
32 stars including a star cluster, likely representing the Pleiades.
The disk dated to 1600 BC was found in Saxony-Anhalt, Germany.](<../resources/Chapter 1/Nebra.jpg>)


![**Nebra sky disk.** A bronze disk depicting the Sun, Moon, and
32 stars including a star cluster, likely representing the Pleiades.
The disk dated to 1600 BC was found in Saxony-Anhalt, Germany. Image credit: [J. M Bonnet Bidaud, F. Praderie, S. Whitfield](https://apod.nasa.gov/apod/ap090619.html)](<../resources/Chapter 1/Nebra.jpg>)

![**Nebra sky disk.** A bronze disk depicting the Sun, Moon, and
32 stars including a star cluster, likely representing the Pleiades.
The disk dated to 1600 BC was found in Saxony-Anhalt, Germany.
Image credit: <a href="https://apod.nasa.gov/apod/ap090619.html">J. M Bonnet Bidaud, F. Praderie, S. Whitfield</a>](<../resources/Chapter 1/Nebra.jpg>)

### 1.2.2 Geocentric, Static Earth and Perfect Circles

Greek philosopher Plato (424--348 BC) and later his student Aristotle
(384--322 BC) advocated a model where the Earth is at the center
of the Universe, while the Moon, Sun and planets orbit in concentric
circles around Earth. Although now we know that this model is wrong,
what the ancient Greeks did was still highly commendable. They tried
to make sense of the periodic motion of planets and Sun along the
ecliptic with a physical model. The act of doing so is aligned with
modern scientific thinking and processes. 

It should also be noted that not all Greek philosophers believed in
the geocentric model. The Pythagorean school of thought believed that
the Earth, the planets and the Sun are orbiting around a "central
fire". Aristarchus (310-230 BC) proposed the first heliocentric
model where the Earth orbits the Sun. These models were generally
sidelined in favour for the more influential Aristotlean school of
thought.
!!! dark
**If** Earth is moving,

**then** one should observe some stellar parallax (shift in position
of a nearby star against the background).
!!!

However as no stellar parallax had been observed in ancient times,
it was logical to conclude that Earth is static. 

There were unsurprisingly some elements of mysticism in the early
models. It was believed that circles and spheres are geometrically
perfect, and thus the motion of heavenly bodies must be in perfect
circles. 


### 1.2.3 Retrograde Motion of Planets

While the geocentric model generally accounts for the observed motions
of celestial bodies, it could not explain an anomalous behaviour of
planetary movement known as retrograde motion. Planets generally drift
from east to west along the ecliptic over the year. But sometimes
they appear to move backwards for weeks or months, before continuing
back in the usual direction.

![**Path of Mars across the fixed stars in the night sky as seen from
Earth.** From around August to October in 2003, the planet moved in
the opposite way, from west (left) to east (right). Image credit:
\protect\href{https://commons.wikimedia.org/w/index.php?curid=4662202}{Eugene Alvin Villar, CC BY-SA 4.0](<../resources/Chapter 1/retrogradeMotionMars.png>)


### 1.2.4 Ptolemy's Solution: Circles within Circles

Claudius Ptolemy (AD 100-170), Roman/Greek/Egyptian mathematician
and geographer made an ingenious twist to the geocentric model to
allow the model to fit observational data better. To the original
circular orbit of a planet which he called the deferent, he added
a smaller circle called the epicycle. The center of the epicycle is
on the (circumference of the) deferent, and the planet is on the (circumference
of the) epicycle. 

While the epicycle moves clockwise along the deferent, the planet
moves clockwise along the epicycle. When the (linear) direction of
motion in the epicycle is opposite to that in the deferent, retrograde
motion occurs. 

This circle within circle model allowed Ptolemy to have another set
of independent parameters: radius and period associated with the epicycle.
In more modern terms, Ptolemy decomposed a complicated periodic motion
(derived from astronomical observations) into two simple circular
periodic motion. Does this sound like something you have learned before?

Speaking of sound, to visualise with our ears Ptolemy's trick, run
the following in [Wolfram|Alpha](https://www.wolframalpha.com/).

```
play sin(880 pi t) for 10 s
```
```
play sin(880 pi t)+0.1{*}sin(440 pi t) for 10 s
```

The first sound $\sin(880\pi t)$ you hear is analogous to the original
geocentric model with 1 circle. The second sound $\sin(880\pi t)+0.1\sin(440\pi t)$
is analogous to Ptolemy's geocentric model with an epicycle. Hear
for yourself to note the difference.

![Snapshots of simulated retrograde motion of a planet with Ptolemy's
geocentric model with one epicycle. ](<../resources/Chapter 1/Ptolemy_retrograde.png>)


### 1.2.5 Heliocentric model

Nicolaus Copernicus (1473-1543) published *On the Revolutions
of the Heavenly Spheres* in 1543, where he re-proposed the heliocentric
(Sun-centered). Earth was treated as just another planet doing circular
orbit around the Sun. He arranged the planets in order of distance
from the Sun using the period of orbit he calculated. Earth was the
third rock from the Sun, after Mecury and Venus, before Mars, Jupiter
and Saturn. He also used geometry and observational data to estimate
the relative distance from the Sun for different planets. 

The elegance of the heliocentric model comes from its ability to demonstrate
retrograde motion of planets in a simple way. Retrograde motion of
a planet can be observed around the time when it is at it's closest
distance to Earth.

![Snapshots of simulated retrograde motion of a planet with Corpernicus'
heliocentric model without epicycles.](<../resources/Chapter 1/Copernicus_retrograde.png>)

Unfortunately, despite the elegance, Copernicus' model cannot account
for the observational data very well when it comes down to numbers.
To match the numerical data, he had to add epicycles to the heliocentric
orbits! This is one of the main reasons why many were skeptical of
Corpernicus' heliocentric model.. 

### 1.2.6 Tycho Brahe's Observations

Tycho Brahe (1546-1601) was the most respected astronomer of his
time. He took pride to make systematic and careful astronomical observations.
One of his early works was the sighting of a supernova in the constellation
of Cassiopeia in 1572. Tycho Brahe used this as evidence to challenge
the Aristotelian view that the heavens is unchanging,

He was offered an island by the Danish king, on which he built an
observatory and alchemy research centre. There, he constructed several
custom built (non-telescope) astronomical instruments capable of measuring
positions of celestial objects to 40'' (arcseconds!),
which far surpassed his contemporaries. The bulk of his observational
data was compiled compiled by Johannes Kepler in the *Rudolphine
Tables* published in 1627, several years after his death.

Brahe knew about Copernicus' heliocentric model and appreciated its
elegance but could not accept a moving Earth. He could not measure
stellar parallax, even with his accurate instruments. He maintained
a static Earth centered model where the Moon and Sun orbit the Earth
while the other planets orbit the Sun. 

Tycho fell out of favour with the new Danish king and moved to Prague
to begin work as Imperial Mathematician.

![Tycho Brahe's geo-heliocentric model. The Moon and Sun orbit the Earth
while the other planets orbit the Sun. \protect\href{https://commons.wikimedia.org/wiki/File:Tychonian_system.svg}{Image credit: Fastfission, PD}](<../resources/Chapter 1/Tycho_system.PNG>)

### 1.2.7 Johannes Kepler and the Laws of Planetary Motion

In 1600, Prague, Brahe employed Johannes Kepler, a German mathematician,
to work on mathematical modelling to fit his observational data of
planetary motion. One year later, Brahe passed away and Kepler was
appointed as Brahe's successor and continued to work on the project.
Instead of using Brahe's geo-heliocentric model, Kepler adopted a
modified version of Copernicus' heliocentric model. Kepler found that
the data will fit very well in a heliocentric model if the planetary
orbit follows an elliptical path instead of a circular one.

In 1609, he published two laws of planetary motion and in 1619, he
published the third law. The laws are:

1. Law of ellipses: The orbit of each planet is an ellipse, with
the Sun located at one of its foci.
2. Law of equal areas: A line drawn between the Sun and the planet
sweeps out equal areas in equal times as the planet orbits the Sun. 
3. Harmonic Law: The square of the time taken for a planet to
complete one revolution about the Sun (relative to the stars) is directly
proportional to the cube of the semimajor axis of the planet's
orbit. 

Mathematically, the equation of an ellipse in polar coordinates $(r,\theta)$
is given by 
$$
r=\frac{a(1-\epsilon^{2})}{1+\epsilon\cos\theta}
$$
where $a$ is the semi-major axis which is the longest line from the
center of the ellipse to its circumference, and $\epsilon$ is the
eccentricity, which characterises how elongated the ellipse is. 

![Anatomy of an ellipse. To see how the parameters affect the shape
of the ellipse, visualise it on \protect\href{https://www.desmos.com/calculator}{Desmos})(A0 Q6)](<../resources/Chapter 1/Ellipse.png>)

The second law can be expressed mathematically by 
$$
\frac{dA}{dt}=\text{constant}
$$
It gives information of how fast the planet is moving at different
parts of the orbit.

It was later known that the second law is equivalent to the law of
conservation of angular momentum. Interested reader may refer to the
appendix for details.

The third law relates the sizes and periods of orbits for different
planets. 
$$
\left(\frac{T_{1}}{T_{2}}\right)^{2}\propto\left(\frac{a_{1}}{a_{2}}\right)^{3}
$$
It is interesting to note that Kepler published the first and second
law in 1609 using only data from Mars. The third law was published
much later in 1619 after a long attempt to find patterns that could
represent ''*universal music*'' , an old philosophical concept
that movements of celestial bodies follow some beautiful proportions,
like the proportions that give rise to musical notes.
