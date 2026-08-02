# Explain this

> bujhay dao
> valovabe note korte pari nai...kisu jinish missing thakte pare
> properly bujhay dao
>
> User context
>
> Images:
> - `~/CrossDevice/CMF by Nothing Phone 2 Pro/storage/DCIM/Camera/IMG_20260802_081843499.jpg`
> - `~/CrossDevice/CMF by Nothing Phone 2 Pro/storage/DCIM/Camera/IMG_20260802_081837440.jpg`
> - `~/CrossDevice/CMF by Nothing Phone 2 Pro/storage/DCIM/Camera/IMG_20260802_081834475.jpg`
> - `~/CrossDevice/CMF by Nothing Phone 2 Pro/storage/DCIM/Camera/IMG_20260802_081825027.jpg`
> - `~/CrossDevice/CMF by Nothing Phone 2 Pro/storage/DCIM/Camera/IMG_20260802_081822418.jpg`
> - `~/CrossDevice/CMF by Nothing Phone 2 Pro/storage/DCIM/Camera/IMG_20260802_081815722.jpg`
> - `~/CrossDevice/CMF by Nothing Phone 2 Pro/storage/DCIM/Camera/IMG_20260802_081811165.jpg`
> - `~/CrossDevice/CMF by Nothing Phone 2 Pro/storage/DCIM/Camera/IMG_20260802_081804069.jpg`
> - `~/CrossDevice/CMF by Nothing Phone 2 Pro/storage/DCIM/Camera/IMG_20260802_081759924.jpg`
> - `~/CrossDevice/CMF by Nothing Phone 2 Pro/storage/DCIM/Camera/IMG_20260802_081753204.jpg`
> - `~/CrossDevice/CMF by Nothing Phone 2 Pro/storage/DCIM/Camera/IMG_20260802_081725451.jpg`
> - `~/CrossDevice/CMF by Nothing Phone 2 Pro/storage/DCIM/Camera/IMG_20260802_081720996.jpg`
> - `~/CrossDevice/CMF by Nothing Phone 2 Pro/storage/DCIM/Camera/IMG_20260802_081717615.jpg`
> - `~/CrossDevice/CMF by Nothing Phone 2 Pro/storage/DCIM/Camera/IMG_20260802_081705040.jpg`
> - `~/CrossDevice/CMF by Nothing Phone 2 Pro/storage/DCIM/Camera/IMG_20260802_081701778.jpg`
> - `~/CrossDevice/CMF by Nothing Phone 2 Pro/storage/DCIM/Camera/IMG_20260802_081655556.jpg`
> - `~/CrossDevice/CMF by Nothing Phone 2 Pro/storage/DCIM/Camera/IMG_20260802_081653160.jpg`
> - `~/CrossDevice/CMF by Nothing Phone 2 Pro/storage/DCIM/Camera/IMG_20260802_081647003.jpg`
> - `~/CrossDevice/CMF by Nothing Phone 2 Pro/storage/DCIM/Camera/IMG_20260802_081643025.jpg`

তোমার ছবিগুলোর মূল topic হলো **Wave Motion**—progressive wave, wave equation, particle velocity, energy–intensity, stationary wave, group/phase velocity, Doppler effect এবং acoustics। নিচে নোটের ভুল ও missing step ঠিক করে পুরো chapter-টা ধারাবাহিকভাবে বোঝাচ্ছি।

> গুরুত্বপূর্ণ notation:
> \(y\)=particle displacement, \(a\)=amplitude, \(\lambda\)=wavelength, \(f\)=frequency, \(T\)=period,
> \(\omega=2\pi f\), \(k=2\pi/\lambda\), \(v=\) wave velocity,
> \(u=\partial y/\partial t=\) particle velocity, \(\rho=\) density।

---

## 1. Wave আসলে কী?

Wave হলো এমন disturbance, যা এক স্থান থেকে অন্য স্থানে **energy বহন করে**, কিন্তু medium-এর particles-কে স্থায়ীভাবে সঙ্গে নিয়ে যায় না।

যেমন দড়ির একটি মাথা নাড়ালে disturbance সামনে যায়, কিন্তু দড়ির প্রতিটি particle শুধু নিজের mean position-এর আশেপাশে oscillate করে।

### Progressive বা travelling wave

যে wave medium-এর মধ্য দিয়ে সামনে এগোয় এবং energy transfer করে, তাকে progressive wave বলে।

### Transverse wave

Particle vibration wave চলার দিকের perpendicular।

উদাহরণ: stretched string-এর wave।

### Longitudinal wave

Particle vibration wave চলার দিকের parallel। এতে compression ও rarefaction তৈরি হয়।

উদাহরণ: air-এ sound wave।

---

## 2. Basic relations

একটি wave এক period \(T\)-তে এক wavelength \(\lambda\) যায়। তাই

\[
v=\frac{\lambda}{T}=f\lambda
\]

কারণ

\[
f=\frac1T
\]

Angular frequency ও wave number:

\[
\omega=2\pi f=\frac{2\pi}{T},
\qquad
k=\frac{2\pi}{\lambda}
\]

তাই

\[
\boxed{v=\frac{\omega}{k}}
\]

---

## 3. Phase এবং phase difference

SHM-এ

\[
y=a\sin\theta
\]

এখানে \(\theta\)-কে phase বলে।

Travelling wave-এর phase:

\[
\theta=\omega t-kx+\phi
\]

যেখানে \(\phi\) initial phase।

একই সময়ে \(x\) দূরত্বে থাকা দুই particle-এর phase difference:

\[
\Delta\phi=k\Delta x
=\frac{2\pi}{\lambda}\Delta x
\]

অতএব,

\[
\boxed{\Delta\phi=\frac{2\pi\Delta x}{\lambda}}
\]

বিশেষ ক্ষেত্রে:

\[
\begin{array}{c|c}
\text{Path difference} & \text{Phase difference}\\
\hline
\lambda & 2\pi\\
\lambda/2 & \pi\\
\lambda/4 & \pi/2
\end{array}
\]

দুই point-এর phase difference \(2n\pi\) হলে তারা same phase-এ এবং \((2n+1)\pi\) হলে opposite phase-এ থাকে।

---

## 4. Progressive wave equation

ধরা যাক origin-এ particle-এর vibration:

\[
y(0,t)=a\sin\omega t
\]

Wave যদি \(+x\) দিকে \(v\) velocity-তে চলে, তবে \(x\) point-এ disturbance পৌঁছাতে সময় লাগে

\[
\frac{x}{v}
\]

সুতরাং \(x\) point-এর oscillation origin-এর তুলনায় \(x/v\) সময় পিছিয়ে:

\[
y(x,t)=a\sin\omega\left(t-\frac{x}{v}\right)
\]

যেহেতু

\[
\frac{\omega}{v}=k=\frac{2\pi}{\lambda},
\]

তাই

\[
\boxed{y=a\sin(\omega t-kx)}
\]

অথবা,

\[
\boxed{y=a\sin\frac{2\pi}{\lambda}(vt-x)}
\]

এটি \(+x\) direction-এর wave।

\(-x\) direction-এ গেলে:

\[
\boxed{y=a\sin(\omega t+kx)}
\]

### Direction চিনবার shortcut

\[
f(x-vt)\Rightarrow +x\text{ direction}
\]

\[
f(x+vt)\Rightarrow -x\text{ direction}
\]

তবে sine-এর ভেতরের পুরো expression negative করে ফেললে phase বদলাতে পারে—তাই শুধু একটি sign দেখে নয়, \(x\mp vt\) form-এ এনে direction বিচার করাই নিরাপদ।

---

## 5. Particle velocity বনাম wave velocity

এখানে সবচেয়ে বেশি confusion হয়।

- Wave velocity \(v\): wave pattern কত দ্রুত সামনে যাচ্ছে।
- Particle velocity \(u\): medium-এর কোনো particle কত দ্রুত উপরে-নিচে বা সামনে-পেছনে oscillate করছে।

ধরি,

\[
y=a\sin(\omega t-kx)
\]

তখন particle velocity:

\[
u=\frac{\partial y}{\partial t}
=a\omega\cos(\omega t-kx)
\]

অর্থাৎ,

\[
\boxed{u=a\omega\cos(\omega t-kx)}
\]

Maximum particle velocity:

\[
\boxed{u_{\max}=a\omega=\frac{2\pi av}{\lambda}}
\]

Particle acceleration:

\[
\alpha=\frac{\partial^2y}{\partial t^2}
=-a\omega^2\sin(\omega t-kx)
\]

যেহেতু \(y=a\sin(\omega t-kx)\),

\[
\boxed{\alpha=-\omega^2y}
\]

Maximum acceleration:

\[
\boxed{\alpha_{\max}=a\omega^2}
\]

এতে বোঝা যায় medium-এর প্রতিটি particle SHM করে।

### Particle velocity ও slope-এর relation

\[
\frac{\partial y}{\partial x}
=-ak\cos(\omega t-kx)
\]

আর

\[
\frac{\partial y}{\partial t}
=a\omega\cos(\omega t-kx)
\]

কারণ \(\omega=vk\),

\[
\boxed{\frac{\partial y}{\partial t}
=-v\frac{\partial y}{\partial x}}
\]

অর্থাৎ \(+x\)-গামী wave-এর জন্য

\[
\boxed{u=-v\frac{\partial y}{\partial x}}
\]

\(-x\)-গামী wave-এর জন্য:

\[
\boxed{u=+v\frac{\partial y}{\partial x}}
\]

তোমার নোটে এই relation-এর মূল ধারণা ঠিক ছিল।

---

## 6. One-dimensional wave equation

ধরি,

\[
y=a\sin(\omega t-kx)
\]

দুইবার \(x\) অনুযায়ী differentiate করলে:

\[
\frac{\partial^2y}{\partial x^2}=-k^2y
\]

দুইবার \(t\) অনুযায়ী differentiate করলে:

\[
\frac{\partial^2y}{\partial t^2}=-\omega^2y
\]

যেহেতু

\[
v=\frac{\omega}{k}
\quad\Rightarrow\quad
\omega^2=v^2k^2,
\]

তাই

\[
\boxed{\frac{\partial^2y}{\partial t^2}
=v^2\frac{\partial^2y}{\partial x^2}}
\]

অথবা,

\[
\boxed{\frac{\partial^2y}{\partial x^2}
=\frac1{v^2}\frac{\partial^2y}{\partial t^2}}
\]

এটাই one-dimensional wave equation।

### কোনো function wave equation-এর solution কি না কীভাবে দেখব?

Function-টির জন্য \(\partial^2 y/\partial t^2\) এবং \(\partial^2 y/\partial x^2\) বের করো। যদি একটি constant positive \(v^2\)-এর জন্য

\[
\frac{\partial^2y}{\partial t^2}
=v^2\frac{\partial^2y}{\partial x^2}
\]

হয়, তাহলে সেটি wave equation-এর solution।

General solution:

\[
\boxed{y(x,t)=F(x-vt)+G(x+vt)}
\]

এখানে \(F\) ডানদিকে এবং \(G\) বামদিকে চলা arbitrary-shaped wave।

---

## 7. Progressive wave-এর energy

Wave-এর প্রতিটি particle SHM করে। তাই particle-এর energy থেকেই wave energy পাওয়া যায়।

ধরি,

\[
y=a\sin(\omega t-kx)
\]

Particle velocity:

\[
u=a\omega\cos(\omega t-kx)
\]

### Kinetic energy density

প্রতি unit volume-এর mass হলো \(\rho\)। তাই

\[
K=\frac12\rho u^2
\]

অতএব,

\[
\boxed{K=\frac12\rho a^2\omega^2
\cos^2(\omega t-kx)}
\]

### Potential energy density

Small-amplitude harmonic mechanical wave-এর জন্য

\[
\boxed{U=\frac12\rho v^2
\left(\frac{\partial y}{\partial x}\right)^2}
\]

এখন,

\[
\frac{\partial y}{\partial x}
=-ak\cos(\omega t-kx)
\]

এবং \(vk=\omega\), তাই

\[
\boxed{U=\frac12\rho a^2\omega^2
\cos^2(\omega t-kx)}
\]

অর্থাৎ progressive sinusoidal wave-এ একই point ও একই সময়ে

\[
\boxed{K=U}
\]

তাই total instantaneous energy density:

\[
E=K+U
\]

\[
\boxed{E=\rho a^2\omega^2
\cos^2(\omega t-kx)}
\]

এর time average:

\[
\left\langle\cos^2\theta\right\rangle=\frac12
\]

সুতরাং

\[
\boxed{\langle E\rangle
=\frac12\rho a^2\omega^2}
\]

অথবা,

\[
\boxed{\langle E\rangle
=2\pi^2\rho a^2f^2}
\]

তোমার নোটে \(2\pi^2\rho n^2a^2\) লেখা—এখানে \(n\) frequency বোঝালে formula ঠিক।

> Correction: instantaneous energy density constant নয়; এটি position ও time-এর সঙ্গে বদলায়। কিন্তু একটি পূর্ণ cycle-এর average constant।

---

## 8. Intensity of wave

Intensity হলো wave propagation-এর perpendicular unit area দিয়ে প্রতি second-এ transfer হওয়া average energy:

\[
\boxed{I=\frac{\text{energy}}{\text{area}\times\text{time}}}
\]

অর্থাৎ power per unit area:

\[
\boxed{I=\frac{P}{A}}
\]

\(t\) সময়ে wave \(vt\) দূরত্ব যায়। Cross-sectional area \(A\) হলে swept volume:

\[
V=Avt
\]

সুতরাং transported energy:

\[
\text{Energy}=\langle E\rangle Avt
\]

তাই

\[
I=\frac{\langle E\rangle Avt}{At}
=\langle E\rangle v
\]

অতএব,

\[
\boxed{I=\frac12\rho a^2\omega^2v}
\]

বা,

\[
\boxed{I=2\pi^2\rho a^2f^2v}
\]

একই medium ও একই frequency হলে

\[
\boxed{I\propto a^2}
\]

তাই amplitude দ্বিগুণ হলে intensity চারগুণ।

---

## 9. Stationary বা standing wave

একই amplitude, frequency ও wavelength-এর দুটি wave বিপরীত দিকে চললে superposition-এর ফলে stationary wave তৈরি হয়।

ধরি,

\[
y_1=a\sin(\omega t-kx)
\]

\[
y_2=a\sin(\omega t+kx)
\]

তাহলে

\[
y=y_1+y_2
\]

Identity:

\[
\sin A+\sin B
=2\sin\frac{A+B}{2}\cos\frac{A-B}{2}
\]

ব্যবহার করলে

\[
\boxed{y=2a\sin\omega t\cos kx}
\]

এখানে

\[
\boxed{A(x)=2a|\cos kx|}
\]

হলো position-dependent amplitude। এজন্য standing wave সামনে এগোয় না; বিভিন্ন position-এর particle বিভিন্ন amplitude-এ oscillate করে।

### Node

যেখানে amplitude শূন্য:

\[
\cos kx=0
\]

\[
kx=\frac{(2n+1)\pi}{2}
\]

\[
\boxed{x=\frac{(2n+1)\lambda}{4}}
\]

অর্থাৎ,

\[
\frac{\lambda}{4},\frac{3\lambda}{4},
\frac{5\lambda}{4},\ldots
\]

### Antinode

যেখানে amplitude maximum \(2a\):

\[
|\cos kx|=1
\]

\[
kx=n\pi
\]

\[
\boxed{x=\frac{n\lambda}{2}}
\]

অর্থাৎ,

\[
0,\frac{\lambda}{2},\lambda,
\frac{3\lambda}{2},\ldots
\]

### Distances

\[
\boxed{\text{Adjacent nodes-এর distance}=\frac{\lambda}{2}}
\]

\[
\boxed{\text{Adjacent antinodes-এর distance}=\frac{\lambda}{2}}
\]

\[
\boxed{\text{Nearest node–antinode distance}=\frac{\lambda}{4}}
\]

### Particle velocity in stationary wave

\[
y=2a\cos kx\sin\omega t
\]

তাই

\[
u=\frac{\partial y}{\partial t}
=2a\omega\cos kx\cos\omega t
\]

Node-এ \(\cos kx=0\), তাই particle সবসময় স্থির। Antinode-এ maximum particle speed সবচেয়ে বেশি:

\[
u_{\max}=2a\omega
\]

### Phase relation

একই দুই adjacent node-এর মধ্যবর্তী সব particle same phase-এ vibrate করে। পাশাপাশি দুই segment-এর particle opposite phase-এ vibrate করে।

### Stationary wave energy transfer করে কি?

Ideal stationary wave-এ net average energy transfer নেই। Energy localভাবে kinetic এবং potential form-এর মধ্যে exchange হয়।

---

## 10. Progressive এবং stationary wave-এর পার্থক্য

| Progressive wave | Stationary wave |
|---|---|
| Wave pattern সামনে যায় | Pattern স্থির থাকে |
| Net energy transfer হয় | Net average energy transfer হয় না |
| Ideal case-এ amplitude সব জায়গায় সমান | Amplitude position অনুযায়ী বদলায় |
| Permanent node/antinode নেই | Fixed node ও antinode আছে |
| Phase continuously position-এর সঙ্গে বদলায় | এক loop-এর particles same phase-এ থাকে |

---

## 11. Group velocity ও phase velocity

একটি sinusoidal component:

\[
y=a\sin(\omega t-kx)
\]

এর constant phase condition:

\[
\omega t-kx=\text{constant}
\]

Differentiating:

\[
\omega-k\frac{dx}{dt}=0
\]

তাই phase velocity:

\[
\boxed{v_p=\frac{\omega}{k}}
\]

এটি individual crest বা phase কত দ্রুত চলছে।

### Group velocity

কাছাকাছি frequency ও wave number-এর দুটি wave superpose করলে wave packet বা group তৈরি হয়:

\[
y_1=a\sin(\omega_1t-k_1x)
\]

\[
y_2=a\sin(\omega_2t-k_2x)
\]

Superposition-এর envelope term:

\[
2a\cos\left(
\frac{\Delta\omega}{2}t-\frac{\Delta k}{2}x
\right)
\]

Envelope-এর velocity:

\[
v_g=\frac{\Delta\omega}{\Delta k}
\]

Limit নিলে:

\[
\boxed{v_g=\frac{d\omega}{dk}}
\]

এটাই group velocity। সাধারণভাবে wave packet, information ও energy group velocity-তে চলে।

### \(v_g=v_p-\lambda\,dv_p/d\lambda\) derivation

\[
\omega=kv_p
\]

তাই

\[
v_g=\frac{d\omega}{dk}
=v_p+k\frac{dv_p}{dk}
\]

এখন

\[
k=\frac{2\pi}{\lambda}
\quad\Rightarrow\quad
\frac{d\lambda}{dk}=-\frac{\lambda}{k}
\]

তাই

\[
k\frac{dv_p}{dk}
=k\frac{dv_p}{d\lambda}
\frac{d\lambda}{dk}
=-\lambda\frac{dv_p}{d\lambda}
\]

অতএব,

\[
\boxed{v_g=v_p-\lambda\frac{dv_p}{d\lambda}}
\]

### Dispersion

- Non-dispersive medium: \(v_p\) frequency বা wavelength-এর উপর নির্ভর করে না। তখন \(v_g=v_p\)।
- Dispersive medium: \(v_p\) frequency-এর সঙ্গে বদলায়। তখন সাধারণত \(v_g\neq v_p\), ফলে wave packet ছড়িয়ে যেতে পারে।

---

## 12. Doppler effect

Source এবং listener-এর relative motion-এর কারণে observed frequency বদলে যাওয়াকে Doppler effect বলে।

Sound-এর speed medium-এর তুলনায় \(v\), source velocity \(v_s\), observer velocity \(v_o\), emitted frequency \(f\) হলে:

\[
\boxed{
f'=f\frac{v\pm v_o}{v\mp v_s}
}
\]

Sign মুখস্থ করার সহজ নিয়ম:

- Observer source-এর দিকে গেলে numerator-এ \(+v_o\)
- Observer source থেকে দূরে গেলে numerator-এ \(-v_o\)
- Source observer-এর দিকে গেলে denominator-এ \(-v_s\)
- Source দূরে গেলে denominator-এ \(+v_s\)

দুজন কাছে এলে observed frequency বাড়ে; দূরে গেলে কমে।

### Source moving, observer stationary

Source observer-এর দিকে গেলে সামনে effective wavelength:

\[
\lambda'= \frac{v-v_s}{f}
\]

তাই

\[
\boxed{f'=\frac{v}{v-v_s}f}
\]

Source দূরে গেলে:

\[
\boxed{f'=\frac{v}{v+v_s}f}
\]

### Observer moving, source stationary

Observer source-এর দিকে গেলে wavefront encounter speed \(v+v_o\):

\[
\boxed{f'=f\frac{v+v_o}{v}}
\]

Observer দূরে গেলে:

\[
\boxed{f'=f\frac{v-v_o}{v}}
\]

---

## 13. Acoustics

Acoustics হলো sound-এর production, propagation, reception এবং control-এর বিজ্ঞান।

### Architectural acoustics

Room, auditorium, classroom বা hall-এ sound যেন পরিষ্কার এবং comfortableভাবে শোনা যায়—এটি নিয়ে architectural acoustics কাজ করে।

একটি ভালো auditorium-এর জন্য সাধারণত প্রয়োজন:

- যথাযথ loudness
- সব জায়গায় প্রায় uniform sound distribution
- উপযুক্ত reverberation time
- echo না থাকা
- external ও internal noise control
- focusing বা dead spot না থাকা
- resonance নিয়ন্ত্রণ

### Reverberation বনাম echo

Sound source বন্ধ হওয়ার পর multiple reflection-এর কারণে sound কিছু সময় ধরে টিকে থাকাকে reverberation বলে।

যদি reflected sound original sound থেকে আলাদা করে শোনা যায়, সেটি echo। মানুষের auditory persistence প্রায় \(0.1\,s\)। তাই distinct echo-এর জন্য reflected sound-এর delay সাধারণত অন্তত \(0.1\,s\) হতে হয়।

Sound speed \(340\,m\,s^{-1}\) ধরলে reflector-এর minimum distance:

\[
2d=v(0.1)
\]

\[
d\approx17\,m
\]

### Reverberation time

Source বন্ধ হওয়ার পর sound intensity \(10^{-6}\) গুণ, অর্থাৎ level \(60\,dB\) কমতে যে সময় লাগে, তাকে reverberation time বলে।

Sabine formula:

\[
\boxed{T_R=\frac{0.161V}{A}}
\]

SI unit-এ:

- \(V\)=room volume in \(m^3\)
- \(A=\sum \alpha_iS_i\)=total absorption in sabin
- \(\alpha_i\)=absorption coefficient
- \(S_i\)=corresponding surface area

---

## 14. তোমার নোটের গুরুত্বপূর্ণ correction

1. \(u=dy/dx\) নয়। Particle velocity:

\[
\boxed{u=\frac{\partial y}{\partial t}}
\]

আর \(dy/dx\) হলো wave profile-এর slope।

2. Progressive wave-এর kinetic energy density ও potential energy density:

\[
K=U=\frac12\rho a^2\omega^2\cos^2(\omega t-kx)
\]

তাই instantaneous total energy density:

\[
E=\rho a^2\omega^2\cos^2(\omega t-kx)
\]

কিন্তু average:

\[
\langle E\rangle=\frac12\rho a^2\omega^2
\]

3. Standing wave-এর equation কোন trigonometric form দিয়ে শুরু করা হয়েছে তার ওপর node ও antinode-এর coordinate বদলাতে পারে। তোমার equation

\[
y=2a\cos kx\sin\omega t
\]

হলে \(x=0\) antinode। কিন্তু

\[
y=2a\sin kx\cos\omega t
\]

হলে \(x=0\) node। Physics একই; শুধু origin নির্বাচন আলাদা।

4. Group velocity-এর সঠিক মূল formula:

\[
\boxed{v_g=\frac{d\omega}{dk}}
\]

5. ছবিতে acceleration of particle অংশে spatial derivative ও time derivative মিশে গেছে। Particle acceleration অবশ্যই:

\[
\boxed{\alpha=\frac{\partial^2y}{\partial t^2}=-\omega^2y}
\]

---

## পুরো chapter-এর formula sheet

\[
v=f\lambda=\frac{\omega}{k}
\]

\[
k=\frac{2\pi}{\lambda},\qquad
\omega=2\pi f
\]

\[
y=a\sin(\omega t-kx)
\quad(+x)
\]

\[
y=a\sin(\omega t+kx)
\quad(-x)
\]

\[
u=\frac{\partial y}{\partial t},
\qquad
u_{\max}=a\omega
\]

\[
\alpha=-\omega^2y,
\qquad
\alpha_{\max}=a\omega^2
\]

\[
\frac{\partial^2y}{\partial t^2}
=v^2\frac{\partial^2y}{\partial x^2}
\]

\[
\langle E\rangle
=\frac12\rho a^2\omega^2
\]

\[
I=\frac12\rho a^2\omega^2v
\]

\[
y_{\text{standing}}
=2a\cos kx\sin\omega t
\]

\[
x_{\text{node}}=\frac{(2n+1)\lambda}{4}
\]

\[
x_{\text{antinode}}=\frac{n\lambda}{2}
\]

\[
v_p=\frac{\omega}{k}
\]

\[
v_g=\frac{d\omega}{dk}
=v_p-\lambda\frac{dv_p}{d\lambda}
\]

\[
f'=f\frac{v\pm v_o}{v\mp v_s}
\]

এই corrected explanation-টাই তোমার ১৯টি ছবির ধারাবাহিক, পূর্ণাঙ্গ version।

