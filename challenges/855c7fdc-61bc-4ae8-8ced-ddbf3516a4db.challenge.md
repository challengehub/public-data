---
affiliated_institute:
  en_name: Kyushu University
  name: "\u4E5D\u5DDE\u5927\u5B66"
  url: https://www.kyushu-u.ac.jp
editor_id: github.NanoScaleDesign
extra_resources: {}
id: 855c7fdc-61bc-4ae8-8ced-ddbf3516a4db
language: en
modified: '2019-11-10T23:44:08.875095Z'
scrambled_answer: fb774cd739418c4ce154dc0542f4491a902a5550
title: Solving non-homogeneous ODE's
title_id: solving-non-homogeneous-odes
topics: []
translations: {}
version: '1.0'
---

## Comment
The 2nd-order equations we were considering until now were homogeneous equations (ie, the RHS was zero). We can now build upon this to expand our ability to solve non-homogeneous equations (ie, where the RHS of the equation is non-zero).

The Khan Academy videos give an excellent initial introduction to the subject, and so please do take the time to view and take notes about all four videos in the series.

In the 4th video Mr Kahn describes about how it is possible to add solutions if there are multiple terms on the right. This occasionally causes confusion. Consider for example:

`$$ y'' - 3y' - 4y = 2 \sin x $$`

This corresponds to the particular solution

`$$ y_p = A \sin x + B \cos x $$`

A common point of confusion is about what to do in the case of something like

`$$ y'' - 3y' - 4y = 2 \sin x + 2 \cos x \tag{1}$$`

Should you just write `$y_p = (A \sin x + B \cos x) + (C \sin x + D \cos x)$`? After all, you have two terms in equation 1 (ie, `$2 \sin x$` and `$2 \cos x$`). You can note however that `$A \sin x + C \sin x$` simplifies to `$E \sin x$` where `$E$` is just another constant (in this case `$A+B$`) so in the end you will be left with `$y_p = E \sin x + F \cos x$`. So while it may be clearer to explicitly calculate coefficients for every term on the RHS, in many cases the terms will simplify.

## Challenge

Find the general solution of the following non-homogeneous differential equations:

1. `$$ y'' + 4y = 8 $$`
2. `$$y'' + 4y = 8t^2 - 20t + 8$$`
3. `$$y'' + 4y = 5 \sin 3t - 5 \cos 3t$$`
4. `$$y'' + 4y = 24 e^{-2t}$$`

## Resources
- All 4 Khan Academy videos starting at https://www.khanacademy.org/math/differential-equations/second-order-differential-equations/undetermined-coefficients/v/undetermined-coefficients-1


## Solution Form
You will end up with 4 expressions corresponding to the 4 solutions above. It should be possible to write each one in a form matching one of the expressions below. Add up the points of the corresponding expressions below and enter that number as an integer to check your answers.

Obviously, in an exam setting you will need to derive the answer fully, so I recommend to work all the way to obtaining the final expression before comparing your answer to the possible solutions. Even guessing the answer first and *then* using that as a reference to derive the final answer will put you at a disadvantage in the final exam.

**1 points**: `$ y = C_1 \cos 2t + C_2 \sin 2t + 3e^{-2t} $`
**2 points**: `$ y = C_1 \cos 2t + C_2 \sin 2t + 8e^{-2t} $`
**4 points**: `$ y = C_1 \cos 2t + C_2 \sin 2t + 8e^{-4t} $`
**8 points**: `$ y = C_1 \cos 2t + C_2 \sin 2t + 3e^{-4t} $`
**16 points**: `$ y = C_1 \cos 2t + C_2 \sin 2t + 2t^2 - 5t + 1 $`
**32 points**: `$ y = C_1 \cos 2t + C_2 \sin 2t + 3t^2 + t + 3 $`
**64 points**: `$ y = C_1 \cos 2t + C_2 \sin 2t + 2t^2 + t + 3 $`
**128 points**: `$ y = C_1 \cos 2t + C_2 \sin 2t + 3t^2 - 5t + 3 $`
**256 points**: `$ y = C_1 \cos 2t + C_2 \sin 2t + 3 \cos 3t - 3 \sin 3t $`
**1024 points**: `$ y = C_1 \cos 2t + C_2 \sin 2t + \cos 3t - \sin 3t $`
**2048 points**: `$ y = C_1 \cos 2t + C_2 \sin 2t - \cos 3t + 3 \sin 3t $`
**4096 points**: `$ y = C_1 \cos 2t + C_2 \sin 2t + 3 \cos 3t + 8 \sin 3t $`
**8192 points**: `$ y = C_1 \cos 2t + C_2 \sin 2t + 8 \cos 3t - 3 \sin 3t $`
**16384 points**: `$ y = C_1 \cos 2t + C_2 \sin 2t + 2 $`
**32768 points**: `$ y = C_1 \cos 2t + C_2 \sin 2t + 5 $`
