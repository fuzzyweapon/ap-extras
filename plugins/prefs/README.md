# RP Preferences

## Status

**Supported** Although not part of the main Ares code release, this is a supported plugin.  Report any problems you encounter: https://aresmush.com/feedback

Designed for AresMUSH 1.0

## Overview

The RP preferences system provides a way to record RP preferences in a yes/no/maybe fashion with detailed notes.  You can view preferences:

    +==~~~~~====~~~~====~~~~====~~~~=====~~~~=====~~~~====~~~~====~~~~====~~~~~==+
    RP Preferences for Mary
    
    -----  +  --------------------------------------------------------------------
    Adventure       More!
    
    -----  ~  --------------------------------------------------------------------
    Intrigue
    
    -----  -  --------------------------------------------------------------------
    Politics        Ugh.
    
    ------------------------------------------------------------------------------

And find players with specific preferences. 

    +==~~~~~====~~~~====~~~~====~~~~=====~~~~=====~~~~====~~~~====~~~~====~~~~~==+
    RP Preferences - Adventure
    -----  +  --------------------------------------------------------------------
    Mary            More!
    John          
    +==~~~~~====~~~~====~~~~====~~~~=====~~~~=====~~~~====~~~~====~~~~====~~~~~==+

## Installation

1. Connect to the [server shell](https://aresmush.com/tutorials/code/extras/) and change to the aresmush directory.
2. Run `bin/addplugin prefs`.
3. Type `load prefs` in-game.

## Configuration

Once installed, go to the web portal setup screen.  Edit `prefs.yml` and you can configure the following setings.

## categories

You can configure the list of categories that players can set a preference for.

## Web Portal

This plugin has no web portal component.

