FROM athenaos/base-pentest:latest

#ENV PUSER=athena
ENV PUSER=root
#ENV PUID=1000

RUN pacman -Syyu --noconfirm --needed \
aeskeyfind afflib air analyzemft autopsy bmap-tools bulk-extractor chainsaw chkrootkit \
dc3dd dcfldd dftimewolf dumpzilla exiflooter fs-nyarl galleta guymager hashdb \
imagemounter indxcarver jefferson jpegdump lazagne libfvde limeaide log-file-parser \
loki-scanner mac-robber magicrescue maltego mdbtools memdump mft2csv mftcarver \
mimipenguin networkminer ntdsxtract parse-evtx pcapfex pdf-parser peepdf pev \
python-oletools reglookup regripper rekall rifiuti2 scalpel stringsifter \
volatility-extra

WORKDIR /root

# Running as login shell
CMD ["/bin/fish", "-l"]
