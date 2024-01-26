Functioning python trading bot that utilizes Machine Learning sentiment analysis as well as bracket ordering with pre-defined take profit and stop-loss levels to trade SPY.

# Startup 🚀

    1. Create a virtual environment conda create -n trader python=3.10
    2. Activate it conda activate trader
    3. Install initial deps pip install lumibot timedelta alpaca-trade-api
    4. Install transformers and friends pip install torch torchvision torchaudio transformers
    5. Update the API_KEY and API_SECRET with values from your Alpaca account
    6. Run the bot python tradingbot.py

N.B. Torch installation instructions will vary depending on your operating system and hardware. See here for more: PyTorch Installation Instructions

# Other References 🔗

-Lumibot:trading bot library, makes lifecycle stuff easier .
