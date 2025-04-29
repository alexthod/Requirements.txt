# Requirements.txt
python-telegram-bot==20.0
services:
  - type: web
    name: telegram-stats-bot
    env: python
    buildCommand: ""
    startCommand: "python stats_bot.py"
    envVars:
      - key: TOKEN
        value: ΒΑΛΕ_ΕΔΩ_ΤΟ_TOKEN_ΣΟΥ
        import os
TOKEN = os.getenv('TOKEN')
