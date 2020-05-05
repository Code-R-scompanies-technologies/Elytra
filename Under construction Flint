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


def randomly_generate_villages():
    print(':n are the location number , don\'t get confused')
    time.sleep(5)
    o = randrange(1, 10)
    if o == 1:
        print('the map looks like this:\n market:1, farmland:2,\n municipal office:3\n war struck zone:4 \n'
              'houses : 5 ')
    elif o == 2:
        print('the map looks like this \n farmland:1 municipal office:2\n houses:3 \n market : 4 \n war struck zone '
              ': 5 ')
    elif o == 3:
        print('municipal office : 1 ,\n war struck zone : 2 \n, farmland : 3 \n houses: 4 \n market :5 ')


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
        time.sleep(5)
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
            guess = guess
            break
    if attempt == 3:
        print("you are dead")


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
            return
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
        # add a village


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
    print('one is a door in trunk, a mailbox and the last one is a handwritten sign ')
    ted = input('would you like to go to the "trunk"? ,the "mailbox" or the "sign" ')
    if ted == 'trunk':
        trunk()
    elif ted == 'mailbox':
        mailbox()
    else:
        sign()


# work here
def trunk():
    print('let\'s go to the Door ')
    time.sleep(5)


def mailbox():
    pass


def sign():
    pass


# mountains , flower garden
def daisy_path():
    print('lets go to the flower path')
    print('we reach a gate which seems like a garden gate with a rabbit next to it')
    time.sleep(5)
    opera = input('would you like to go inside the gate?')
    if opera == 'yes':
        print('there is a line of daisies ')
        daffodil = input('would you like to follow the daisies?')
        if daffodil == 'yes':
            print('lets follow the daisies ')
            time.sleep(10)
            print("That's a bridge!")
            chrome = input('would you like to cross the bridge?')
            if chrome == 'yes':
                print('lets cross the bridge ')
                time.sleep(10)
                print('oh we see 4 colorful stones')
                print('there is nothing here ! lets cross back')
                time.sleep(10)
                print('where are the daisies?')
                print('ha ha ha '"did you laugh? OH NO ITS A TROLL! RUN")
                time.sleep(10)
                print('Troll: You have to answer my riddle or i will kill you?')
                omlette = input('would you like to answer the riddle')
                if omlette == 'yes':
                    b = randrange(1, 3)
                    if b == 1:
                        guess_one = input('what is something you see at night but runs away when it sees light?')
                        check_guess(guess_one, 'darkness')
                    else:
                        guess_two = input('what is a fancy hat but cant protect you from sun or rain')
                        check_guess(guess_two, 'crown')
                    print('The troll lets us go and we hear someone crying ')
                    time.sleep(5)
                    print('we see a princess crying')
                    time.sleep(1)
                    print('Princess: I lost my crown can you help me?')
                    print('ha ha ha '"its the troll again! ")
                    print('Troll: You have to answer my riddle or i will kill you!')
                    lama = input('would you lake to again answer his riddle?')
                    if lama == 'yes':
                        guess_three = input('i have many hair but not a head , I can paint you the best picture')
                        check_guess(guess_three, 'paint brush')
                        print('the troll gives the crown and we run to the princess and give the crown ')
                        print('princess: would you like to come to the royal ball with me?')
                        print('we say yes to her ')
                        time.sleep(3)
                        print(' look, princess gives us a pink box ')
                        pinky = input('would you like to open the pink box?')
                        if pinky == 'yes':
                            print('Oh! its a purple egg and it opens we see two gold coins')
                        else:
                            print(' its ok  well open it later')
                        print('we go with the princess to her palace ')
                        print('we see the obsidian door!')
                        time.sleep(5)
                    else:
                        print('YOU ARE DEAD')
                        time.sleep(5)
                else:
                    print('YOU ARE DEAD')
                    time.sleep(5)
            else:
                print('ha ha ha', "did you laugh? OH NO ITS A TROLL! RUN")
                time.sleep(10)
                print('Troll: You have to answer my riddle or i will kill you?')
                eggy = input('would you like to answer the riddle!')
                if eggy == 'yes':
                    Q = randrange(1, 3)
                    if Q == 1:
                        guess_four = input("what is something you see at night but runs away when it sees "
                                           "light?")
                        check_guess(guess_four, 'darkness')
                    else:
                        guess_five = input('what is a fancy hat but cant protect you from sun or rain')

                        check_guess(guess_five, 'crown')
                        print('the troll became the obsidian door !')
        print('lets follow the rose path')
        time.sleep(5)
        print('look we found an egg and a golden key!')
        print('lets keep them')

        print('we see the obsidian door ahead ')
        print('lets run to it')
        time.sleep(5)
    else:
        print('wait the gate became a obsidian door!')
        time.sleep(5)


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
        time.sleep(10)
    else:  # work HERE!
        print('lets go back')
        time.sleep(5)
        print('look we see a troll')
        print('Troll: Answer my questions and you shall pass or you shall be slain and stuck of last')
        choice = input('would you like to answer his questions ')
        if choice == 'yes':
            guess_six = input('what is brown and sticky?')
            check_guess(guess_six, 'stick')
            print('look thats the obsidian door! ')
            time.sleep(10)
        else:
            print('you are dead!')
            time.sleep(10)
    # add a village and a city !


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
def arnav():
    pass


def new_func():
    print('ok let\'s check the mailbox')
    print('look we have the invitation for the special edition zone')
    Happy_BDay_sumati()


def Happy_BDay_sumati():
    print('Welcome to the special edition Zone')
    Xerxes = input('Do you want to go for the "Birthday party" or "look around" this magnificent park?')
    if Xerxes == 'birthday party'.lower():
        early_Birthday_party()
    else:
        stay_in_the_park()


def space_center():
    pass


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


def birthday_party():
    print('let\'s run ')
    time.sleep(5)
    print('phew! we reach the building just in time ')


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


# actual code
while True:
    print('Flint')
    print('Pre- release spl edition')
    time.sleep(2)
    p = randrange(1, 5)
    if p == 1:
        print('did you know you have to write what is is inside"" or else the code will go wrong?')
        print('example : "go to the beach"')
    elif p == 2:
        print('did you know that there are villages and a space center in this game?(and cities too in later '
              'versions!!)?')
    elif p == 3:
        print('to get the latest Flint go to,')
        webbrowser.open('https://github.com/Code-R-scompanies-technologies')
    else:
        print('stay at home, stay safe')
    time.sleep(5)
    Door = input('Would you like to go to the "mountains", the "sea"  or the "dark forest"?')
    print('you can also open up the mailbox')
    if Door == 'mountains':
        sumati()
    elif Door == 'sea':
        suvid()
    elif Door == 'dark forest':
        arnav()
    elif 'mailbox':
        new_func()
    else:
        Door = input('Would you like to go to the "mountains", the "sea"  or the "dark forest"?')

# code/R and Sumati Datta are the developers(all rights reserved)
# free open source software
#
