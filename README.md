# Prevent colab for disconnecting automatically when training a model

This script prevent colab for disconnecting automatically during the training. It use a simple mouse click event from the pynput library. 

We trigger mouse click from our computer using the library. In this way colab listen to the click event and keep the session active till the training is ended.

Note that if you counsume the weekly hours for your account, colab will automatically disconnect your session.