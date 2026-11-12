# Hi, I'm Ray 👋

### I take ideas from 0 to 1 with AI, and ship things that actually run.

I'm AI-native: AI writes much of the code, and I spend my own effort on what to build, what "working" means, and checking that it does. Everything below is live or running, with tests or checks behind it.

## What I've launched

| | Outcome | Where AI fits |
|---|---|---|
| 🎮 [**jiang-hu-game**](https://github.com/Rayjiao123/jiang-hu-game) | A live game anyone can [play on a phone](https://jiang-hu-game-production.up.railway.app), in English, 中文 and ไทย. Tests, CI, rate limits and a daily spend cap. | AI voices the characters, the server decides every outcome, and a second model scores the first. |
| 🌡️ [**WeatherAgents**](https://github.com/Rayjiao123/WeatherAgents) | An automated system running continuously on live Polymarket temperature markets: forecast, trade (paper), score. | Rules are written down before the data, and the forecast never sees prices. |
| 🏀 [**nba-opinion-lab**](https://github.com/Rayjiao123/nba-opinion-lab) | A research system running daily that tests whether fans, bloggers and Reddit can beat NBA prop betting lines. | An LLM reads the opinions and never predicts. Every output is validated before it is stored. |

## How I get from 0 to 1

- **Start from the outcome.** What has to be true when it's done: a live URL, an agent running on its own, a number I can check.
- **Own the judgement, delegate the typing.** I design, review, play-test and file the bugs. AI does much of the building.
- **Guard the model.** Validate its output, test with a fake model, add a second model as judge, cap the spend.
- **Ship, then measure honestly,** including the results I don't like.

Python · FastAPI · JavaScript · SQL · LLM APIs and evals · Claude Code
