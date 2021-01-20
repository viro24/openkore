General path options:
--control=PATHS           Specify folders in which to look for control files.
--tables=PATHS            Specify folders in which to look for table files.
--plugins=PATH            Specify folders in which to look for plugins.
For the above options, you can specify multiple paths, delimited by ';'.

--fields=PATH             Specify the folder in which to look for field files.
--logs=PATH               Save log files in the specified folder.

Control files lookup options:
--config=FILENAME         Which config.txt to use.
--mon_control=FILENAME    Which mon_control.txt to use.
--items_control=FILENAME  Which items_control.txt to use.
--shop=FILENAME           Which shop.txt to use.
--chat-log=FILENAME       Which chat log file to use.
--console-log=FILENAME    Which console log file to use.
--storage-log=FILENAME    Which storage log file to use.
--sys=FILENAME            Which sys.txt to use.

Other options:
--interface=NAME          Which interface to use at startup.
--lockdown                Disable potentially insecure features.
--ai                      Starting AI mode (on, manual, off) (default: on)
--command=COMMAND         Initial command to place on the AI queue
--help                    Displays this help message.
--version                 Displays the program version.

Developer options:
--no-connect              Do not connect to any servers.

Options for the 'profiles' plugin:
   --profile=PROFILE      profile to use (default: prompt)

cpan       Protocol::WebSocket     JSON::Any    JSON::PP      Wx     File::ReadBackwards
   
   
============================= Available commands ==============================
a            Attack a monster.
achieve      Achievement management
ai           Enable/disable AI.
aiv          Display current AI sequences.
al           Display the status of your vending shop.
analysis
arrowcraft   Create Arrows.
as           Stop attacking a monster.
attendance   Attendance System.
au           Display possible commands for auction.
aua          Adds an item to the auction.
aub          Bids an auction.
auc          Creates an auction.
aud          Deletes an auction.
aue          Ends an auction.
aui          Displays your auction info.
aur          Removes item from auction.
aus          Search for an auction according to the criteria.
auth         (Un)authorize a user for using Kore chat commands.
autobuy      Initiate auto-buy AI sequence.
autosell     Auto-sell AI sequence.
autostorage  Initiate auto-storage AI sequence.
bangbang     Does a bangbang body turn.
bank         Banking management.
bg           Send a message in the battlegrounds chat.
bingbing     Does a bingbing body turn.
bl
booking      Interact with a group booking
bs
buy          Buy an item from the current NPC shop
buyer
c            Chat in the public chat.
canceltransaction
captcha      Answer captcha
card         Card compounding.
cart         Cart management
cash
cashbuy
changeProfile  Changes profile
charselect   Ask server to exit to the character selection screen.
chat         Chat room management.
chist        Display last few entries from the chat log.
cil          Clear the item log.
cl           Chat room management.
clan
clearlog     Clear the chat log.
cln
closebuyershop
closebuyshop
closeshop    Close your vending shop.
cm
conf         Change a configuration key
connect
cook         Attempt to create a food item.
create
damage       Damage taken report
dead
deal         Trade items with another player.
debug        Toggle debug on/off.
dl           List items in the current deal.
doridori     Does a doridori head turn.
drop         Drop an item from the inventory.
dump         Dump the current packet receive buffer and quit.
dumpnow      Dump the current packet receive buffer without quitting.
e            Show emotion.
east         Move 5 steps east.
elemental
eq           Equip an item.
eqsw         Equip an switch item.
eval         Evaluate a Perl expression.
exp          Experience report.
falcon       Falcon status.
follow       Follow another player.
friend       Friend management.
g            Chat in the guild chat.
getcharname
getplayerinfo  Get the name of the player with specified ID
gmb
gmbb
gmcreate
gmdc
gmhide
gmkickall
gmlb
gmlbb
gmlnb
gmmapmove
gmmute
gmnb
gmrecall
gmremove
gmresetskill
gmresetstate
gmsummon
gmunmute
gmwarpto
guild        Guild management.
help         Help displays commands
homun        Interact with homunculus.
i            Display inventory items.
iconf        edit items_control.txt
identify     Identify an unindentified item.
ignore       Ignore a user (block their messages).
ihist        Displays last few entries of the item log.
il           Display items on the ground.
im           Use item on monster.
ip           Use item on player.
is           Use item on yourself.
kill         Attack another player (PVP/GVG only).
look         Look in a certain direction.
lookp        Look at a certain player.
m            Displays Mail commands.
ma           Mail & Attachment.
macro        Macro plugin
map          Map plugin
mconf        edit mon_control.txt
md           Deletes a Mail.
memo         Save current position for warp portal.
merc         Interact with Mercenary.
merge
mi           Opens Mailbox.
misc_conf    Send to Server Misc Configuration.
ml           List monsters that are on screen.
mo           Open a mail.
move         Move your character.
mr           Returns the mail to the sender.
ms           Sends Mail.
mw           Interacts with mail box window.
nl           List NPCs that are on screen.
north        Move 5 steps north.
northeast    Move 5 steps northeast.
northwest    Move 5 steps northwest.
openbuyershop
openshop     Open your vending shop.
p            Chat in the party chat.
party        Party management.
pause        Delay the next console commands.
pconf        edit pickupitems.txt
pecopeco     Pecopeco status.
pet          Pet management.
petl         List pets that are on screen.
pl           List players that are on screen.
plugin       Control plugins.
pm           Send a private message.
pml          Quick PM list.
portals      List portals that are on screen.
priconf      edit priority.txt
quest        Quest management.
quit         Exit this program.
rc           Reload source code files.
rc2
refine       Refine an item (using the whitesmith skill)
refineui
reload       Reload configuration files.
relog        Log out then log in again.
repair       Repair player's items.
respawn      Respawn back to the save point.
revive       Use of the 'Token Of Siegfried' to self-revive.
rodex        rodex use (Ragnarok Online Delivery Express)
roulette     Roulette System.
s            Display character status.
sconf        edit shop.txt
searchstore  Universal catalog command
sell         Sell items to an NPC.
send         Send a raw packet to the server.
showeq       Equipment showing.
sit          Sit down.
skills       Skills management.
sl           Use skill on location.
sll          Display a list of slaves in your immediate area.
sm           Use skill on monster.
south        Move 5 steps south.
southeast    Move 5 steps southeast.
southwest    Move 5 steps southwest.
sp           Use skill on player.
spells       List area effect spells on screen.
ss           Use skill on self.
ssl          Use skill on slave.
ssp          Use skill on ground spell.
st           Display stats.
stand        Stand up.
stat_add     Add status point.
storage      Handle items in Kafra storage.
store        Display shop items from NPC.
switch_equips  Switch Equips
switchconf   Switch configuration file.
take         Take an item from the ground.
talk         Manually talk to an NPC.
talknpc      Send a sequence of responses to an NPC.
tank         Tank for a player.
tele         Teleport to a random location.
testshop     Show what your vending shop would sell.
timeout      Set a timeout.
top10        Displays top10 ranking.
uneq         Unequp an item.
uneqsw       Unequp an switch item.
vender       Buy items from vending shops.
verbose      Toggle verbose on/off.
version      Display the version of openkore.
vl           List nearby vending shops.
vs           Display the status of your vending shop.
warp         Open warp portal.
weight       Gives a report about your inventory weight.
west         Move 5 steps west.
where        Shows your current location.
who          Display the number of people on the current server.
whoami       Display your character and account ID.
===============================================================================
