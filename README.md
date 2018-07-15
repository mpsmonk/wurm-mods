# wurm-mods
HoTA Statues mod WU adds a HoTA statues in craft


Reward mod WU
Mod create table REWARDS in wurmitems.db. Supports the following commands:
/rewardget - explain using that command 
/rewardget Key - if it key exists in db then you receive item corresponding that key .
/rewardset - explain using that command. if power <2 then receive message about it
/rewardset TemplateId,Ql,Material,Rarity - create item in db and key
Or you can active hand on any item and select "reward" then you will see message window for more comfortable creating reward
/rewardlist - for looking all exists rewards

Reward mod v2 WU
Do somethink like v1, but adding auxiliary data fields and support only question window

Bids mod WU
Mod for holding draws for players. Supports the following commands:
/bidinfo - status at the moment
/bid sum_of_bid_in_iron_coin - start bid. For example /bid 100 - start bid with stake 1 copper
/bidup - join to bid
All info about bid will be in chat tab "Bids"
Duration of a draw can be regulated in properties.
For participation in a draw the player has to have money on the bank account


Bookshelfs mod WU
You can create a blank book: Activate leather on paper sheet and choose "create".  Need 1 leather and 10 paper sheet, uses papyrus making skill.
You can try write a book of skill: Activate reed pen on blank book and choose "Write the book". At first you must have papyrus making skill more than 50. You will receive list of skill for writing a book. If you chosen skill is lower than 70, you will fail.
In other case you will receive "tome of skill"
You can study that tome and receive small amount of skill. Activate hand on tome and choose "Study". The quality of the tome influences the number of experience in that skill.
You can put the tome in bookshelf. Activate tome on high/low bookshelf and choose "Put the book". In high you can put 20 tome, in low 10.
You can reed something from bookshelf. Activate hand on bookshelf and choose " Thumb through". You receive a small amount in skill depends of what book was put on it, or only in one of mind/logic/speed if there is no book inside.
You can create a cover book: Activate leather on paper sheet and choose "create".  Need 1 leather and 1 paper sheet, uses papyrus making skill. Simple container.


Doorbell mod WU
You can use right click on the gate and choose "Ring at doorbell" if gate on the deed, all citizen will receive message about it.
If gate not on a deed only one who attach the lock will receive it


RedBeam mod WU
You can create beam of the red light on any tile you want: Activate "hand" and click on tile then select add/remove beam.
To remove beam click on marker and select add/remove beam.

RedBeam_v2 mod WU
Auto create beam of the red light on any tile from properties at the server strartup.

Lighting storm mod WU
You can create lighting storm on any tile you want: Activate "hand" and click on tile then select add/remove storm. You can regulate frequency in properties file.
To remove beam click on marker and select add/remove storm. 


EmptyTrashBin mod WU
For immediately dispose of all items inside. Activate flint and steel and click on trash heap then select Empty trash bin. You have time to think while action executing. Time on action changes in properties
