# Unwrapped

Toolkit to improve packagings.


## Detailed Description

Toolkit to improve packagings.

Panoramica del Progetto

The purpose of this project is to improve the experience while using products from Harry’s and Wasa for blind, limited dexterity, but also no disability people. We identify different issues with the help of two people with disabilities : visibility of products information - description, price, composition -, understanding and practicality of the opening/closing system,... 
System of easy opening and closing bags: the consumer can easily identify the tears at the top of the bag and take off the twist tie. This twist tie, bigger than the ones usually used, allows an easy grip. Finally, to close it you just have to wrap it. Clarity of the information: a graphic charter show clearly the information that guide the user in his purchase and later, in his meal. Information: a QR code on the packagings and the website make essential informations audible on your device. 
The packagings are made to be the simplest as possible. We applied the same open / close system to the 4 products with a giant twist tie that allows to crimp the bag and keep it closed. The bags are made of kraft and cut with a lasercut. We also created a graphic charter to show clearly the information that guide the user in his purchase and later, in his meal - with the help of the QR Code system. Besides, a small arduino box help the customer inside the shop.

Documentazione Dettagliata

**PACKAGING**
The packagings are designed to be the simplest as possible. We applied the same open / close system to the 4 products with a giant twist tie that allows to crimp the bag and keep it closed. We also created a graphic charter to show clearly the information that guide the user in his purchase and later, in his meal. Theses information take form in a simple tag added on the packaging.

Find the presentation video here : Video - Unwrapper | Facilitators



**QR CODE**

The QR code is generated online - to be understable for a majority of people we use the classic QR Code - not Aztec or Matrix. It can be easily generated with this open source web tool : keremerkan.net | QR code and 2d code generator. Then, the QR code is print on the packaging.

With a thermoforming machine, we mold a plastic sheet to overprint a braille text on the QR code to help blind and visually impaired people to find it easily. The QR code lead to a website that gives vocal informations.



**VOCAL TAG**

The prototype of the vocal tag is based on an Arduino board - connected on battery and on a speaker, with the built-in program returning the specific sound of the product (the program can be find here : vocal tag - ino.

In this case, everything fit inside a 3D Print box which can be easily fix on the shelves for each product (or product type). Ideally, the objective being to be able to connect via Bluetooth, or to make it interactive via NFC, so that it can be easily updated.

This additional interaction allows audio content to be accessed from a smartphone.



Guida Passo-Passo

1. How to redesign packaging to make it more accessible

System of minimalist sticker tags on kraft bags with an easy grip twist tie to allow to save material, homogenize brands and make products accessible to disabled people. 

















All the files can be find here : frama.link/hack-packaging

List of Materials:Kraft, Printer, Thermoforming machine (braille), Sealing machine, Metal string

**Guidelines Graphic:**

To create a simple and easy to understand packaging stickers, here some tools and fonts we used to create them.

- Fonts used (under SIL Open Font License) : Manrope
- Guidelines : fonts and contrast ratio

**Packaging:**

Here, you will find all the files to create one of these packaging. It can be made with a lasercut machine.

- Template and guidelines for the packaging - made by hand, but using the color scheme of printed/cut files : templates.The lines indicate also where to cut, fold and glue.
- This packaging is made from : Recycled Kraft Paper (220gr) - ideally, it will be better with a inside layer of PE.

2. How to make information on the packaging more accessible

A QR Code to help visually impaired or blind people to understand the product they are about to buy or they already have at home by giving vocal informations as price per kg and food allergens. The QR code is generated online - to be understable for a majority of people we use the classic QR Code - not Aztec or Matrix.





**QR Code:**

To generate the QR Code link to an action, a link or a media, this online tool can be used: keremerkan.net | QR code and 2d code generator

**Braille Surface:**

To create a small thermoformer, you will need a 3D Printer, a lasercut (and also PLA and plastic sheets):

- Files for the thermoformer: 3D files and Gcode files : FilesSettings for Cura - printed on WASP 2040 : Settings
- To mount everything, you will need :2 x threaded rods (d.8mm x l.50mm)2 wing nuts (d.8mm)
- To use, you will need :Plastic sheet (200gr)A vacuum (domestic one is enough)

To create the plate with your text in braille, you will need a CNC Milling machine (and also MDF) :
- Braille Font to use : font
- Use a 1mm Flute on you CNC machine to drill the small holes of the braille text in a MDF 6MM sheet (50mm*50mm max.)

Some videos of the process can be find here :
- Video 1
- Video 2
- Video 3

3. How to make information more accessible in store

Help customers to have more information about Harry’s and Wasa products in stores with a connected vocal price tag. We extend the idea of inclusive packaging and accessibility to information with a vocal price tag in stores : with a loudspeaker diffusing sounds by pressing a button. It allows to spread information about products on the shelves, including price per kg and food allergens. This integrated speaker makes the information accessible to people who do not have a phone to scan an NFC code or tag.





**Voice:**

Generating the voice audio file.To do this, you can have acces to two different tools:

- Mary TTS (last version, package ready to use)
- Google Voice Builder

When you have one of this package, write your text and export the audio file (.mp3)

**Vocal Tag:**

For the electronic part, needs:

- for beginners : Arduino Uno Rev 3 // for more advanced : Arduino Nano 33 BLE / IoT
- a button : Button
- a speaker : Speaker
- connecting wires
- battery

**To implement the code:**

- Arduino program : Program
- download or use the web based editor : Arduino IDE
- link the voice (audio file) you want to the program

Next, the box:

- Here, you can find the 3D files of the two partsyou need to print : STL Files
- To help, the settings used : Settings


## Project Information

- **Category:** Altro
- **Difficulty Level:** 2/5
- **Estimated Time:** Varia
- **License:** CC-NC-BY-SA
- **Original Author:** ludovico@hackability.it


## Materials Needed

None listed.

## Tools Required

None listed.

## Instructions

1. **How to redesign packaging to make it more accessible**
   System of minimalist sticker tags on kraft bags with an easy grip twist tie to allow to save material, homogenize brands and make products accessible to disabled people. 00\_HACKABILITY.jpg
2. **How to make information on the packaging more accessible**
   A QR Code to help visually impaired or blind people to understand the product they are about to buy or they already have at home by giving vocal informations as price per kg and food allergens. The QR code is generated online - to be understable for a majority of people we use the classic QR Code - not Aztec or Matrix.
3. **How to make information more accessible in store**
   Help customers to have more information about Harry’s and Wasa products in stores with a connected vocal price tag. We extend the idea of inclusive packaging and accessibility to information with a vocal price tag in stores : with a loudspeaker diffusing sounds by pressing a button. It allows to spread information about products on the shelves, including price per kg and food allergens. This integrated speaker makes the information accessible to people who do not have a phone to scan an NFC code or tag.


## 📥 Download

Tutti i file del progetto sono disponibili come Release Assets su GitHub. Clicca sui link sottostanti per scaricare i singoli file:

- **[BOITE_SMALL_1.stl](https://github.com/HackabilityNPO/Hackability-Soluzioni/releases/download/project-a9be0bba-c779-4aa1-93b0-ae9701c8837e/BOITE_SMALL_1.stl)** - 6.67 MB
- **[BOITE_SMALL_2.stl](https://github.com/HackabilityNPO/Hackability-Soluzioni/releases/download/project-a9be0bba-c779-4aa1-93b0-ae9701c8837e/BOITE_SMALL_2.stl)** - 86.90 KB

**Visualizza tutti i file della release:** [project-a9be0bba-c779-4aa1-93b0-ae9701c8837e](https://github.com/HackabilityNPO/Hackability-Soluzioni/releases/tag/project-a9be0bba-c779-4aa1-93b0-ae9701c8837e)



## Tags

`Inclusione` `Disabilità Visiva` `Arduino`


---

*This project was uploaded from Hackability platform.*
