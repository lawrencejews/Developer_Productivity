## Developer Productivity.
- Install Docker locally on your laptop
- Start Docker locally and test: docker run -d -p 80:80 docker/getting-started
- Create a Dockerfile
- Build a Docker container in the current directory: docker build -t ubuntu . 
- Then RUN: docker run --rm -it ubuntu bash  
### Ansible
- Cloud key storage server.
- Ansible has a top level and task level.
- This can be used to set-up your development configurations.
- Create an environment like docker.
- Run ansible-playbook ansible.yaml
- Task only Node -> ansible-playbook -t node ansible.yml
### tmux
- man tmux
 - Start -> tmux
 - Stop server -> tmux kill-server
 - Check running sessions -> tmux list-sessions
 - End -> control + D
 - Detach sessions -> tmux new-session -d
### Bash
#### Directory depth and a cheat-sheet langauge explorer
- Root navigation && path view
- Chmod +x tmux-sessionizer bash file
- Run this bash file in tmux