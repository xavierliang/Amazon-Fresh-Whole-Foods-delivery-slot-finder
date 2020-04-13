**Featured on [CNBC](https://www.cnbc.com/2020/04/08/how-to-get-a-amazon-fresh-whole-foods-delivery-timeslot.html)**

# Whole Foods Delivery Slot Finder and Auto Buy
Mac-only tool that finds available delivery slots for Amazon.com's Whole Foods delivery and Amazon Fresh services.

Fork from [ahertel](https://github.com/ahertel/Amazon-Fresh-Whole-Foods-delivery-slot-finder)

## Whole Foods/Insta Cart Auto Buy
* #### No prompt comfirmation.
* #### Auto checkout after slot found.
* #### Download the 'whole-foods-auto-buy.scpt' [here](https://github.com/xavierliang/Whole-Foods-Instacart-auto-buy/raw/master/whole-foods-auto-buy.scpt)
* #### Download the 'instacart-auto-buy.scpt' [here](https://github.com/xavierliang/Whole-Foods-Instacart-auto-buy/raw/master/instacart-auto-buy.scpt) (Half done on instacart, you still need to manually checkout.)

## Instructions
1. Read the [Compatibility](#compatibility) section below to make sure the tool will work for you
2. Download the 'whole-foods-auto-buy.scpt' [here](https://github.com/xavierliang/Whole-Foods-Instacart-auto-buy/raw/master/whole-foods-auto-buy.scpt)
3. Enable "Allow JavaScript from Apple Events". [How-to video](https://www.youtube.com/watch?v=S6zb_6yTAbo)
4. Log into your Amazon account in Safari
5. Fill your Whole Foods cart with your complete order and proceed through the checkout process manually. Stop once you've arrived at the page saying no slots are available
6. Open whole-foods-auto-buy.scpt in _Script Editor_ and click the 'Play' button to run it and follow the prompts
![run button](https://i.imgur.com/kpQee5h.png)
7. Turn up the volume to hear the notification when a slot is found
8. Once you receive your order, please consider tipping if you can. They are exposing themselves to risk to protect us. Thanks!

Notes:
The script will stop running if your computer falls asleep. You can adjust your 'Energy Saver' settings in System Preferences or download [Caffeine app](https://intelliscapesolutions.com/apps/caffeine) to keep your Mac awake.

## Compatibility
**Before using this tool**, ensure that your checkout page looks **exactly** like the examples in the _Compatible_ section below.
This tool currently only works for some regions because Amazon's checkout pages seem to vary based on your location and I designed the tool based on the page I see in my region. 
If your checkout page doesn't look like the examples in the _Compatible_ or _Incompatible_ sections below, this tool may still work for you but no guarantees.

### Compatible
These are sample screenshots for delivery to a New Jersey address
#### Whole Foods
![Whole Foods](https://i.imgur.com/r7EQQF6.jpg)

#### Amazon Fresh
![Amazon Fresh](https://i.imgur.com/ncVyqQR.jpg)

### Incompatible
#### Amazon Fresh
##### 1.
![Santa Clara, CA](https://i.imgur.com/SyNtrZs.png)
##### 2.
![an unkown city in CA](https://i.imgur.com/PYrO9Il.jpg)


## How it works
- It opens the checkout page in a new window, minimizes it, and then refreshes every ~20 seconds in the background.
- Once it finds an open slot it alerts you by putting a notification on your screen and playing a sound, and automatically checkout page.

## Supporting me/Donations
Thank you so much for wanting to support me! I don't want anything in return for this tool - I'm just happy to be hearing all the stories about how this has helped people, especially those in need. That said, a [few](https://github.com/ahertel/Amazon-Fresh-Whole-Foods-delivery-slot-finder/issues/19) people have wanted to donate. Please consider donating to [GiveDirectly](https://www.givedirectly.org/covid-19/) which directly pays affected families, or one of the [many other charities](https://www.forbes.com/sites/kellyphillipserb/2020/03/21/helping-out-during-the-coronavirus-crisis-where-what--how-to-donate/#6267520350df) addressing COVID-19.

