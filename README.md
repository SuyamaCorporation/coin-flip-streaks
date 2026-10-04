# Coin Flip Streak Probability Visualizer

Simulate up to 10,000 coin flips, visualize the sequence with longest-streak highlighting, run 1,000 Monte Carlo trials to histogram the streak distribution, and compare to the theoretical log₂(N) expectation.

## Features
- Flip slider from 10 to 10,000 flips; instant simulation or frame-by-frame animation at 5–60 FPS
- Sequence display with the longest streak highlighted in color (green for Heads, red for Tails)
- Live coin display with running streak counter during animation mode
- Monte Carlo button runs 1,000 full simulations and plots a histogram with theoretical overlay
- Stats: current longest streak, heads/tails count, theoretical expected streak, MC mean/median/max

## Usage
Set the number of flips with the slider and click Simulate for an instant result, or click Animate to watch flips happen live (adjust FPS with the speed slider). Click Monte Carlo to run 1,000 simulations and see the distribution. The yellow bar on the histogram marks the theoretical expected longest streak (≈ log₂N).
