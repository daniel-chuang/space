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
