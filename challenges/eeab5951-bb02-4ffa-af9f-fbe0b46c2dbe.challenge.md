---
extra_resources: {}
topics: []
editor_id: linkedin.e5bx9BUaOC
modified: 2021-01-30T09:03:14.799140852Z
affiliated_institute:
  url: https://challengehub.app
  en_name: ChallengeHub
  name: ChallengeHub
version: '1.0'
title_id: was-convolution-of-t2-with-a-window-function
language: en
id: eeab5951-bb02-4ffa-af9f-fbe0b46c2dbe
translations: {}
title: 'Was: Convolution of t^2 with a window function'

---

## Comments
The "signal" here is `$g(t-\tau)$` and the "window function" is `$f(\tau)$`.


## Challenge
Consider that you have a (somewhat unrealistic but mathematically manageable) input signal that varies as `$g(t)=t^2$` with time. 

Obtain the convolution of the signal `$(f \star g)(t)$` with a window function:

`$$
    f(t)=
    \begin{cases}
        1 & \text{for } -1/2 < t < 1/2\\
        0 & \text{otherwise}
    \end{cases}
$$`


## Solution Form
To check your answer, calculate `$(f \star g)(1.5)$`
