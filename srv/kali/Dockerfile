FROM kalilinux/kali-rolling:latest

RUN apt-get update && apt-get install -y metasploit-framework
# RUN apt-get -y dist-upgrade && apt-get install -y kali-linux-top10 && apt-get install -y kali-linux-forensic && apt-get install -y kali-linux-web
RUN apt-get clean && rm -rf /var/lib/apt/lists/* 
