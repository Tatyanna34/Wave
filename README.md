# WaveStart:
Display "Welcome to Microwave"
Display "Enter cooking time (seconds):"
Input cookingTime
Display "Enter power level (1-10):"
Input powerLevel

If cookingTime <= 0 or powerLevel < 1 or powerLevel > 10:
    Display "Invalid input. Please enter valid values."
    Goto Start

Display "Cooking for " + cookingTime + " seconds at power level " + powerLevel

Turn on microwave with specified settings

Wait for cookingTime seconds

Turn off microwave

Display "Cooking complete. Enjoy your meal!"

End
