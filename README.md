# Woodmont Trail Counter

A low-power LoRaWAN sensor that counts trail visitors at Woodmont Park. Counts only; no images or personal data.

Project page: https://woodmontfriends.org/trail-counter/

## Architecture

PIR (Grove) → SenseCAP S2110 (XIAO RP2040, RS485/Modbus) → SenseCAP S2100 data logger → LoRaWAN → SenseCAP M2 gateway (rec center poolhouse) → cloud

## Status

First pass / design sketch. See `index.html` for the plan and open questions.

## Layout

- `index.html` – project page (GitHub Pages)
- `firmware/` – RP2040 counter firmware (not started)
