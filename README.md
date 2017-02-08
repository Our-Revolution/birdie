# Birdie - A Slack bot for ~~taking over the world~~ getting stuff done.

## Prerequisites

1. [Pip](https://pip.pypa.io/en/stable/installing/)
2. [Slack bot user API token](https://my.slack.com/services/new/bot)

## Installation
1. Clone the project and cd into the project directory.

  ```
  git clone git@github.com:Our-Revolution/birdie.git
  cd birdie
  ```

2. _Optional, but best practice:_ Create a [virtual env](https://pypi.python.org/pypi/virtualenv). We use [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/) to manage our many virtual envs.
3. _Optional:_ [Activate virtualenv](https://virtualenv.pypa.io/en/stable/userguide/).
4. Install prerequisites.
  ```
  pip install -r requirements.txt
  ```
5. Set your Slack bot API token.
  ```
  export SLACK_BOT_TOKEN='slack_bot_api_token_here'
  ```
6. Set your BOT_ID.
  ```
  //get bot id
  python ./print_bot_id.py
  
  //set env
  export BOT_ID='slack_bot_id_here'
  ```
7. Run the bot!
  ```
  python ./birdie.py
  ```
