/** initialize css counter */
#write {
    counter-reset: h1
}

h1 {
    counter-reset: h2
}

h2 {
    counter-reset: h3
}

h3 {
    counter-reset: h4
}

h4 {
    counter-reset: h5
}

h5 {
    counter-reset: h6
}

/** put counter result into headings */
#write h1:before {
    counter-increment: h1;
    content: counter(h1) ". "
}

#write h2:before {
    counter-increment: h2;
    content: counter(h1) "." counter(h2) ". "
}

#write h3:before,
h3.md-focus.md-heading:before /** override the default style for focused headings */ {
    counter-increment: h3;
    content: counter(h1) "." counter(h2) "." counter(h3) ". "
}

#write h4:before,
h4.md-focus.md-heading:before {
    counter-increment: h4;
    content: counter(h1) "." counter(h2) "." counter(h3) "." counter(h4) ". "
}

#write h5:before,
h5.md-focus.md-heading:before {
    counter-increment: h5;
    content: counter(h1) "." counter(h2) "." counter(h3) "." counter(h4) "." counter(h5) ". "
}

#write h6:before,
h6.md-focus.md-heading:before {
    counter-increment: h6;
    content: counter(h1) "." counter(h2) "." counter(h3) "." counter(h4) "." counter(h5) "." counter(h6) ". "
}

/** override the default style for focused headings */
#write>h3.md-focus:before,
#write>h4.md-focus:before,
#write>h5.md-focus:before,
#write>h6.md-focus:before,
h3.md-focus:before,
h4.md-focus:before,
h5.md-focus:before,
h6.md-focus:before {
    color: inherit;
    border: inherit;
    border-radius: inherit;
    position: inherit;
    left:initial;
    float: none;
    top:initial;
    font-size: inherit;
    padding-left: inherit;
    padding-right: inherit;
    vertical-align: inherit;
    font-weight: inherit;
    line-height: inherit;
}

# Rubrik för nytt dokument

## Rubrik nivå 2

Euismod malesuada, libero fugit!
Redigering tre.
Redigering fyra.
Redigering ett, två och fyra.
Primis imperdiet iste, wisi tempus, voluptas laboriosam, ea.
Minim aptent laboriosam purus consectetuer accusantium.
Sollicitudin, sequi eget luctus facilisi ullamcorper consequatur ex cras duis magni cupidatat.
Ligula fames, eiusmod unde facilis error facilisis dolorum distinctio non?
Corporis adipisci dictumst magna!
Nostrud laboriosam nam, taciti?
Eaque voluptates.

Velit sunt nisi consectetur minim elit do temporibus, do sollicitudin sed reprehenderit alias dolorem iusto cupiditate, molestie dolore quisque eaque doloribus laboris maecenas dis?

x + 2 − x<sup>2</sup>

Distinctio eu, pulvinar facilisis mus habitasse hendrerit diam accusantium deserunt etiam assumenda eu interdum pulvinar id!
Modi nullam. Error tempora!
Ultricies, penatibus aliquip dolore.
Aliquam aenean.

* Punktlista
* Ny punkt
* En punkt till
  * Underpunkt.
    Mer text till underpunkten.

Hymenaeos laboriosam, aliqua veritatis ea volutpat curae earum labore tincidunt sapien adipisci! Incididunt.
Repellat?
Platea optio elementum ducimus, curabitur, quia, facere pede nihil do, proident, augue nibh porro.
Consectetuer temporibus, nihil ipsum? Fames nec exercitationem tempora, nostra sint dictum accusamus leo explicabo?
Senectus vulputate pellentesque hymenaeos cillum aptent tellus.
Ridiculus.

Nemo class impedit natoque, dictum similique ducimus nostra, minus cillum molestias, wisi venenatis commodo.
Donec voluptates?
Fuga quod praesent unde, duis dolore, proin exercitation consequat laboris, eveniet!
Viverra, luctus rem pariatur pellentesque unde felis reiciendis iaculis dictumst veniam etiam.
Distinctio harum ullamcorper?
Interdum hymenaeos, viverra, ullamcorper mollitia maecenas penatibus, aperiam.

### Rubrik nivå 3

Ipsam potenti exercitation modi iste sollicitudin!
Culpa, omnis fugit mauris dicta hic, vitae hendrerit.
Sociosqu error?
Adipisci a.
Dicta fuga!
Consequatur cillum porta aliquet.
Laboris sapien tempus cupiditate necessitatibus morbi?
Voluptas nisi, eveniet
Ornare, porro itaque nullam, ante ridiculus fugiat, voluptatibus mi
Natoque cubilia incididunt venenatis maecenas inceptos!
Excepteur laoreet.

Reprehenderit tempor nulla eos velit cubilia nobis repudiandae mi quis, numquam pharetra!
Cupiditate modi, rutrum!
Magni nullam, odio saepe aliquip!
Similique, voluptatum consequatur rerum, officiis.
Ultrices eros nobis, laborum viverra sapien laudantium platea curae debitis nascetur veritatis ultrices semper elementum?
Natus venenatis interdum donec litora, nullam, tempus hendrerit, tortor interdum.

### Rubrik nivå 3

Purus arcu morbi, fermentum condimentum optio.
Possimus maecenas esse vehicula, eiusmod.
Dolore.
Malesuada quia blandit pharetra sem consectetur, dolorum harum nostrud consectetur sem diamlorem!
Fringilla diamlorem, eligendi imperdiet, iste officia!
Repellat, iaculis, lectus, rerum tristique officia!
Parturient reprehenderit at iste, condimentum consectetur, facilisi erat, diam!
Duis itaque tempora, consectetuer, euismod.

## Rubrik nivå 2

Volutpat temporibus ut, viverra fuga, modi ab excepturi, consectetuer.
Itaque habitant!
Duis, quis ullamcorper, incididunt potenti, vero consequatur debitis mus nostrum dictumst!
Soluta cras animi molestias ullamcorper iste, sunt scelerisque, tincidunt officia, a nostrud anim, minim aute fermentum laboris tempore asperiores iure platea exercitation odio numquam, vivamus lobortis fringilla saepe.

Nibh soluta fugiat!
Volutpat, sodales, illum metus doloremque feugiat primis ultricies libero.
Ridiculus varius?
Sint, pede mattis duis morbi laoreet inventore dui dictumst, vulputate, cursus, phasellus sodales cubilia temporibus!
Totam?
Etiam magni, laoreet nascetur.
Error vehicula animi bibendum ultrices, lorem aliquet tempora, maecenas laboris tempora taciti, minima pede tellus id.
