I upload .ipynb file that includes steps.

# Google Colab making Android .apk (Kivy and KivyMD) #

1- !pip install buildozer

2- !pip install cython==0.29.33

3- !sudo apt-get update
   !sudo apt install -y git zip unzip openjdk-17-jdk python3-pip autoconf libtool pkg-config zlib1g-dev libncurses5-dev libncursesw5-dev libtinfo5 cmake libffi-dev libssl-dev --fix-missing

4- !buildozer init

5- !buildozer -v android debug

[*] it tested, June 2026, works well. Stars of the Sky | Reşat Berk
