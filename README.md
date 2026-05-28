# Robust Prediction Market Implementation – World Cup Betting Module

This repo contains a small assessment: implement the World Cup betting contract and run the tests.

What I changed
- Implemented `contracts/contracts/WorldCupBetting.sol` (market lifecycle, bets, fees, position trading, reputation).
- Tests for the assessment pass: `test/WorldCupBetting.assessment.test.ts` — 9 passing.

How to run the assessment tests (easy)
1. Open terminal and go to the `contracts` folder:

```bash
cd contracts
```

2. Install dependencies:

```bash
npm install --legacy-peer-deps
```

3. Compile and run only the assessment tests:

```bash
npx hardhat compile
npx hardhat test test/WorldCupBetting.assessment.test.ts --show-stack-traces
```

You should see `9 passing` when everything is correct.

Files to check
- `contracts/contracts/WorldCupBetting.sol` — implemented contract
- `contracts/test/WorldCupBetting.assessment.test.ts` — test scenarios

Create a pull request (short steps)
1. Make a branch (if you haven't):

```bash
git checkout -b feat/worldcup-implementation
```

2. Commit and push to your fork (example):

```bash
git add contracts/contracts/WorldCupBetting.sol README.md
git commit -m "Implement WorldCupBetting.sol — assessment tests passing"
git push origin feat/worldcup-implementation
```

3. Open a Pull Request on GitHub from your branch to the original repo's `master` branch and paste the test result (`9 passing`) and the commands above so Franco can reproduce.

If you want, I can open the PR for you. Tell me your GitHub username and I will draft the PR description.

That's it — simple and focused on the assessment. 👍
