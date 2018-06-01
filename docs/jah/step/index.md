---
---

# Step

Sample based, grid controlled step sequencer

## Features

- 8 voice sample playback
- Tempo and swing
- Bottom row (row 8) optionally used to cut playback position

## Operation

- ENC1: Volume
- ENC2: Tempo (20-300 BPM)
- ENC3: Swing Amount (0-100%)

- KEY2: Stop Sequencer
- KEY3: Start Sequencer

- GRID: Edit Trigs

## Grid Support

Step is designed for varibright grids. It utilizes 8 rows and 8 or 16 columns of buttons.

## Options

Options are available in the MENU > PARAMETERS list.

Script options:

- grid width: 8 or 16
- last row cuts: yes or no. If yes, row 8 will cut playhead position.
- tempo: 20-300 BPM
- swing amount: amount to swing odd steps (0-100%)

The script exposes [../ack](ack engine parameters) for each channel.
