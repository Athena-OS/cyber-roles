FROM athenaos/base-pentest:latest

#ENV PUSER=athena
ENV PUSER=root
#ENV PUID=1000

RUN pacman -Syyu --noconfirm --needed \
42zip blacknurse bonesi davoset ddosify dhcpig dnsdrdos etherflood fhttp goldeneye habu \
httpbog hulk hwk hyde iaxflood impulse inviteflood isip katana-framework mausezahn nbname \
network-app-stress-tester nkiller2 ntpdos openvas phpstress pwnloris pyersinia rspet \
shitflood slowloris slowloris-py smod sps synflood synner t50 tcgetkey thc-ssl-dos \
torshammer ufonet wifi-pumpkin wreckuests zizzania

WORKDIR /root

# Running as login shell
CMD ["/bin/fish", "-l"]
