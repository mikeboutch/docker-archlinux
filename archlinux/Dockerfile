FROM finalduty/archlinux
RUN curl -o /etc/pacman.d/mirrorlist "https://www.archlinux.org/mirrorlist/?country=all&protocol=https&ip_version=6&use_mirror_status=on" && \
  sed -i 's/^#//' /etc/pacman.d/mirrorlist
#RUN pacman-key --init
#RUN pacman-key --populate
#RUN pacman-key --refresh-keys
#RUN pacman -Sy  --noconfirm
#RUN pacman -S --force openssl --noconfirm
#RUN pacman -S pacman  --noconfirm
#RUN pacman-db-upgrade
RUN pacman -Syu  --noconfirm
