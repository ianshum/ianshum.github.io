---
layout: post
title: "Valiant Force 2 of XII Braves Pte. Ltd."
categories: Game Posts
author:
- Ian
meta: "ValiantForce2"
coverImage: "/assets/ValiantForce2/CoverImage.png"
---

<img src="../../../../../assets/ValiantForce2/GameTitleMenu.jpg" width="100%">

<br/>

## Official Website of Valiant Force 2

---

[Valiant Force 2](https://playvaliantforce2.com/)

<br/>

## Introduction

---

I joined XII Braves Pte. Ltd. as a junior software engineer and had the chance to work on one of their big mobile game production: Valiant Force 2.

Valiant Force 2 is a turn-based, online strategy mobile role-playing game. This game is a sequel to Valiant Force, which is also a production of XII Braves Pte. Ltd. 

You can find more information from the official website mentioned in the first section.

<br/>

## Responsibilities

---

Being a junior software engineer in the team, I was assigned to some light task at the early stage. For instance, I was mainly tasked to work on some user interface updates in the Unity Edtior, while also getting used to the existing code structure of the project and coding practices of the team. As I gained more knowledge on the workflow, I started to work on different game features, including new game features and quality of life (QOL) updates. Listed below are some of the features I worked on.

### Frame System

---

I worked on the frame system of the game whereby the players can acquire frames with different visual which can be equipped on their profile display. The players can access the selection panel from their profile panel and the frames are grouped into categories. 

<div style="display: flex; justify-content: center; margin-bottom: 15px;">
    <div style="display: flex; flex-direction: column; align-items: center; width: 50%; margin: 5px;">
        <a target="_blank" href="../../../../../assets/ValiantForce2/FrameSystem2.PNG">
            <img src="../../../../../assets/ValiantForce2/FrameSystem2.PNG">
        </a>
        <span style="margin-top: 10px;">Selection Panel (Frame) - All Time Category</span>
    </div>
    <div style="display: flex; flex-direction: column; align-items: center; width: 50%; margin: 5px;">
        <a target="_blank" href="../../../../../assets/ValiantForce2/FrameSystem3.PNG">
            <img src="../../../../../assets/ValiantForce2/FrameSystem3.PNG">
        </a>
        <span style="margin-top: 10px;">Selection Panel (Frame) - Seasonal Category</span>
    </div>
</div>
<div style="width: 100%; text-align: center; margin-bottom: 15px;">
    <i>Click the image to open in full size</i>
</div>

While working on the frame system, I also revised the avatar system by combining it to another tab in the same selection panel. Players can select the hero's avatar to be displayed on their profile's display. There is also a class category selector which allows the players to find the hero easier.

<div style="display: flex; justify-content: center; margin-bottom: 15px;">
    <div style="display: flex; flex-direction: column; align-items: center; width: 50%; margin: 5px;">
        <a target="_blank" href="../../../../../assets/ValiantForce2/FrameSystem1.PNG">
            <img src="../../../../../assets/ValiantForce2/FrameSystem1.PNG">
        </a>
        <span style="margin-top: 10px;">Selection Panel (Avatar)</span>
    </div>
</div>
<div style="width: 100%; text-align: center; margin-bottom: 15px;">
    <i>Click the image to open in full size</i>
</div>

On the right side of the selection panel, players can preview the looks of the avatar and frame combination on their profile display before confirming the selection. Once equipping the avatar and frame on the profile display, they will be visible to the other players in various panels, for example in friends list and guild members list.

<div style="display: flex; justify-content: center; margin-bottom: 15px;">
    <div style="display: flex; flex-direction: column; align-items: center; width: 50%; margin: 5px;">
        <a target="_blank" href="../../../../../assets/ValiantForce2/FrameSystem4.PNG">
            <img src="../../../../../assets/ValiantForce2/FrameSystem4.PNG">
        </a>
        <span style="margin-top: 10px;">Friends List</span>
    </div>
    <div style="display: flex; flex-direction: column; align-items: center; width: 50%; margin: 5px;">
        <a target="_blank" href="../../../../../assets/ValiantForce2/FrameSystem5.PNG">
            <img src="../../../../../assets/ValiantForce2/FrameSystem5.PNG">
        </a>
        <span style="margin-top: 10px;">Guild Members List</span>
    </div>
</div>
<div style="width: 100%; text-align: center; margin-bottom: 15px;">
    <i>Click the image to open in full size</i>
</div>

### Paid Gem and Free Gem System

---

Gems is a premium currency in the game and it comes with 2 different version: paid and free version. The players can get free gems from various activites, such as completing achievements, daily login rewards, and daily quests, whereas paid gems can only be obtained from In Apps Purchase (IAP). 

The main usage of gem is for summoning heroes and recharging energy. Free gems will always be consumed before paid gems unless stated.

<div style="display: flex; justify-content: center; margin-bottom: 15px;">
    <div style="display: flex; flex-direction: column; align-items: center; width: 50%; margin: 5px;">
        <a target="_blank" href="../../../../../assets/ValiantForce2/GemSystem1.PNG">
            <img src="../../../../../assets/ValiantForce2/GemSystem1.PNG">
        </a>
        <span style="margin-top: 10px;">Summon - Free/Paid Gem</span>
    </div>
    <div style="display: flex; flex-direction: column; align-items: center; width: 50%; margin: 5px;">
        <a target="_blank" href="../../../../../assets/ValiantForce2/GemSystem2.PNG">
            <img src="../../../../../assets/ValiantForce2/GemSystem2.PNG">
        </a>
        <span style="margin-top: 10px;">Summon - Paid Gem Only</span>
    </div>
</div>
<div style="display: flex; justify-content: center; margin-bottom: 15px;">
    <div style="display: flex; flex-direction: column; align-items: center; width: 50%; margin: 5px;">
        <a target="_blank" href="../../../../../assets/ValiantForce2/GemSystem3.PNG">
            <img src="../../../../../assets/ValiantForce2/GemSystem3.PNG">
        </a>
        <span style="margin-top: 10px;">Energy Recharge</span>
    </div>
</div>
<div style="width: 100%; text-align: center; margin-bottom: 15px;">
    <i>Click the image to open in full size</i>
</div>

I implemented the logic to calculate and display a gem consumption breakdown confirmation pop up for the total, paid and free gems. I also implemented the functionality to display a pop up for redirection to the IAP shop if the players do not have enough gem for the action.

<div style="display: flex; justify-content: center; margin-bottom: 15px;">
    <div style="display: flex; flex-direction: column; align-items: center; width: 50%; margin: 5px;">
        <a target="_blank" href="../../../../../assets/ValiantForce2/GemSystem4.PNG">
            <img src="../../../../../assets/ValiantForce2/GemSystem4.PNG">
        </a>
        <span style="margin-top: 10px;">Gem Breakdown - Consuming Paid and Free Gem</span>
    </div>
    <div style="display: flex; flex-direction: column; align-items: center; width: 50%; margin: 5px;">
        <a target="_blank" href="../../../../../assets/ValiantForce2/GemSystem5.PNG">
            <img src="../../../../../assets/ValiantForce2/GemSystem5.PNG">
        </a>
        <span style="margin-top: 10px;">Gem Breakdown - Consuming Paid and Free Gem</span>
    </div>
</div>
<div style="display: flex; justify-content: center; margin-bottom: 15px;">
    <div style="display: flex; flex-direction: column; align-items: center; width: 50%; margin: 5px;">
        <a target="_blank" href="../../../../../assets/ValiantForce2/GemSystem6.PNG">
            <img src="../../../../../assets/ValiantForce2/GemSystem6.PNG">
        </a>
        <span style="margin-top: 10px;">Gem Breakdown - Consuming Paid Gem Only</span>
    </div>
    <div style="display: flex; flex-direction: column; align-items: center; width: 50%; margin: 5px;">
        <a target="_blank" href="../../../../../assets/ValiantForce2/GemSystem7.PNG">
            <img src="../../../../../assets/ValiantForce2/GemSystem7.PNG">
        </a>
        <span style="margin-top: 10px;">Insufficient Gem Pop Up</span>
    </div>
</div>
<div style="width: 100%; text-align: center; margin-bottom: 15px;">
    <i>Click the image to open in full size</i>
</div>

### Battle Power Requirement

---

Since the game is a strategy game, players can build up to 5 different squads when they are playing the game. The squad built by players can have different battle power, depending on the heroes (level, equipments) and the mana cards (level) in the squad. Then, the playerS can use the squad they built to tackle the story missions of the game. 

I added the battle power requirement for the mission, allowing the data to control the minimum requirement before a mission can be started. I refactored the existing battle power calculation functions across different places into a universally usable function for calculation consistency, as well as created the functionality to save the highest squad battle power history for unlocking the missions. Additionally, I implemented the quick access to the squad edit panel when the player tries to play a mission while not meeting the requirement.

<div style="display: flex; justify-content: center; margin-bottom: 15px;">
    <div style="display: flex; flex-direction: column; align-items: center; width: 50%; margin: 5px;">
        <a target="_blank" href="../../../../../assets/ValiantForce2/BattlePowerRequirement1.PNG">
            <img src="../../../../../assets/ValiantForce2/BattlePowerRequirement1.PNG">
        </a>
        <span style="margin-top: 10px; text-align: center;">Battle Power Requirement Pop Up with Quick Access Button</span>
    </div>
    <div style="display: flex; flex-direction: column; align-items: center; width: 50%; margin: 5px;">
        <a target="_blank" href="../../../../../assets/ValiantForce2/BattlePowerRequirement2.PNG">
            <img src="../../../../../assets/ValiantForce2/BattlePowerRequirement2.PNG">
        </a>
        <span style="margin-top: 10px;">Sqaud Edit Panel</span>
    </div>
</div>
<div style="width: 100%; text-align: center; margin-bottom: 15px;">
    <i>Click the image to open in full size</i>
</div>

This feature helps the game to maintain a better experience for player when progressing through game, encouraging them to build their squad battle power up and to try more different squad combinations.

### Arena Selection and Landing Page Updates

---

Players can access various type of arenas in the game. I overhauled the arena landing page panel display and included new logic for the opening, starting, ending and closing date time of the arenas. Moreover, I redesigned the existing code for the selection and landing page panel. I restored the missing specification from earlier development stage, removed legacy codes, and introduced some commonly used functions to be used across the arena related panels. 

<div style="display: flex; justify-content: center; margin-bottom: 15px;">
    <div style="display: flex; flex-direction: column; align-items: center; width: 50%; margin: 5px;">
        <a target="_blank" href="../../../../../assets/ValiantForce2/Arena2.PNG">
            <img src="../../../../../assets/ValiantForce2/Arena2.PNG">
        </a>
        <span style="margin-top: 10px;">Arena Slection Panel</span>
    </div>
    <div style="display: flex; flex-direction: column; align-items: center; width: 50%; margin: 5px;">
        <a target="_blank" href="../../../../../assets/ValiantForce2/Arena1.PNG">
            <img src="../../../../../assets/ValiantForce2/Arena1.PNG">
        </a>
        <span style="margin-top: 10px;">Arena Landing Page Panel</span>
    </div>
</div>
<div style="width: 100%; text-align: center; margin-bottom: 15px;">
    <i>Click the image to open in full size</i>
</div>

### First Time Purchase Update (QOL)

---

I revamped the looks of the first time purchase panel by adjusted the background image size for the artist and added localisation for the word image. I also updated the layout for the rewards and added a quick access button to allow players to see the details of the heroes listed as rewards.

<div style="display: flex; justify-content: center; margin-bottom: 15px;">
    <div style="display: flex; flex-direction: column; align-items: center; width: 50%; margin: 5px;">
        <a target="_blank" href="../../../../../assets/ValiantForce2/FirstTimePurchase.PNG">
            <img src="../../../../../assets/ValiantForce2/FirstTimePurchase.PNG">
        </a>
        <span style="margin-top: 10px;">First Time Purchase Panel</span>
    </div>
</div>
<div style="width: 100%; text-align: center; margin-bottom: 15px;">
    <i>Click the image to open in full size</i>
</div>

### Gear Armory Panel Quick Access to Gears (QOL)

---

I incorporated a new tab in the gear armory panel to enable players to quickly access the missions that has the gears as drop loots.

<div style="display: flex; justify-content: center; margin-bottom: 15px;">
    <div style="display: flex; flex-direction: column; align-items: center; width: 50%; margin: 5px;">
        <a target="_blank" href="../../../../../assets/ValiantForce2/GearQuickAccess.PNG">
            <img src="../../../../../assets/ValiantForce2/GearQuickAccess.PNG">
        </a>
        <span style="margin-top: 10px;">Gear Quick Access Tab In Armory Panel</span>
    </div>
</div>
<div style="width: 100%; text-align: center; margin-bottom: 15px;">
    <i>Click the image to open in full size</i>
</div>

### Gear Inventory Sell Mode Auto Select (QOL)

---

I reintroduced the rarity and rarity tier in the auto select option panel and modified the rarity options to be populated dynamically depending on the rarities available in the game, instead of hard coded options. Furthermore, I improved the functionality to save the player's preferences for the auto select option by restructuring the logics. I also added logics to exclude locked and equipped gears when auto selecting gears for sell mode. 

<div style="display: flex; justify-content: center; margin-bottom: 15px;">
    <div style="display: flex; flex-direction: column; align-items: center; width: 50%; margin: 5px;">
        <a target="_blank" href="../../../../../assets/ValiantForce2/SellModeAutoOptions.PNG">
            <img src="../../../../../assets/ValiantForce2/SellModeAutoOptions.PNG">
        </a>
        <span style="margin-top: 10px;">Auto Select Options Panel</span>
    </div>
</div>
<div style="width: 100%; text-align: center; margin-bottom: 15px;">
    <i>Click the image to open in full size</i>
</div>