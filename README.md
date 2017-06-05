# tmux-slack-status
Get your slack status updated to your tmux status bar.

## Installation

Clone this repo. Copy or symlink slack-notifier into $HOME/bin or somewhere in your $PATH.

Generate a legacy slack token and put it in a .slack file or export it as $SLACK_TOKEN

run 'pip install -r requirements.txt'

Add #(slack-notifier) to your .tmux.conf status_bar left or right line.

