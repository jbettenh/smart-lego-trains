# smart-lego-trains
A collection of configuration files to automate Lego trains.

## Dependencies
- [Mattzobricks](https://mattzobricks.com/controllers/firmware-history-and-roadmap)
- [Rocrail](https://wiki.rocrail.net/doku.php?id=win-en)
- [Moqquitto](https://mosquitto.org/)

## Repository Structure
Each folder in the base directory is a separate functional layout, including Rocrail files, Mattzobricks configuration files, and documentation.
Each folder should have a structure like
- Documentation
    - .pdf 
    - .docx
    - .jpg

- Mattzobricks
    - folders for each controller
        - mtc4bt-##### - Mattzo Train Controller 4 Bluetooth plus address it got assigned
        - mlc-#### - Mattzo Layout Controller plus address it got assigned

- Rocrail
    - plan.xml
    - occ.xml

## Layouts
1. Hello World

### Hello World
This was a first attempt at automating the Lego trains using Mattzobricks firmware. It is a simple oval layout and a single Lego Powered up train with 2 stops in Rocrail (4 reed sensors). This would be the bare minimum needed to automate an layout.