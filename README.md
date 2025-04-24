# VoIP MITM Packet Sniffer and Audio Reconstructor

This Python tool performs a **Man-in-the-Middle (MITM)** attack on a VoIP call using RTP over UDP, captures the packets, and reconstructs the audio stream from the captured RTP payloads.

⚠️ **FOR EDUCATIONAL PURPOSES ONLY**

## Features

- Captures RTP packets from VoIP calls.
- Extracts and decodes audio from captured packets (G711 codec).
- Writes the audio to a `.wav` file.

## Requirements

- Python 3.7+
- `scapy`
- `pydub`
- `numpy`
- `wave`

Install with:

```bash
pip install -r requirements.txt
