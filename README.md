

# The config for the microwaves computers (LINUX).
The counter strike global offensive for the guys who have a pc like an microwave like me.
The following guide increased for me the fps, before i played with 30 fps and now im playing like 80 fps.

## The launch options
You can set the launch options on the steam. 

 1. Open the steam
 2. With right click on the game, go to the properties

3. Go to the general tab and click on the set launch options button and copy paste the code and click the ok button![enter image description here](https://cdn.discordapp.com/attachments/697056555421532239/706857034779328572/Screenshot_from_2020-05-04_14-17-14.png)

This is the following launch options

    gamemoderun %command% -noheap -noaafonts -noipx -cpuCount=4 -noforce -noforcemaccel -noforcemparms -noforcemspd -noforcercemspd -freq 60 -refresh 60 +exec autoexec +cl_interp 0 +cl_interp_ratio 1 +violence_hblood 0 -threads 4 -console -nohltv -w 640 -h 480 +mat_queue_mode 2 -disable_d3d9ex -r_remulate_g -softparticlesdefaultoff +fps_max 30 -nojoy -high -fullscreen +mat_disable_fancy_blending 1 +cl_forcepreload 1 -limitvsconst -forcenovsync +r_dynamic 0 -novid

You can install the gamemoderun on the linux
Run the following commands from a new Terminal (`ctrl` + `alt` + `t`) window:

 

 > `sudo add-apt-repository ppa:samoilov-lex/gamemode`
>  `sudo apt install gamemode`

![enter image description here](https://cdn.discordapp.com/attachments/697056555421532239/706853430701850670/Screenshot_from_2020-05-04_14-02-59.png)

And press the button Enter to continue
![enter image description here](https://cdn.discordapp.com/attachments/697056555421532239/706853789428220025/Screenshot_from_2020-05-04_14-04-03.png)


You can run the command `sudo apt-get update` and install the gamemode
![enter image description here](https://cdn.discordapp.com/attachments/697056555421532239/706854227120488509/Screenshot_from_2020-05-04_14-05-50.png)

## Autoexec
You can create an autoexec. You need to put your autoexec.cfg on this filepath:

   
> `~/.steam/steam/steamapps/common/Counter-Strike Global Offensive/csgo/cfg`

![enter image description here](https://cdn.discordapp.com/attachments/697056555421532239/706860214787375144/Screenshot_from_2020-05-04_14-29-35.png)

You can go to the cfg filepath from the Files![enter image description here](https://cdn.discordapp.com/attachments/697056555421532239/706860784554213406/Screenshot_from_2020-05-04_14-31-58.png)

This is the autoexec.cfg
![enter image description here](https://cdn.discordapp.com/attachments/697056555421532239/706861446067257393/Screenshot_from_2020-05-04_14-34-24.png)
There is the source of the [autoexec.cfg](https://github.com/Khantanjil/CsgoConfig/blob/master/autoexec.cfg)

## Options inside of the game
Editing...
