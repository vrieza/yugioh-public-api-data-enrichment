<div align="center">
    <img src="https://wallpapercave.com/dwp1x/wp2001960.jpg"><br>
    source: Wallpapercave.com
</div>

-----------------

# Yugioh Public Api Data Enrichment
> "It's time to duel" - Yugi Mutou

## Introduction

This respitory was created with the aim of completing an assignment in a Bootcamp with the material title <blue> **Collaboration With Git** </blue>.

The initial data contained are the names of 10 yugioh cards, the data can be seen on <blue> **Yugioh.csv** </blue>.
To add other data based on the data provided, the data will be merged using external data obtained using <blue> **API** </blue> from:
 https://ygoprodeck.com/api-guide/.

## Tools & Method

The assigment will be done using a jupyter notebook with python language where the main libraries used are:
1. **numpy** is used for working with arrays
2. **pandas** is used for working with dataframes
3. **request** allows to send HTTP requests using Python.
4. **json** The full-form of JSON is JavaScript Object Notation.

While the git language is used to interact with github.

## Data Definition

The initial data consist of 10 rows with one attribute which are name attribute<br>
* name - Name of the card<br>

While the external data consist of several attributes<br>
* id - ID or Passcode of the card<br>
* name - Name of the card<br>
* type - The type of card you are viewing (Normal Monster, Effect Monster, Synchro Monster, etc)<br>
* desc - Card description/effect<br>
* atk - The ATK value of the card<br>
* def - The DEF value of the card<br>
* level - The Level/RANK of the card<br>
* race - The card race which is officially called type (Spellcaster, Warrior, Insect, etc)<br>
* attribute - The attribute of the card<br>
* archetype - The Archetype that the card belongs to based on role and simillarty between each card<br>
* banlist_info.ban_tcg - The status of the card on the TCG Ban List<br>
* banlist_info.ban_ocg - The status of the card on the OCG Ban List<br>
* banlist_info.ban_goat - The status of the card on the GOAT Format Ban List<br>
* card_sets_set_name - The name of the sets for the card<br>
* card_sets_set_code - The code of the sets <br>
* card_sets_set_rarity - The rarity of the card to be obtain in the card sets<br>
* card_sets_set_rarity_code - The code for the rarity<br>
* card_sets_set_price - Is the $ value<br>
* card_images_id - Id image of the card<br>
* card_images_image_url - Image url<br>
* card_images_image_url_small - Image url<br>
* card_prices_cardmarket_price - The price of the card from Cardmarket (in €)<br>
* card_prices_tcgplayer_price - The price of the card from CoolStuffInc (in $)<br>
* card_prices_ebay_price - The price of the card from Tcgplayer (in $)<br>
* card_prices_amazon_price - The price of the card from eBay (in $)<br>
* card_prices_coolstuffinc_price - The price of the card from Amazon (in $)<br>