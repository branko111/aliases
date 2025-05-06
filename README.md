# aliases  MAY 7 2025
alias a3='sudo lsof -i :3000'

alias ac='sudo cat ~/.bash_aliases'
alias an='sudo nano ~/.bash_aliases'

alias aw='cd /var/www/'

alias b='bash'

alias c='clear'
alias cc='cd ..'
alias ccc='cd ~'

alias cpw3=' scp -r /var/www/ root@192.168.1.123:/var/  '
alias cpna3=' scp -r /etc/nginx/sites-available/ root@192.168.1.123:/etc/nginx/  '
alias cpne3=' scp -r /etc/nginx/sites-enabled/ root@192.168.1.123:/etc/nginx/  '


alias cpw2=' scp -r /var/www/ root@192.168.1.122:/var/  '
alias cpna2=' scp -r /etc/nginx/sites-available/ root@192.168.1.122:/etc/nginx/  '
alias cpne2=' scp -r /etc/nginx/sites-enabled/ root@192.168.1.122:/etc/nginx/  '

alias cpw1=' scp -r /var/www/ root@192.168.1.121:/var/  '
alias cpna1=' scp -r /etc/nginx/sites-available/ root@192.168.1.121:/etc/nginx/  '
alias cpne1=' scp -r /etc/nginx/sites-enabled/ root@192.168.1.121:/etc/nginx/  '


#docker...........................................................

#dc=xxxxxx........

alias deh='echo $dc'

alias dp='docker ps -a'
alias ds=' docker start $dc '
alias de='  docker exec -it $dc bash '

alias dcl='docker container ls -a '
alias dil='docker image list '
alias dnl='docker network list '


alias dncr='docker network create  '
alias dncn='docker network connect  '
alias dnd='docker network disconnect  '


alias dni='docker inspect  '

alias dr='docker run -d '
alias drc='docker container run -d '
alias dru='docker run -itd ubuntu'

alias dS='docker stop '
alias dSS='sudo aa-remove-unknown '

alias dR='docker rm  '
alias dRR=' sudo aa-remove-unknown  '

alias dRI='docker rmi  '


#docker............END...............................................


alias dI='sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin -y'

alias dU='sudo apt-get purge -y docker-engine docker docker.io docker-ce docker-ce-cli docker-compose-plugin
sudo apt-get autoremove -y --purge docker-engine docker docker.io docker-ce docker-compose-plugin'

alias ip='hostname -I'
alias ipp='curl ifconfig.me'

alias gi='git init'
alias ga='git add .'
alias gc='git commit -m "Commit message"'
alias gp='git push origin master'
alias gs='git status'
alias gl='git log'

alias nxi=' apt install nginx -y  && se nginx    && sss nginx '

alias nxR=' ssss nginx && apt purge nginx nginx-common nginx-core -y && apt remove nginx nginx-common nginx-core -y && apt autoremove -y'


alias na='cd /etc/nginx/sites-available '
alias ne='cd /etc/nginx/sites-enabled '


# a=food


alias neh='echo $a'

alias ncb='cp /etc/nginx/sites-available/B  /etc/nginx/sites-available/$a.s111 '

alias ncbb='cp /etc/nginx/sites-available/BB  /etc/nginx/sites-available/$a.s111 '

alias nn='nano /etc/nginx/sites-available/$a.s111'
alias nc='cat  /etc/nginx/sites-available/$a.s111'
alias nl='ln -s /etc/nginx/sites-available/$a.s111  /etc/nginx/sites-enabled'

alias nmd=' mkdir /var/www/$a.s111 && cd /var/www/$a.s111 '

alias npc='pnpm create next-app  .'
alias npk=' nano package.json  '
alias npkc=' cat package.json  '

alias npi='pnpm  i'
alias npb='pnpm build'
alias npr='pnpm run'

alias np2=' pm2 start npm --name "$a" -- start '

alias nct='certbot --nginx -d $a.s111.com'

alias np2S=' pm2 stop $a '

alias nnR='rm   /etc/nginx/sites-enabled/$a && rm  /etc/nginx/sites-available/$a && rm -r /var/www/$a '


# a=food END


alias nt='apt install -y net-tools && apt install openssh-client && apt install openssh-server  && apt install  xclip  && apt install ncdu   && apt install  iputils-ping  && apt install inetutils-traceroute
  && apt install iproute2  && apt install curl && apt install telnet && apt install  dnsutils '

alias ntt=' apt install   nano '

alias pmk='pm2 kill '
alias pms='pm2 status '

alias s1='ssh root@192.168.1.121'
alias s2='ssh root@192.168.1.122'
alias s3='ssh root@192.168.1.1231'



#ssh................................................


alias sshcr='cat ~/.ssh/id_rsa.pub'
alias sshce='cat ~/.ssh/id_ed25519.pub'

alias sshca='cat ~/.ssh/authorized_keys'
alias sshck='cat ~/.ssh/known_hosts'

alias sshna='nano ~/.ssh/authorized_keys'

alias sshl=' ls -al ~/.ssh '

alias sshgr=' ssh-keygen -t rsa -b 2048 '

alias sshge=' ssh-keygen -t ed25519 '

#ssh.........END.................................



alias sd='sudo systemctl disable'
alias se='sudo systemctl enable '
alias sr='sudo systemctl restart '
alias sR='systemctl --type=service --state=running | less'
alias ss='sudo systemctl status '
alias sss='sudo systemctl start '
alias ssss='sudo systemctl stop '

alias tz='sudo timedatectl set-timezone Australia/Sydney'

alias u='sudo apt update -y'
alias uu='sudo apt update && sudo apt upgrade -y'

alias ufe='ufw enable '
alias ufs='ufw status'
alias ufl='ufw app list'

alias uf1='sudo ufw allow from 192.168.1.0/24'

alias ufap='sudo ufw allow "Apache Full" '
alias ufnx='sudo ufw allow "Nginx Full" '
alias ufop='sudo ufw allow OpenSSH'

alias ufDN='sudo ufw deny'
alias ufDL='sudo ufw delete'

alias ufDS='sudo ufw disable'
alias ufRS='sudo ufw reset'
