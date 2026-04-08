# BESS Fair Demo – TwinCAT/Beckhoff

PLC program developed in Beckhoff TwinCAT (Structured Text) for a BESS (Battery Energy Storage System) demo unit designed for trade fairs and events.

## Description

This project is a stripped-down/demo version of a real BESS system. Its sole functionality is communication with the HMI (Human-Machine Interface) to control the state and color of the system's LEDs based on the states defined from the HMI itself.

It does not include energy control logic or real hardware communication — it is an interactive visual representation designed for live demonstrations.

## Features

- Bidirectional communication with HMI via ADS/TwinCAT
- LED state and color control driven by HMI variables
- Simplified logic (demo/capped version)
- Developed in Structured Text (IEC 61131-3)

## Tech Stack

- Beckhoff TwinCAT 3
- Structured Text (ST)
- ADS Communication
