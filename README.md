# Credibility Engine

An AI-powered system that:
- Collects tweets from key users
- Detects predictions
- Verifies them against reality
- Tracks long-term credibility

## Architecture
Twikit → Amazon Bedrock → S3 → SQLite

## Features
- Social prediction detection
- Automated claim extraction
- Historical verification
- Credibility scoring

## Setup
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
