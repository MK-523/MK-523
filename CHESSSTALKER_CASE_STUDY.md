# ChessStalker

[Live product](https://chessstalker.com/) | Opponent analysis for Lichess, Chess.com, and FIDE players

**Role:** Co-Founder

ChessStalker turns a player's public game history into a preparation workflow: opening tendencies, recurring mistakes, head-to-head records, time-pressure patterns, Stockfish-backed evaluations, and practice against a Twin Bot modeled on the opponent's observed style.

## Product scope

- Searches Lichess and Chess.com usernames and FIDE players from one interface.
- Supports opening-repertoire analysis, blunder patterns, endgame statistics, head-to-head comparison, Nemesis detection, Stalker Score, and Stockfish depth-25 analysis.
- The live product reports more than 82K online analyses and 20K FIDE analyses.
- [Used throughout a 29-minute video by Hikaru Nakamura](https://www.youtube.com/watch?v=lHFyIkjdGf0) on his official YouTube channel.

## My contributions

- Implemented Monte Carlo simulations over rating-conditioned decision trees to estimate player win probabilities.
- Built opening-tree analytics that surface likely continuations and variation-level performance for opponent preparation.
- Co-founded and iterated on the product from analysis concept through a live preparation workflow.

## Why I built it

As a US Chess Top 100 Junior, I wanted opponent preparation to be faster and more systematic than manually opening games one at a time. ChessStalker packages the repetitive search, comparison, and engine-analysis work into a single product that produces an immediately usable scouting report.

## Product decisions

- **Multi-platform identity:** players may compete under different online usernames and a separate FIDE identity, so the product keeps platform-specific workflows while presenting a consistent analysis experience.
- **Actionable output:** results are organized around preparation decisions rather than raw game statistics alone.
- **No-signup entry point:** the free workflow lets a player run an analysis without creating an account.
- **Transparent scope:** ChessStalker is an independent product and is not affiliated with Lichess.org or Chess.com.

## Public evidence

- [Live product](https://chessstalker.com/)
- [Technical FAQ and feature descriptions](https://chessstalker.com/faq)
- [Hikaru Nakamura's official feature](https://www.youtube.com/watch?v=lHFyIkjdGf0)
- [Live Hikaru analysis](https://chessstalker.com/chesscom/hikaru)

The production implementation is proprietary. This case study documents the product, my role, and the technical work that can be discussed publicly without exposing source code, credentials, or private infrastructure.
