# The Polka Dot Generator 🎨

Welcome to  the beginner-friendly project - " The Polka Dot Generator   "

Crafted and taught by **Shreya Malogi!** 🌐


 [![GitHub stars](https://img.shields.io/github/stars/shreyamalogi/Polka-Dot-Generator.svg?style=social)](https://github.com/shreyamalogi/https://github.com/shreyamalogi/Polka-Dot-Generator/stargazers)

### Project Details: 💻🌐📅✍️


- **Functionality:** Generates stunning Hirst-inspired paintings using Python's Turtle module.
- **Tech Stack:** `Python`, `turtle-GUI`
- **Author:** [@shreyamalogi](https://github.com/shreyamalogi/)
- **Year of Project:** 2021
  
---




# Table of Contents 📚

1. [Introduction](#introduction-)
2. [Prerequisites](#prerequisites-%EF%B8%8F)
3. [Installation](#installation-)
4. [Running the Script](#running-the-script-%EF%B8%8F)
5. [Customizing Your Painting](#customizing-your-painting-)
6. [Understanding the Code](#understanding-the-code-)


## Introduction 🎨

This Python script utilizes the Turtle module to create a stunning Hirst-inspired painting. Let's embark on your artistic coding journey! 🚀

## Prerequisites 🛠️

Before you dive in, make sure you have Python installed on your machine. If not, you can download it [here](https://www.python.org/downloads/).

## Installation 🐢

You'll need the `turtle` module to run this script. Install it using:

```bash
pip install PythonTurtle
```

## Running the Script ▶️

1. Open the script in your favorite Python environment.
2. Run the script. This will launch the Turtle graphics window.

## Customizing Your Painting 🎨

The script uses a predefined `color_list` variable containing RGB tuples. Feel free to customize this list to create your unique color palette. 🌈

## Understanding the Code 🤓

Let's break down the script:

```python
import turtle as turtle_module
import random

# ... (other imports)

turtle_module.colormode(255)
myrtle = turtle_module.Turtle()
myrtle.speed("fastest")
myrtle.penup()
myrtle.hideturtle()

color_list = [(202, 164, 109), (238, 240, 245), ... , (176, 192, 209)]

# ... (more code)

screen = turtle_module.Screen()
screen.exitonclick()
```

- `colormode(255)`: Configures Turtle to use RGB values ranging from 0 to 255.
- `Turtle()`: Creates a Turtle object named `myrtle`.
- `speed("fastest")`: Sets the drawing speed to the fastest.
- `penup()`: Lifts the pen, so no drawing occurs when moving.
- `hideturtle()`: Hides the turtle cursor.

---
#### Running the Painting Loop 🔄

The script uses a loop to draw dots on the canvas:

```python
for dot_count in range(1, number_of_dots + 1):
    myrtle.dot(20, random.choice(color_list))
    myrtle.forward(50)

    if dot_count % 10 == 0:
        # ... (code for changing direction and position)
```

## Exploring Your Art 🌌

The script will create a unique Hirst-inspired artwork. Experiment with colors and settings to make it your own! Enjoy the creative process! 🎉

## Contribution- Show Your Support (Star This) ⭐🌟📜✨

Feel the magic within you? Contribute to this enchanting spellbook and make it even more magical. Don't forget to star the project! ⭐🌟

## License 🕊️

This project is enchanted under the spell of the MIT License. Share the magic responsibly!

MIT License

Copyright (c) 2021 Shreya Malogi

Stay Enchanted! 🌍💙
