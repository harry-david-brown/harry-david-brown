<p align="center">
  <img src="./assets/header-retromma.svg" width="100%" alt="Harry David Brown" />
</p>

<p align="center"><a href="https://harrydavidbrown.com">harrydavidbrown.com</a></p>

---

## [RetroMMA](https://apps.apple.com/app/id6836540151)

<img src="./assets/retromma-fight.png" width="100%" alt="RetroMMA: a fight in the cage" />

An 8-bit MMA game for iPhone and iPad. The fight is played with one thumb inside a career with two promotions, bookmaker odds and a living division of computer fighters. Godot 4.7 and GDScript. [On the App Store](https://apps.apple.com/app/id6836540151).

## Neural Sudoku solvers

<p align="center">
  <img src="./assets/header-diffusion.svg" width="100%" alt="A sudoku denoised by a discrete diffusion model, step by step" />
</p>

Small transformers (~800k parameters) trained on Sudoku. Investigating what a network needs in order to solve constraint problems that require search and backtracking.

The grid in the header is a run: the GIDD ancestral sampler with p_u = 0.2, 64 steps on an easy puzzle. Every unknown cell is resampled at every step, so wrong digits appear, survive, and get corrected near t = 0.

- [**sudoku-diffusive-uniform**](https://github.com/harry-david-brown/sudoku-diffusive-uniform): GIDD
  (masked / hybrid discrete diffusion, a port of von Rütte et al., ICML 2025) and a looped transformer, scored
  by difficulty band
- [**sudoku-diffusive-masked**](https://github.com/harry-david-brown/sudoku-diffusive-masked): masked
  diffusion, most confident cells first
- [**sudoku-autoregressive-transformer**](https://github.com/harry-david-brown/sudoku-autoregressive-transformer):
  the autoregressive baseline
- [**sudoku-norvig**](https://github.com/harry-david-brown/sudoku-norvig): Norvig's constraint-propagation
  solver

## Other Projects

- [**Static.bio**](https://static.bio/): link-in-bio pages compiled to static HTML, no client-side JS
- [**FlyrPro**](https://flyr.software/): field-sales platform for door-to-door canvassing teams; Next.js, Supabase and a Swift iOS app
- [**SnackTrack**](https://apps.apple.com/app/snacktrack-ubereats-wrapped/id6755827910): Uber Eats Wrapped from your order receipts; Node.js, PostgreSQL, Redis, React Native
- [**Clearday**](https://apps.apple.com/app/clearday-quit-vaping/id6758288385): quit-vaping iOS app; streaks, a health timeline, StoreKit 2 subscriptions
- **Monaco-Compiler**: compiler frontend in C (buffer, scanner, parser)
- **QNX-Metronome**: RTOS message passing and a resource manager on QNX Neutrino
- **ZugzwangBot**: visual chess engine
