# servilo

this is a note or folder to help me writing down my thought on how to build my server.

i was thinking about calling it servilo, the Esperanto word for server

other names could be:
- serviicola
- serricola
- senriicola

the idea should be about a replicable server setup, maybe an ad hoc git repo, instead of s subfolder of my dotfile repo…in particular, i would like to:
- connect multiple pcs, my old laptop etc, into one cluster
- Maybe using ansible
- And an ethernet switch
- Have only 1 nas (or eventually das) as the one and only storage solution
	- Ideally i would like to have all the nodes in the cluster to have 0 hdd or ssd
	- Or eventually use nfs and share multiple storage as one
- i’m thinking about podman over docker, in order to learn the rootless way
- have nixos as the os for the nodes
- Use servilo as my server for everything 
	- Immich
	- headscale, for replacing tailscale
	- remote ventoy or similar
	- home assistant (?)
	- Disney ++
	- Disney -
	- Webriicola
	- Mail, smtp, or whatever
	- Drive
	- Sincthing
	- Qbittorrent
	- Backups
	- Podsync
	- Bookmarks (?)
	- Git
	- Tabs (?)
	- Tasks, todos
- kubernetes to be studied
- In the future, adding a mac mini m1 node to the cluster
- some kind of script or mechanism that turns on the server only by necessity and turns it off if i’m not using it
- Ovviamente accessible via ssh da anche rete esterna 
- avere un piccolo dispositivo che faccia da ponte per accendere il cluster a distanza…uno tra questi:
	- xiaomi mara
	- Raspberry pie
	- router in cui si può installare tailscale
	- Mac mini
	- Scassone vecchio acer

...
