# code:
# imports
import time
from random import randrange
import webbrowser


def first_floor():
    print('Up here at the sencod floor we see a close door and a open door.In open door we see a table and chair'
          'on the chair there was a key!  I think we need it to open something in the lighthouse')
    time.sleep(5)
    print('there is nothing here. let\'s go up')
    print('wait i hear a noise')
    print('ahh th-i-i-s l-i-i-g-hh-ht h-o-u-s-e i-is...')
    time.sleep(3)
    print('that was spooky ! brr')
    second_floor()


# noinspection PyUnusedLocal,PyShadowingNames
def randomly_generate_villages():
    village = int(1)
    village = village + 1
    print(name, 'has gone through ', village, 'villages')
    if village == 1:
        print('you have going through 1 village, gone through 20 villages to earn the title: Village Explorer')
    elif village <= 20:
        print('Congratulations! You have earned the title of: Village Explorer, gone through 20 villages to earn the '
              'title:Regular Visitor')
    elif village <= 50:
        print('Congratulations! You have earned the title of: Regular Visitor ,gone through 20 villages to earn the '
              'title:Addict Village personality')
    elif village <= 100:
        print('Congratulations you have earned the title of: Addict Village personality! The highest level')

    print('":n" are the location number , don\'t get confused')
    time.sleep(5)
    o = randrange(1, 5)
    if o == 1:
        print('the map looks like this:\n market:1, farmland:2,\n municipal office:3\n war struck zone:4 \n'
              'houses : 5 ')
    elif o == 2:
        print('the map looks like this \n farmland:1 municipal office:2\n houses:3 \n market : 4 \n war struck zone '
              ': 5 ')
    elif o == 3:
        print('municipal office : 1 ,\n war struck zone : 2 \n, farmland : 3 \n houses: 4 \n market :5 ')
    else:
        print('houses:1 ,\n market:2 \n , municipal office :3\n  war-struck zone:4 \n farmland:5 \n')
        time.sleep(5)
    location = input('Do you want to go to "houses","market","municipal office" ,"war-struck zone" or "farmland"')
    if location == 'houses':
        houses()
    elif location == 'market':
        market()
    elif location == 'municipal office':
        municipal_office()
    elif location == 'war-struck zone':
        war_struck_zone()
    else:
        farmland()


def houses():
    print('let\'s go to the houses ')
    time.sleep(5)
    print('we see 2 storey buildings with funny roofs on top')
    print('we see through the windows that the houses have a bed,bookshelf swords and a chest ')
    dwarf = input('Do you want to break in a house and loot a chest ?')
    if dwarf == 'no':
        print('we\'ll break in a house some other day')
        wello = input(
            'where do you want to go to? you can say "market", "farmland", "municipal office" or war struck zone')
        if wello == 'market':
            market()
        elif wello == 'farmland':
            farmland()
        elif wello == 'municipal office':
            municipal_office()
        else:
            war_struck_zone()
    else:
        break_in_a_house()


def market():
    print('lets go to the market')
    time.sleep(4)
    print('I really have to say that the market is filled with talent')
    time.sleep(3)
    print('There are blacksmiths , cobblers , fruit sellers tailors , fire work makers and so many more')
    time.sleep(3)
    print('with the villagers are animals such as lamas, cats , dogs and so on')
    print('There is the municipal office!')
    oklahama = input('Do you want to go to the municipal office?')
    if oklahama == 'y':
        municipal_office()
    else:
        operation = input('where do you want to go to? you can say , "farmland", "houses" or "war struck zone"')
        if operation == 'farmland':
            farmland()
        elif operation == 'houses':
            houses()
        else:
            war_struck_zone()


# -----------------------------------------------------------------------------------------------------------------------
def municipal_office():
    print('lets go to the municipal office')
    time.sleep(5)
    print('lets meet the village chief of the village ')
    time.sleep(5)
    print('Chief: Hello travellers how are you?\n its almost tea time , lets have a nice tea')
    print('we sit and have tea with him, we ask him his name ')
    nma4 = randrange(1, 9)
    if nma4 == 1:
        print('Chief: My name is John')
    elif nma4 == 2:
        print('Chief: My name is Michael')
    elif nma4 == 3:
        print('Chief: My name is Abdullah')
    elif nma4 == 5:
        print('Chief: My name is Robert')
    elif nma4 == 6:
        print('Chief: My name is William')


def war_struck_zone():
    print('a villager tells us :')
    print('villager:the war struck zone is the area which is constantly attacked with zombies,tarantulas and skeletons')
    print('this happens to all villages as mobs attack here ')
    time.sleep(5)
    print('we see so many graves of the villagers in the war struck zone')
    time.sleep(5)
    print('look that is the obsidian door')
    time.sleep(2)
    print('its getting dark ')
    re12 = input(
        'do you want to "sleep" or go to the "obsidian door", "market", "farmland", "municipal office" or "houses"? '
        'or look for '
        'another "village"?')
    if re12 == "obsidian door":
        time.sleep(2)
        print(name, 'has accomplished the mission')
    elif re12 == "market":
        market()
    elif re12 == "farmland":
        farmland()
    elif re12 == "municipal office":
        municipal_office()
    elif re12 == "houses":
        houses()
    elif re12 == 'sleep':
        sleep()
    else:
        go_for_another_village()


def sleep():
    print('leaving for  sleep')
    print('look that is the obsidian door')
    time.sleep(2)
    print('its getting dark ')
    re12 = input(
        'do you want to  go to the "obsidian door", "market", "farmland", "municipal office" or "houses"? or look for '
        'another "village"?')
    if re12 == "obsidian door":
        time.sleep(2)
        print(name, 'has accomplished the mission')
    elif re12 == "market":
        market()
    elif re12 == "farmland":
        farmland()
    elif re12 == "municipal office":
        municipal_office()
    elif re12 == "houses":
        houses()

    else:
        go_for_another_village()


def farmland():
    print('lets look the farmland')
    time.sleep(5)
    print('The farmlands are the areas that have livestock such as cows,sheep, chicken and even bees!')
    print('The farmers farm crops like wheat ,rice and pulses ')
    time.sleep(5)
    print('look! they do terrace farming, that is smart')
    time.sleep(5)
    print('They also grow roses, daisy,jasmine and many more ... and they sell it in the market!')
    wenzi = input('now where do you want to go?"market", "hoses", "municipal office" or war struck zone')
    if wenzi == 'market':
        market()
    elif wenzi == 'farmland':
        farmland()
    elif wenzi == 'municipal office':
        municipal_office()
    else:
        war_struck_zone()


def go_for_another_village():
    print('lets find another village')
    time.sleep(20)
    print('a village!')
    time.sleep(5)
    randomly_generate_villages()


# noinspection PyUnusedLocal
def break_in_a_house():
    print('lets break in the house')
    time.sleep(5)
    print('we break the door and we find that the owner of this house is not here anymore')
    time.sleep(3)
    print('we break open the chest and we find :')
    random_loot = randrange(1, 6)
    if random_loot == 1:
        print('5 diamonds , 1 golden egg and two lepaz jewels\n(lepaz is a rare stone found over the destiny door)')
        # noinspection PyUnusedLocal,PyShadowingNames
    elif random_loot == 2:
        print('1 diamond ')
        print('a waste loot')
    elif random_loot == 3:
        print('2 diamonds, 3 lepaz jewels')
    elif random_loot == 4:
        print('3 diamonds and a diamond axe')
    print('let\'s go back to the village ')
    wello = input('where do you want to go to? you can say "market", "farmland", "municipal office" or war struck zone')
    if wello == 'market':
        market()
    elif wello == 'farmland':
        farmland()
    elif wello == 'municipal office':
        municipal_office()
    else:
        war_struck_zone()


def third_floor():
    print('there are windows and a door outside with creepy songs that come from a phone hanging on top.')
    print('this is the location where the bulb is ')
    time.sleep(4)
    print('wait! , the is a screw without a nut')
    time.sleep(1)
    print('let\'s try to fix the nut')
    time.sleep(4)
    print('it worked! the nut fixed ')
    time.sleep(1)
    print('the noise is coming again...')
    time.sleep(3)
    print('tt-hha-ankk you t-travellers..')
    print('I think it is very creepy in here ')
    print('look the door became the obsidian door!')
    time.sleep(2)
    print(name, 'has accomplished the mission')
    time.sleep(2)
    opinion = input('do you want to go through the "obsidian door" or inform and "thank the lady"?')
    if opinion == 'thank the lady':
        print('ok, let\'s go and thank the lady')
        time.sleep(10)
        print('we reach the caravan, the lady was playing a violin ')
        time.sleep(3)
        print('oh! travellers did you fix the light house and drove away the ghost')
        print('we said yes to her and she fell silent')
        time.sleep(3)
        print('Woman: Thank you , next time do try the other paths as there are more adventurers there ')
        time.sleep(5)
        print('look , the caravan became the obsidian door ')
        time.sleep(2)
        print(name, 'has accomplished the mission')
        time.sleep(2)
    else:
        print('ok ,the journey is over !')
        time.sleep(5)


def second_floor():
    print("there is nothing but the lighthouse machine and the stairs for the top floor")
    time.sleep(5)
    print("wait! there is a keyhole in the machine ! ")
    arre = input('should we put the key in the keyhole')
    if arre == 'yes':
        print('It worked and  the machine gave us a nut(screw)!')
        time.sleep(3)
        print('i think it will help us in some way')
        another = input(' do you want to go "up" or "down" or "get out of here?')
        if another == 'up':
            third_floor()
        elif another == 'down':
            first_floor()
        else:
            time.sleep(5)


def light_house():
    print('we bang the door and the door breaks ')
    print('we walk inside')
    print('the lighthouse is dark and creepy. There is only one bulb in the first floor but does not work at all.'
          "There is a stair case right in front of us and  an old table at the right side .On the left of the room is a"
          "shelf full of creepy toys that are moving a bit.")
    waka = input('do you want to go to the "first floor" or "look around here"?')
    if waka == 'first floor':
        print('let\'s go to the first floor ')
        first_floor()
        second_floor()


# checking if your answer pleased the troll
def check_guess(guess, answer):
    still_guessing = True
    attempt = 0
    while still_guessing and attempt < 3:
        if guess.lower() == answer.lower():
            print('Correct answer')
            break
        else:
            if attempt < 2:
                guess = input('sorry wrong answer , Try again')
            attempt = attempt + 1
            # noinspection PyUnusedLocal
            guess = guess
            break
    if attempt == 3:
        print("you are dead")
        print(name, 'was slain by troll')
        time.sleep(2)


# mountains , dirt path
def dirt_path():
    print('we walk towards a bridge and see a cottage ')
    time.sleep(10)
    print('It is locked , wait there is a key !')
    open_the = input('would you like to open the door?')
    if open_the == 'yes':
        print('look there is the obsidian door ! ')
        roar = input('would you like to open the  obsidian door?')
        if roar == 'yes':
            time.sleep(2)
            print(name, 'has accomplished the mission')
            time.sleep(2)
        else:
            print('ok, let go out of the house and walk away from the cottage')
            time.sleep(5)
            print('look we see a village')
            randomly_generate_villages()
    else:
        print('ok, lets go to the bridge')
        print('look ! there is someone! lets say hi to him')
        time.sleep(5)
        print('person: hi weary travellers would you like to come to my cottage?')
        print('i say yes to him. he takes us to the same cottage we saw ')
        time.sleep(10)
        print('he opens the door and it becomes the obsidian door!')
        luku = input('do you want to go through the obsidian door?')
        if luku == 'yes':
            time.sleep(2)
            print(name, 'has accomplished the mission')
            time.sleep(2)
        else:
            randomly_generate_villages()


def another_adventure():
    print('we bid goodbye to the woman ')
    time.sleep(5)
    print('look! we see an eagle , let\'s follow it !')
    time.sleep(5)
    print('we follow it for a few minutes')
    print('we see 3 interesting things')
    time.sleep(1)
    house_matter()


def house_matter():
    ted = input('do you want to go  to the "trunk",check the "mailbox" or look at the "sign"?   ')
    if ted == 'trunk':
        trunk()
    elif ted == 'mailbox':
        mailbox()
    else:
        sign()


# work here
def trunk():
    print('let\'s go to the trunk ')
    time.sleep(5)
    print('we open the door,\n its tiny but big enough for a table and chair')
    time.sleep(3)
    print('we see stairs near the table')
    time.sleep(3)
    print('we see that it leads to a underground path')
    time.sleep(3)
    print('the underground path is steep ,\n we fall into the path   ')
    time.sleep(3)
    print('we walk on the  path for a while')
    time.sleep(3)
    print('we see a dark room with no door , we can hear creepy noises')
    time.sleep(3)
    print('we enter the dark room \n we see stairs that lead to the underground floor ')
    edge = input('do you want to look at this "floor" or go "down stairs"')
    if edge == 'floor':
        look()
    else:
        under_ground_floor()


def under_ground_floor():
    print('we are now on the underground floor')
    print('we are looking for the four stones ')
    time.sleep(3)
    print('we see an ender  sleeping  ')
    time.sleep(5)
    print('we walk and see the four stones lets get it')
    time.sleep(5)
    print('but careful ,we soon get it and look more around here')
    time.sleep(5)
    what = input('do you have the key that Mr.polly gave')
    if what == 'yes':
        print('oh!wow you got it now we will see where we need it')
        time.sleep(5)
        print('we hear the sound of someone crying')
        time.sleep(3)
        print('it is a princess!')
        time.sleep(1)
        print('Princess: Shh , There is a dragon, underneath the dragon is the portal to my palace!')
        wer14 = input('should we help the "princess" or find the "obsidian door"?')
        if wer14 == 'princess':
            print('lets help the princess ')
            time.sleep(5)
            print('we sneak over the large body of the dragon who had his back turned upon us ')
            time.sleep(3)
            print('we climb over the large body of the dragon and jump to the front side upon which we find a large '
                  'obsidian box')
            time.sleep(4)
            print('we need to use the key!')
            print('lets unlock it go to the princess')
            time.sleep(10)
            print('we finally reach the princess')
            time.sleep(3)
            print('we unlock the cage of the princess and open the portal! ')
            time.sleep(3)
            print('look we see the king and the queen')
            print('the king sees her princess and shouts:"my princess",The queen tells us "Thank you travellers"')
            time.sleep(5)
            print('we thank the queen when  the door of the palace has became the obsidian door')
            print('we bid goodbye to the King,Queen and the princess')
            time.sleep(2)
            print('that was a enjoyable experience!')
            time.sleep(2)
            print(name, 'has accomplished the mission')
            time.sleep(2)
        else:
            print('we walk away when she screams,\n you traitors I will wake the dragon!')
            time.sleep(2)
            print('She screams and the dragon wakes up')
            time.sleep(2)
            print('He sees aus and gives a look that he does not like our presence!')
            time.sleep(2)
            print('He blasts a flame on us and..')
            time.sleep(2)
            print(name, 'was burnt to crisp by dragon')
    else:
        print('oh that ok but we can still find it right')
        time.sleep(5)
        print('we hear the sound of someone crying')
        time.sleep(3)
        print('it is a princess!')
        time.sleep(1)
        print('Princess: Shh , There is a dragon, underneath the dragon is the portal to my palace!')
        wer13 = input('should we help the "princess" or find the "obsidian door"?')
        if wer13 == 'princess':
            print('lets help the princess ')
            time.sleep(5)
            print('we sneak over the large body of the dragon who had his back turned upon us ')
            time.sleep(3)
            print('we climb over the large body of the dragon and jump to the front side upon which we find a large '
                  'obsidian box')
            time.sleep(4)
            print('look! we needed the key! but there is a way we can unlock it by using a spell')
            time.sleep(9)
            print('yes! It worked lets get it to the princess')
            time.sleep(10)
            print('we finally reach the princess')
            time.sleep(3)
            print('we unlock the cage of the princess and open the portal! ')
            time.sleep(3)
            print('look we see the king and the queen')
            print('the king sees her princess and shouts:"my princess",The queen tells us "Thank you travellers"')
            time.sleep(5)
            print('we thank the queen when  the door of the palace has became the obsidian door')
            print('we bid goodbye to the King,Queen and the princess')
            time.sleep(2)
            print('that was a enjoyable experience!')
            time.sleep(2)
            print(name, 'has accomplished the mission')
            time.sleep(2)
        else:
            print('we walk away when she screams,\n you traitors I will wake the dragon!')
            time.sleep(2)
            print('She screams and the dragon wakes up')
            time.sleep(2)
            print('He sees aus and gives a look that he does not like our presence!')
            time.sleep(2)
            print('He blasts a flame on us and..')
            time.sleep(2)
            print(name, 'was burnt to crisp by dragon')
def look():
    print('Ok let\'s look around  the room! ')
    print('The room is Dark with a door hook without a door, There is a creepy thing in the other corner with glowing '
          'eyes which were giving us a snarl,I suppose we should go down stairs')
    under_ground_floor()


def mailbox():
    print('oh we open the mail box and see the key')
    time.sleep(2)
    print('perhaps we should keep the key ')
    print("we keep the key in our pocks for now")
    op12 = input('do you want to look at "sign" or go to the "trunk"  ')
    if op12 == 'sign':
        sign()
    else:
        trunk()


def road():
    print("we walk on the road ")
    print('we see a man ')
    time.sleep(2)
    print('we walk over to the man')
    print("Man:hi travellers my name is Mr.polly")
    print('he gives us a box  ')
    time.sleep(3)
    print('we pull the box it does not open')
    time.sleep(5)
    print('oh!we have the key we open the box and see that there is a gold necklace ')


def sign():
    print('we read the sign\n Oh! its for us ')
    time.sleep(2)
    print('it says "we are going to find someone ')
    op12 = input('do you want to look at "mailbox" or go to the "trunk"  ')
    if op12 == 'mailbox':
        mailbox()
    else:
        trunk()


# mountains , flower garden
def daisy_path():
    prnt = input('we see two paths , do you want to go to the "rose path" or the "daisy path"')
    if prnt == 'daisy path':
        print('let\'s go by the daisy path')
        time.sleep(5)
        print('look we see a river and a bridge across it ')
        loro = input('do you want to cross the "bridge" or "stay" here?')
        if loro == 'bridge':
            print('let\'s go by the bridge ')
            time.sleep(3)
            print('look a village ! ')
            time.sleep(2)
            randomly_generate_villages()
        else:
            print('let\'s stay here ')
            time.sleep(5)
            print('LOOK ! thats a TROLL!')
            time.sleep(3)
            print('Troll: ANSWER MY QUESTIONS! ')
            dhoop = input('do yo-u-u ww-aaa-n-tt t-oo a--an-swerr hiis questions?')
            if dhoop == 'yes':
                woo = randrange(1, 3)
                if woo == 1:
                    guess_1 = input('what is a fancy hat but can\'t save you fom sun or rain')
                    check_guess(guess_1, 'crown')
                    prequel()
                else:
                    guess_2 = input('what is something you see at night but runs away when it sees light?')
                    check_guess(guess_2, 'Darkness')

            else:
                time.sleep(2)
                print(name, 'was slain by Troll')
                time.sleep(2)
    else:
        print('let\'s go by the rose path ')
        time.sleep(5)
        print('look we see a village')
        randomly_generate_villages()


def prequel():
    print('oh we are saved , Good Job')
    time.sleep(3)
    print('wait i hear someone crying ')
    time.sleep(3)
    print('It\'s a princess')
    print('princess: I have lost my crown ! can you please help me? ')
    time.sleep(2)
    print('we agree to help her when there was an evil laugh!')
    print('Not the troll again!')
    time.sleep(1)
    print('answer my questions')
    w1 = input('do you want to answer his questions?')
    if w1 == 'yes':
        xi = randrange(1, 3)
        if xi == 1:
            guess_3 = input('what is a fancy hat but can\'t save you fom sun or rain')
            check_guess(guess_3, 'crown')
            last()

        else:
            guess_4 = input('what is something you see at night but runs away when it sees light?')
            check_guess(guess_4, 'Darkness')
            last()

    else:
        time.sleep(2)
        print(name, 'was slain by Troll')
        time.sleep(2)


def last():
    print('the troll gives us the crown he stole and we give it to the princess')
    print('Princess : Oh thank you ! here\'s a gift for you')
    time.sleep(2)
    print('it\'s a pink box with a magical egg in it')
    time.sleep(2)
    print('Princess: Do you want to come to the ball with me?')
    print('we say yes to her! ')
    time.sleep(5)
    print('wait the palace door becomes the obsidian door')
    time.sleep(2)
    print(name, 'accomplished the mission ')
    time.sleep(2)


# sea , boat
def beach():
    print('lets row the boat ')
    time.sleep(5)
    print('we see pandas!')
    print('wow so cute!')
    time.sleep(5)
    print('wait! we have bamboo lets feed them')
    time.sleep(5)
    x = randrange(1, 3)
    if x == 1:
        print('it was so nice feeding them')
    else:
        print('look it likes us!')
    print('lets go to the beach!')
    time.sleep(9)
    print('wow what a marvellous beach! look there is a ship! and a village nearby ')
    akshay = input(' would you like to get to the ship or get out of here?')
    if akshay == 'get to the ship':
        print('lets get to the ship ')
        time.sleep(9)
        print('look thats the captain of the ship')
        print('Captain: Ahoy Aboard young sailors let us have a dish for you')
        time.sleep(11)
        # work here:
        print('we ask the captain how the village nearby is like')
        print('Captain: Oh ! the village is ever-changing always I originate from the nearby village')
        print('look there is the obsidian door!')
        beatles = input('Do you want to go to the "obsidian door" or go to the "village"')
        if beatles == 'village':
            print('let\'s proceed to the village')
            time.sleep(5)
            randomly_generate_villages()
        else:
            print('let\'s go through the obsidian door')
            print('good bye captain ')
            time.sleep(2)
            print(name, 'has accomplished the mission')
            time.sleep(2)
    else:
        print('let\'s go to the village')
        randomly_generate_villages()


# sea , music
def music():
    print('lets follow the music')
    time.sleep(5)
    print('look! we see a pink caravan')
    print('A woman with a purple shawl came out of the caravan and spoke to us')
    print('Woman: young travellers,Do you want to have an adventure?')
    adventure = input('Do you want to have an adventure')
    if adventure == 'yes':
        print("Woman:"'good! There is a lighthouse near the beach. "I own it" she added , '
              'There is a Ghost in the light house ,Can you save the light house ?')
        time.sleep(5)
        print('we think for a while and a bravely answered her "yes we will save the light house" ')
        another_path = input('do you want to continue?')
        if another_path == 'yes':
            print('lets go!')
            time.sleep(5)
            print('look the path is becoming sandy! , we can also hear the waves ')
            time.sleep(5)
            print('now we see the beach , the sun is setting ')
            print('we take out our special watch , the watch says its 5 pm in the evening')
            time.sleep(5)
            print('we see a tall tower on the beach , it is colored with red and blue stripes and with a huge bulb '
                  'facing the sea')
            Same_thing = input('would you like to "go to the tower" or "get out of here"?')
            if Same_thing == 'go to the tower':
                print('we walk towards the light house ')
                time.sleep(5)
                print('we walk towards the door and ')
                print('sure enough there is no key ! ')
                time.sleep(2)
                print('is that a man there? why don\'t we ask him?')
                Bhagwan = input('should we ask the man ?')
                if Bhagwan == 'yes':
                    print('let\'s go to the man ')
                    time.sleep(3)
                    print('Hello sir is this light house the woman in the strange caravan\'s property')
                    time.sleep(5)
                    print('Man: I want my sailors back ')
                    print('the man fades away and we go back to the entrance ')
                    light_house()
                else:
                    light_house()
    else:
        print('as you refuse to have the adventure even i do so')
        time.sleep(5)
        print(" Woman:Don't worry i'm not sad , please continue your adventure ")
        another_adventure()


def Happy_BDay_sumati():
    print('Welcome to the special edition Zone')
    Xerxes = input('Do you want to go for the "birthday party" or "look around" this magnificent park?')
    if Xerxes == 'birthday party'.lower():
        early_Birthday_party()
    else:
        stay_in_the_park()


def space_center():
    print('woah! that\'s so high tech ')
    print('we see a rocket, ready for launch , a building with the ground staff dock ')
    kohli = input('Do you want to meet the "ground staff" or look at the "rocket" launch? ')
    if kohli == 'ground staff':
        meet_the_ground_staff()
    else:
        rocket_launch()


def meet_the_ground_staff():
    print('let\'s talk to the ground staff')
    time.sleep(5)
    print('I asked a woman with a heavy suit: ')
    print('Ma\'am , who are you? ')
    print('Woman: I am the head of the Ground staff ,coming steve! i am talking to the travellers!,\n yes , ')
    print('"we are getting ready for the launch of the r..MARY! COME HERE",A man called her and she quickly said:\n I '
          'have to go , nice to meet you! COMING STEVE! and she walked away ')
    time.sleep(3)
    print('let\'s see the rocket launch')
    rocket_launch()


def rocket_launch():
    print('let\'s go to a safe distance! ')
    time.sleep(3)
    print('we go through a series of floors in the building ')
    time.sleep(3)
    print('we reach the top floor of the building  ')
    time.sleep(3)
    print('There was a man saying : the rocket is launching in 1 minutes')
    time.sleep(3)
    print('we stick on the window and we hear the man say')
    time.sleep(3)
    print('...5...4...3...2...1...Launch')
    time.sleep(3)
    print('we hear a fizz and woosh and the rocket launches ')
    print('it soars over the sky...')
    time.sleep(3)
    print('It was a once in a lifetime view')
    time.sleep(5)
    wloip = input('do you want to meet the "ground director" or find the "obsidian door"?')
    if wloip == 'ground director':
        print('let\'s meet the ground director')
        time.sleep(3)
        print('Hello Ground director')
        print('GD: hello,hello')
        time.sleep(5)
        print('he said that he helped the astronauts and Ground staff with signals ')  # what is this bakwas change it!
        print('It\'s very tiring ')
    else:
        print('look we now see the obsidian door!')
        time.sleep(5)
        print(name, 'has accomplished the mission')


def stay_in_the_park():
    print('let\'s stay at the park')
    time.sleep(5)
    print('we stroll through the park ')
    time.sleep(3)
    print('there is nothing to DO! let\'s go by the river ')
    time.sleep(5)
    print('wait there is the snow castle , the royal family\'s castle')
    pinky_ponky = input('would you like to "meet the king" or "walk through"?')
    if pinky_ponky == 'walk through':
        print('let\'s walk further')
        time.sleep(5)
        print('look we see a space center')
        space_center()
    else:
        meet_the_royal_family()


def meet_the_royal_family():
    print('let\'s meet the royal family')
    time.sleep(5)
    print('look the royal family is in a hurry!')
    time.sleep(3)
    print('we asked the king what the matter was')
    time.sleep(2)
    print('Dont you want to go to party?')
    vc12 = input('Do you want to go to party?')
    if vc12 == 'y':
        print('King: then lets go')
        birthday_party()
    else:
        print('ok lets continue our journey')
        time.sleep(5)
        print('look we see a space center')
        space_center()


def birthday_party():
    print('let\'s run ')
    time.sleep(5)
    print('phew! we reach the building just in time ')
    time.sleep(5)
    print('yes! we reach the birthday party on time!')
    print('we reach the hall when somebody shouts!')
    print('Everybody sing! Happy Birthday to You ,Happy Birthday to You \n Happy Birthday dear_____ Happy '
          'Birthday to You')
    print('wow , what a birthday!')
    time.sleep(5)
    print('"Happy Birthday to you" we say to the girl and the girl replies\n"Thank you travellers"')
    time.sleep(3)
    print('we enjoyed the muffins , the cakes, the doughnuts and the cookies')
    time.sleep(4)
    print('I am so full i can barely walk around ')
    time.sleep(3)
    print('look,the obsidian door! ')
    time.sleep(2)
    print(name, 'has accomplished the mission')
    time.sleep(2)


def early_Birthday_party():
    print('lets go to the birthday party ')
    time.sleep(5)
    print('look that is the Building where the  birthday would happen')
    time.sleep(3)
    print('we now see a beautiful building with a poster . The poster reads Happy Birthday')
    time.sleep(2)
    print('as we enter inside the building we see many guests , there are so many people ')
    print('as we walk, we see many amusements for children.')
    print('there is a sign which says that the party will start at 6 pm')
    time.sleep(2)
    print('we look at our special watch and it says 4:43 pm ')
    akbar = input('do you want to "remain here" or go outside in the "park"?')
    if akbar == 'park':
        parky()
    else:
        birthday_party()


def stay_here_and_party():
    print('let\'s wait here  ')
    time.sleep(5)
    print('oh! the party starts at 7 , lets enjoy sitting here')
    time.sleep(10)
    print('look! it\'s almost 7 pm let\'s go near the birthday cake')
    time.sleep(5)
    print('Everybody sing! Happy Birthday to You ,Happy Birthday to You \n Happy Birthday dear_____ Happy Birthday to '
          'You')
    time.sleep(5)
    print('"Happy Birthday to you" we say to the girl and the girl replies\n"Thank you travellers"')
    time.sleep(3)
    print('we enjoyed the muffins , the cakes, the doughnuts and the cookies')
    time.sleep(4)
    print('I am so full i can barely walk around ')
    time.sleep(3)
    print('look,the obsidian door! ')
    time.sleep(2)
    print(name, 'has accomplished the mission')
    time.sleep(2)


def parky():
    print('let\'s go out')
    print('we see a lot of daisies, roses ,...and a troll ')
    print('Troll: Today I won\'t hurt anyone as I forgot my riddle ')
    time.sleep(1)
    print('what a thing!', 'any way let\'s stroll in the garden')
    time.sleep(5)
    print('wait! There are pandas munching on bamboo')
    print('there are also deers, dogs, cats , hibiscus and so many things to see')
    print('look there are so many guests going for the party')
    time.sleep(5)
    print('Woman: Don\'t want to come to the party?')
    print('We say the woman that the party stats at 7 ')
    time.sleep(3)
    print('Woman: oh! no it starts at 6 because the birthday girl becomes irritable by 9')
    time.sleep(2)
    print('oh no then we have to run fast in order to reach the party on time ')
    Please = input('Do you want to "go to the party" or "stay at the park" ?')
    if Please == 'go to the party':
        birthday_party()
    else:
        stay_in_the_park()


def dark_forest():
    print('let\'s go to the dark forest ')
    time.sleep(5)
    print('we see a lot of wood on our track')
    time.sleep(3)
    print('we hear creepy noises , let\'s walk faster')
    print('we see light! where is the light coming from?')
    time.sleep(3)
    print(" its coming from a large house\n")
    time.sleep(3)
    print('It is a large house on the top of a hill, the light is coming from a small room on the top floor')
    time.sleep(3)
    print('wait , there is a notice which reads  Caution : There are Tarantulas , Skeletons  and zombies here')
    here_comes_the_sun = input(' do you want to "continue" or "leave " the game?')
    if here_comes_the_sun == 'continue':
        print('ok , let\'s continue')
        time.sleep(3)
        tarantula = randrange(1, 25)
        if tarantula == 16:
            print('OH NO , spider! run ')
            time.sleep(5)
            print('oh no it grabbed me, RUN FOR YOUR LIFE!')
            time.sleep(3)
            print('ksss ')
            print(name, 'was killed by spider')
            time.sleep(2)
        else:
            print('lets continue')
            zombie = randrange(1, 50)
            if zombie == 24:
                print('OH NO , zombie! run ')
                time.sleep(5)
                print('oh no it grabbed me, RUN FOR YOUR LIFE!')
                time.sleep(3)
                print('grr ')
                print(name, 'was killed by zombie')
                time.sleep(2)
            else:
                print('no zombies or spiders , strange !')
                skeleton = randrange(1, 50)
                if skeleton == 1:
                    print('ah! I got an arrow! someone is shooting ! oh no it\'s the skeleton ')
                    time.sleep(3)
                    print(name, ' Was killed by skeleton')
                    time.sleep(2)
                elif skeleton == 25:
                    print('ah! I got an arrow! someone is shooting ! oh no it\'s the skeleton ')
                    time.sleep(3)
                    print(name, ' Was killed by skeleton')
                    time.sleep(2)
                elif skeleton == 16:
                    print('ah! I got an arrow! someone is shooting ! oh no it\'s the skeleton ')
                    time.sleep(3)
                    print(name, ' Was killed by skeleton')
                    time.sleep(2)
                elif skeleton == 47:
                    print('ah! I got an arrow! someone is shooting ! oh no it\'s the skeleton ')
                    time.sleep(3)
                    print(name, ' Was killed by skeleton')
                    time.sleep(2)
                elif skeleton == 29:
                    print('ah! I got an arrow! someone is shooting ! oh no it\'s the skeleton ')
                    time.sleep(3)
                    print(name, ' Was killed by skeleton')
                    time.sleep(2)
                else:
                    addy()
    else:
        print("lets go back")


def addy():
    print('strange! we found no tarantulas, zombies or skeletons ')
    time.sleep(3)
    print('maybe they were frightened of something')
    time.sleep(3)
    print('The wind is cold let\'s walk faster ')
    time.sleep(5)
    print('Phew! we reach the large house\'s gate ')
    run12 = input('Do you want to go inside the house??')
    if run12 == 'yes':
        The_dark_strange_house()
    else:
        time.sleep(2)
        print(name, 'left the game ')


# coded by sumati Datta
def The_dark_strange_house():
    print('we open the gate and walk towards the door')
    time.sleep(5)
    print('when i reach towards the knocker, the knocker knocks for itself')
    print('and the door opens instantly\n creak')
    print("we don't see much but there is a stair case on the left")
    print("the stair case leads to the third floor ")
    time.sleep(5)
    print("we look up and see five floors")
    time.sleep(1)
    google = input('would you like to clime the stair case')
    if google == 'yes':
        upstairs()
    else:
        look_around_here()


def upstairs():
    print('we see that we are not on the second floor we are on the third floor')
    time.sleep(4)
    print('we look down and see tha there is nothing on the second floor')
    time.sleep(4)
    print("we see that there is a box to our right")
    time.sleep(4)
    print('we did not need to open it,its open ')
    time.sleep(1)
    print('we look in the box and see a ring.\n perhaps we should keep it?')
    time.sleep(5)
    print('we keep the ring for now\n we soon see that there is nothing else')
    print('we see stairs and we go towards it')
    time.sleep(3)
    print('it leads us to the last floor')
    print('we see that there is someone up here \n it looks like a old man ')
    time.sleep(3)
    wikipedia = input('would you like to talk to the old man')
    if wikipedia == 'yes':
        print('oh on it is the tarantula!')
        time.sleep(2)
        print(name, 'was slain by tarantula')
        time.sleep(5)
    else:
        print('I think the man is too creepy for us  ')
        time.sleep(2)
        print('lets go to the  door in front of us ')
        print('but the door is locked we look in our pockets and see a ring')
        time.sleep(3)
        print('well we can use the ring ')
        time.sleep(3)
        print('we use the to open the door')
        print('we look inside the room it looks like someone has eaten in here')
        time.sleep(3)
        print('we walk into the room and the door shuts in front of us')
        time.sleep(3)
        print('it look we have come to the end of this adventure')
        time.sleep(3)
        print('it pulling us in')
        time.sleep(2)
        print(name, 'has accomplished the mission')
        time.sleep(2)


def look_around_here():
    print('we see a chair and a table there is a note pad on the table ')
    time.sleep(2)
    print('we keep looking and oh, there a window , in the window we see a skeleton in the garden')
    time.sleep(2)
    print('well we should go up stair now right?')
    bing = input('should go up stairs or get out of here')
    if bing == 'get out of here':
        print(name, 'has left the game')
    else:
        upstairs()


# main func
def new_func():
    print('ok let\'s check the mailbox')
    print('look we have the invitation for the special edition zone')
    time.sleep(5)
    Happy_BDay_sumati()


# main func
def sumati():
    print('we see two paths!')
    time.sleep(2)
    pathway = input('would you like to go to the dirt path or the flower garden?')
    if pathway == 'dirt path':
        dirt_path()

    else:
        daisy_path()


# main func
def suvid():
    print('lets walk to the sea.')
    time.sleep(5)
    print('we see a boat and we hear the music ')
    wistle = input('would you like to "follow the song" or would you like to "row the boat?"')
    if wistle == 'row the boat':
        beach()
    else:
        music()


# main func
def mummy():
    dark_forest()


def Destiny_Door():
    print('This Door is locked , It will unlock in the actual version')


# actual code
while True:
    print('Flint')
    time.sleep(3)
    print('Pre- release spl edition')
    time.sleep(2)
    p = randrange(1, 6)
    if p == 1:
        print('did you know you have to write what is is inside"" or else the code will go wrong?')
        print('example : "go to the beach"')
    elif p == 2:
        print('did you know that there are villages and a space center in this game?(and cities too in later '
              'versions!!)?')
    elif p == 3:
        print('to get the latest Flint go to,')
        webbrowser.open('https://github.com/Code-R-scompanies-technologies')
    elif p == 4:
        print('Do you know that the destiny door is the journey? Spoiler!')
    else:
        print('Do you know that this game was deleted from the beginning?')
    time.sleep(5)
    global name
    # noinspection PyRedeclaration
    name = input('what is your nickname?')
    suggestion = randrange(1, 4)
    if suggestion == 1 :
        print('you can try nicknames such as rentop, steve ,mininghuman65 ')
    elif suggestion == 2 :
        print('you can try nicknames such as marshmello365, addicthuman456 #xQXHvNIyrnLvEbMAYgyUSZ65HUfylw')
    else:
        print('you can try nicknames such as marsh, gaminghuman65 , Iamcoolerance')
    print('Conformation: your nick name is ', name)
    time.sleep(2)
    Door = input('Would you like to go to the "mountains",  "sea"  or  "dark forest"? ''you can also open up '
                 'the "mailbox" or open the "destiny door" ''')
    if Door == 'mountains':
        sumati()
    elif Door == 'sea':
        suvid()
    elif Door == 'dark forest':
        mummy()
    elif Door == 'mailbox':
        new_func()
    elif Door == 'destiny door':
        Destiny_Door()
    else:
        Door = input('Would you like to go to the "mountains",  "sea"  or  "dark forest"? ''you can also open up '
                     'the "mailbox" or open the "destiny door" ''')
# Made by Code/R
# anyone can change, modify the code
