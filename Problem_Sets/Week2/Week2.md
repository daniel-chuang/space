# Week 2: The Rocket Equation - Solutions

## The Rocket Equation Formula Summary

$\Delta v = I_{sp} g \ln(\frac{m_1}{m_2})$
$\frac{m_1}{m_2} = \exp{(\frac{\Delta v}{I_{sp}g})} = e^{(\frac{\Delta v}{I_{sp}g})}$

1. $\Delta v$ is the total change in velocity that has been made over a burn. Said aloud, this is "Delta V".
2. $I_{sp}$ is the Specific Impulse of the engine
3. $g = \frac{9.8m}{s^2}$ is the acceleration due to gravity
4. $m_1$ is the mass that the rocket begins the burn with
5. $m_2$ is the mass that the rocket ends the burn with

Note from Mr. Wiese: $I_{sp}$ depends on where it is being measured due to differing gravities. However, a constant value would be $I_{sp} \cdot g_{earth}$. If you wanted to find the $I_{sp}$ of a differing planet, you could just divide $I_{sp \rightarrow earth} \cdot g_{earth}$ by the rate of gravity on the new planet.

### Problem Set Level 1

#### 1.1 - What are the units of $I_{sp}$?

$\Delta v = I_{sp} g \ln(\frac{m_1}{m_2})$

In terms of units:

1. $\Delta v \rightarrow \frac{m}{s}$

2. $g \rightarrow \frac{m}{s^2}$

3. $\ln(\frac{m_1}{m_2}) \rightarrow (1)$

We can simplify the equation to units:
$\frac{m}{s} = I_{sp} \frac{m}{s^2}$
$s = I_{sp}$

Note from Mr. Tappe:
You can think of $I_{sp}$ as the amount of time that a rocket (forgetting about all masses except for the mass of the fuel) can just hover  (have neutral vertical force with gravity.

The units of $I_{sp}$ are in seconds because it is measuring the amount of time that something can happen.

#### 1.2 - TWR of a rocket with $90,000kg$ and a thrust of $1,500,00N$

$\frac{1,500,000 N}{90,000kg} = 16.\bar{6}$

In order for a rocket to launch, the upwards vertical force (thrust) needs to be greater than the downwards vertical force (gravity $\cdot$ mass).

Therefore, the Thrust-to-Weight ratio has to be bigger than one: $$\frac{T}{W} > 1$$

This rocket will launch.

#### 1.3 How much do you accelerate with an $I_{sp} = 200s$, $m_1 = 10,000kg$, and $m_2 = 500kg$?

$\Delta v = I_{sp} g \ln(\frac{m_1}{m_2})$
$\Delta v = 200s \frac{9.8m}{s^2} \ln(\frac{10,000kg}{500kg})$
$\Delta v = 200 \frac{9.8m}{s} \ln(20)$

$\ln(20) = 2.9957322736 \approx 3$

$\Delta v = \frac{600 \cdot 9.8m}{s} = 5,880\frac{m}{s}$

#### 1.4 How much fuel does your friend need to burn if they have a ship with $I_{sp} = 300s$, $m_1 = 10,000kg$, trying to reach $\Delta v = 5,880$?

$\Delta 5,880 \frac{m}{s} = 300s \cdot \frac{9.8m}{s^2} \ln(\frac{10,000kg}{m_2})$

$\frac{10,000kg}{m_2} = \exp{(\frac{\Delta 5,880 \frac{m}{s}}{300s \cdot \frac{9.8m}{s^2}})} = \exp{(\frac{\Delta 5,880 \frac{m}{s}}{2,940\frac{m}{s}})} = \exp(2) \approx 7.389$

$m_2 = \frac{10,000kg}{7.389} \approx 1,353.3631073217$

$\Delta m = 10,000kg - 1,353.363kg \approx 8,646.637kg$

#### 1.5 Trash Disposal from Earth to the Sun

$\Delta v = I_{sp} g \ln(\frac{m_1}{m_2})$
$\Delta 30\frac{km}{s} = 542s \cdot \frac{9.8m}{s^2} \ln(\frac{m_1}{m_2})$
$\frac{m_1}{m_2} = \exp{(\frac{\Delta 30\frac{km}{s}}{542s \cdot \frac{9.8m}{s^2}})}$
$\frac{m_1}{m_2} = \exp{(\frac{\Delta 30\frac{km}{s}}{5.312\frac{km}{s}})}$

$m_2 = 1t$

$\frac{m_1}{m_2} = \exp{(5.647)} \approx 283.61$
$m_1 = 283.61t$

### Problem Set Level 2

#### 2.1

Notes:
Knowns:
0.45 ton satellite cargo
1.5 ton circulization engine
320s specific impulse circulization engine
1200 $\Delta v \frac{m}{s}$ needed
$m_{t} = \frac{1}{8}m_{f}$ where $m_t$ is the mass of the fuel tank and $m_f$ is the mass of the fuel

Unknowns:
What is the total mass of fuel needed? $m_{f}$
What is the total mass for the initial launch burn

$\Delta v = I_{sp} g \ln{(\frac{m_1}{m_2})}$
$\Delta 1200 \frac{m}{s} = 320s \frac{9.8m}{s^2} \ln{(\frac{m_1}{m_2})}$
$\Delta 1200 \frac{m}{s} = 320s \frac{9.8m}{s^2} \ln{(\frac{(0.45 + 1.5 + \frac{9\cdot m_{f}}{8}) t}{(0.45 + 1.5 + \frac{m_{f}}{8})})}$
$\Delta 1200 \frac{m}{s} = 320s \frac{9.8m}{s^2} \ln{(\frac{(0.45 + 1.5 + \frac{9\cdot m_{f}}{8}) t}{(0.45 + 1.5 + \frac{m_{f}}{8})t})}$

$\frac{(0.45 + 1.5 + \frac{9\cdot m_{f}}{8}) t}{(0.45 + 1.5 + \frac{m_{f}}{8})t} = \exp{(\frac{1200\frac{m}{s}}{320s\frac{9.8m}{s^2}})}$
$\frac{1.95 + \frac{9\cdot m_{f}}{8}}{1.95 + \frac{m_{f}}{8}} = \exp{(0.383)}$
$1.95+\frac{9m_f}{8} = 1.466(1.95+\frac{m_f}{8})$
$1.95+\frac{9m_f}{8} = 2.8587 + 1.466 \frac{m_f}{8}$
$m_f = 0.965$

The total mass that would be needed to bring at the initial launch burn for this stage would equal $3.035625$

#### 2.2

$\Delta v = I_{sp} g \ln{(\frac{m_1}{m_2})}$
$\Delta 1200 \frac{m}{s} = 345s \frac{9.8m}{s^2} \ ln{(\frac{(0.45 + 0.5 + \frac{9}{8}m_f)t}{(0.45 + 0.5 + \frac{m_f}{8})t})}$
$\frac{0.95 + \frac{9m_f}{8}}{0.95 + \frac{m_f}{8}} = \exp{(\frac{1200}{3,381})}$
$m_f = 0.42754$

#### 2.3

Each module has 90 tons initially
Each module has 20 tons of final mass
Each module has a specific impulse of 235s

##### 2.3.a

5 ton payload
$\Delta v = 235s \cdot 9.8\frac{m}{s^2} \cdot \ln{\frac{(90 + 5)t}{(20 + 5)t}}$
$\Delta v = 2,303\frac{m}{s} \ln{(3.8)} = 3,074.51\frac{m}{s}$

##### 2.3.b

10 ton payload
$\Delta v = 235s \cdot 9.8\frac{m}{s^2} \cdot \ln{\frac{(90 + 10)t}{(20 + 10)t}}$
$\Delta v = 2,303\frac{m}{s} \ln{(3.\bar{3})} = 2,772.75\frac{m}{s}$

##### 2.3.c

5 ton payload, two modules used
$\Delta v = 235s \cdot 9.8\frac{m}{s^2} \cdot \ln{\frac{(90 + 90 + 5)t}{(20 + 20 + 5)t}}$
$\Delta v = 2,303\frac{m}{s} \ln{(4.\bar{1})} = 3,255.74\frac{m}{s}$

##### 2.3.d

10 ton payload, two modules used
$\Delta v = 235s \cdot 9.8\frac{m}{s^2} \cdot \ln{\frac{(90 + 90 + 10)t}{(20 + 20 + 10)t}}$
$\Delta v = 2,303\frac{m}{s} \ln{(3.8)} = 3,074.51\frac{m}{s}$

##### 2.3.e

How do rockets work as the masses scale up?
They don't scale up well, especially if they are heavy compared to the cargo.

#### 2.4

Bigger is not always better in rocket design. The bigger the ratio $\frac{m_1}{m_2}$ is, the greater the $\Delta v$, where $m_2$ is the final mass of the rocket. Since there will always be mass in the rocket from components such as the command pod, engines, fuel tanks, wings, and parachutes even after all fuel is burned, the heavier (which generally correlates to size) these components are, the more fuel will be needed to make $m_1$ greater.
