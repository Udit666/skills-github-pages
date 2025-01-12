<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>Pseudo Class Selectors</title>
<style>
/* Styles go here. */
header li {
    list-style: none
}

a:link, a:visited {
    text-decoration: none;
    background-color: rgb(255, 238, 4);
    border: 2px solid blueviolet;
    color: black;
    display: block;
    width: 300px;
    text-align: center;
    margin-bottom: 3px;
}

a:hover, a:active {
    background-color: blue;
    color: red;
    font-size: 30px;
}

header li:nth-child(3) {
    font-size: 22px;
}

section div:nth-child(odd) {
    font-size: 22px;
}

section div:nth-child(even) {
    font-size: 23px;
    font-style: italic;
}

section div:nth-child(odd):hover {
    cursor: pointer;
}

</style>
</head>
<body>
    <h1>Games List (Dodi Repacks)</h1>

    <header>
        <ul>
            <li><a href="/">Home</a></li>
            <li><a href="https://dodi-repacks.site/" target="_blank">Dodi Repacks</a></li>
            <li><a href="https://www.youtube.com/" target="_blank">YouTube</a></li>
        </ul>
    </header>

    <section>
        <div><a href="https://dodi-repacks.site/cyberpunk-2077/" target="_blank">Cyberpunk-2077</a></div>
        <div><a href="https://dodi-repacks.site/horizon-zero-dawn-remastered/" target="_blank">Horizon Zero Dawn Remastered</a></div>
        <div><a href="https://dodi-repacks.site/god-of-war-ragnarok/" target="_blank">God Of War: Ragnarok</a></div>
        <div><a href="https://dodi-repacks.site/elden-ring/" target="_blank">Elden Ring</a></div>
        <div><a href="https://dodi-repacks.site/assassins-creed-valhalla/" target="_blank">Assassins Creed Valhalla</a></div>
        <div><a href="https://dodi-repacks.site/red-dead-redemption/" target="_blank">Red Dead Redemption</a></div>
        <div><a href="https://dodi-repacks.site/red-dead-redemption-2/" target="_blank">Red Dead Redemption 2</a></div>
        <div><a href="https://dodi-repacks.site/wwe-2k24/" target="_blank"> WWE 2K24</a></div>
        <div><a href="https://dodi-repacks.site/194-far-cry-5-gold-edition-v-1-011-all-dlcs-multi15-map-editor-hd-pack-dodi-repack-selective-download-from-26-2-gb/" target="_blank">Far Cry 5 Gold Edition</a></div>
        <div><a href="https://dodi-repacks.site/far-cry-6/" target="_blank">Far Cry 6</a></div>
        <div><a href="https://dodi-repacks.site/marvels-guardians-of-the-galaxy/" target="_blank">Guardians of the Galaxy</a></div>
        <div><a href="https://dodi-repacks.site/alan-wake-2/" target="_blank">Alan Wake 2</a></div>
        <div><a href="https://dodi-repacks.site/589-grand-theft-auto-iv-the-complete-edition-v1-2-0-32-all-dlcs-multi7-dodi-repack/" target="_blank">Grand Theft Auto IV: The Definitive Edition / GTA 4</a></div>
        <div><a href="https://dodi-repacks.site/grand-theft-auto-v/" target="_blank">Grand Theft Auto V / GTA 5</a></div>
        <div><a href="https://dodi-repacks.site/grand-theft-auto-the-trilogy-the-definitive-edition/" target="_blank">Grand Theft Auto: The Trilogy - The Definitive Edition</a></div>
        <div><a href="https://dodi-repacks.site/ghost-of-tsushima/" target="_blank">Ghost Of Tsushima: Director's Cut</a></div>
        <div><a href="https://dodi-repacks.site/starfield/" target="_blank">Starfield: Digital Premium Edition</a></div>
        <div><a href="https://dodi-repacks.site/1203-the-elder-scrolls-v-skyrim-anniversary-edition-v1-6-318-0-8-all-dlcs-all-mods-bonus-contents-multi9-from-11-5-gb-dodi-repack/" target="_blank">The Elder Scrolls V: Skyrim - Anniversary Edition</a></div>
        <div><a href="https://dodi-repacks.site/baldurs-gate-3/" target="_blank">Baldur's Gate 3: Digital Deluxe Edition</a></div>
        <div><a href="https://dodi-repacks.site/star-wars-jedi-survivor/" target="_blank">Star Wars Jedi: Survivor - Deluxe Edition</a></div>
    </section>
</body>
</html>
