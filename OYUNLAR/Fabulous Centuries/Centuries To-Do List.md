
Öncelikler:
 1- Oynanış ve Sistemizasyon
 2- Sunum ve hikaye
 3- Quality of Life cart curt

- [ ] Eldeki karta tıklanınca drawmanger inspecti çağır
- [ ] Slotları eklemek ve silmek için tuşlara çevirebil bunu inspect menüsüne entegre et
- [ ] CardSlot'un eldeyken ve masadaykenki tıklanabilirlerini düzenle, metinlerini ve tüm credential'larını prefabe ekle
- [ ] Tüm kartları yazlnız foto ve çerçeveli halleriyle çıktıla ve kalan tüm kart detaylarını oyunun içinde geliştirilebilir kıl
- [ ] Yeni scene oluştur, bu sahnede her destedeki kartı bir kere çağırıp kopyalarını öldüren bir script olacak, bunları bir gridli klasöre instantiate edecek 100 kartı birden bam diye. Ardından bunları kopyalayıp game mode dan çıkıp yapıştırcaksın. Eğer oyuna güncelleme gelirse, bunu her yaptığında otomatik kodeks güncellemesi olacak. Bunları cardslot formunda çağıracak ve kondisyonları falan üstlerinde canlanmalarını sağlayacaksın.
- [ ] Binalar seçimini ve mantığını ekle
- [ ] Oyuna placeholder bir menü ekle ve oyun modu seçilebilir olsun, normal vs, centuries vs, gibi.
- [ ] Oyuna multiplayer mantığını ekle developmenta devam etmeden önce
good luck bro

- [ ] Sound effects (yaratık sesleri, deste ve buton sesleri, ambians sesleri not music)
- [ ] Menü: Oyna (lobiler ekranına getirir, centuries veya normal mod lobileri katılabilir şekilde gözükür), Player Stats (oyuncu datasının collected bir form halinde sunuluşu), Codex (aşağıda da genişletilebilir bir ekran olarak her kart ve kural bloğu bulunacak), Ayarlar (sesler, dil(notyet), yeee kinda that), Hakkında, Çık
- [ ] Oyunun visual studio applicationa gerçekten bağlanması ve benim bilgisayarda herkesin verisinin işlenmesi
- [ ] Oyun 2v2 sistemi (2 sütun daha eklenir, bina ve tur mekanikleri için ses kaydını dinle)
- [ ] Oyun 1v1v1v1, please god no 


Fabulous centuries, Finishing the game task order  
  
0- Create overhaul list for imporvement  
Execute improvements on a vide scale and drop inspector instructions for implementation  
  
1- Game manager complete design.  
  
2- Deck manager and centuries logic complete design.  
3- Main menu complete design, profile etc.  
  
4- Turn manager complete design with open room to online compatibility  
  
5- Card object complete design and inspector  
  
6- Condition complete design.  
  
7- Map and place manager complete design.  
  
8- Card system+ Effect system base, position checking base, All cards display screen, Codex exporter tools.  
  
9- Action system for every ability and action. Place, turn, condition, kind, all getting together.  
  
10- Online server implementation.  
  
11- Data recorder, sender and exporter based on user card use, turn data everything, also the profile.  
  
12- Achievements.  
  
13- Wildcards expansion.  
  
Design consideration:  
Map anomalies, environment differences


# Prompts

Working on X, Y, Z codes, build a card inspector logic. Create a card inspector code, which will handle all the behaviors and displays on card inspector panel. On this panel the ALL INFORMATIONS will be displayed in FORMATS. This happens when a card is clicked on this button, and the inspection panel will open to display the information and possible buttons.  
  
Make a grid system for the card game. This will function to keep relative track and for placement management of the cards. No two card can be placed on the same grid, but rather a solution is found. There are 6 columns and 4 rows. The first two rows are the red teams and the second two rows are the blue teams girds. If the left up corner is 0-0 and the right bottom corner is 3-5 of the grid, then the rows 1-2 are considered the front rows and the 0-3 are considered the back rows. A red player can only place their cards on the red side and the blue team only place on blue side. If a card is attempted to be placed, the PlacementManager checks if the slot is available. If a card is trying to be placed on an already occupied slot, call the occupants CardSlot's replacement function, giving it information of its empty neighboring grid slots. On occupants CardSlot, the card will check its movability (this will be implemented later) and depending on the given information from the PlacementManager, the occupant displays direction arrows and a button to kill. These arrows signify possible movement to the empty neighboring slots (opponent slots are NOT considered available). If the player clicks on one of the available arrows, the choice is returned to the placement manager and the occupant is moved to that direction while the new card is placed on that slot. If the kill button is chosen, then the occupant CardSlot calls to kill the card and leaves the slot for the newly placed one. A card on the table can call the PlacementManager to move from one slot to another. In that case, with the same process accept the destroying itself button, the available neighbors are given to the slot to display arrows, then back tot the PlacementManager to actually move the card.  
  
I want you to implement a logic for conditions. First examine X, Y, Z and create a system like this: A condition is scriptable element on its own later to be integrated to the action system (just to plan ahead, dont do anything major on this now). Condition objects can be dragged and placed on cards. When placed on a card, they are locked into that cards conditions list and cannot be moved. A newly created card instantiates its conditions on it at the beginning. A condition, if not spawned independently but rather directly on a card, can not be dragged and dropped. An another script may call to instantiate or destroy a condition on top of an existing card. Conditions, while existing on a card, remain nested at a layout list.  
  
CardSlot should be like this: A CardSlot is created with a call function, giving the CardScriptable of that card as parameter. CardScriptable data gets loaded to the card, then if its on hand it goes into hand state. If its directly played, it goes to the Play state. On hand state is simple, card layout is adjusted by calling its OnHand animation and the drag and drop works as normal. Play state is complicated. The card automatically lerps to the cursor position and then the snapping on the grid logic gets followed on placement attempt. Then the OnTable layout is called from the animator.

On GameManager script, implement this logic: The turn counter is being tracked and depending on the turn count or the raunt count the game manager triggers some effects. First of all, it keeps track of the player hand scripts of both sides and their deck choices as as well. When the game starts, it limits the card playing amount for the players. FUUUCK işte movement ve kart oynama hakkı de geç şimdilik allahaşkına