Saad
Requirements :-
Min 16 GB RAM
RTX 3090/4090 GPU ( Optional )
You Can Run Through

Own Device If Compatible
VPS ( Watch Video )
COMMANDS 👇🏻
apt update && apt install -y sudo
sudo apt update && sudo apt install -y python3 python3-venv python3-pip curl wget screen git lsof && curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add - && echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list && sudo apt update && sudo apt install -y yarn
curl -sSL https://raw.githubusercontent.com/ABHIEBA/Gensyn/main/node.sh | bash
cd $HOME && [ -d rl-swarm ] && rm -rf rl-swarm; git clone https://github.com/ABHIEBA/rl-swarm.git && cd rl-swarm
screen -S gensyn
python3 -m venv .venv && . .venv/bin/activate && ./run_rl_swarm.sh
Dashboard: https://dashboard.gensyn.ai/
