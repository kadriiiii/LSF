## **WIP**

# Template

## Uus **Child Template**

Uus **Child Template** Cassiopeia põhjal: Cassiopeia_cassiopeia_for_lsf

**Templates: Styles (Site)** : cassiopeia_for_lsf_style on määratud kui **Default for all pages**.

## _Template_'i stiil

Tegin kausta `/media/templates/site/cassiopeia_cassiopeia_for_lsf/css` faili `user.css`. 

Joomla/Cassiopeia laevad lehe kõigepealt vaikimisi stiilidega ning siis rakendavad sinna otsa `user.css` failis kirjeldatu.

Praeguse seisuga on seal tavapärasega võrreldes muudetud:
* Lehe värvid
* Päise formaat (**Content > Site Modules > P2isepilt** asukohaga **topbar**, **Layout: banner**)


# Värvid

LSFi punane: `#A9005E`


# LSFi favicon

1. Laadisin `media/templates/site/cassiopeia_cassiopeia_for_lsf/images` kataloogi faili `LSF_favicon.svg`.
2. Kopeerisin `index.php` Cassiopeia _template_'ist uude _template_'i (Cassiopeia_cassiopeia_for_lsf).
3. Muutsin real 25 _favicon_'i faili nime: `$this->addHeadLink(HTMLHelper::_('image', 'LSF_favicon.svg', '', [], true, 1), 'icon', 'rel', ['type' => 'image/svg+xml']);` 
