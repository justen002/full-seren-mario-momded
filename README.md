# full-seren-mario-momded
 <!DOCTYPE html>
<html lang="en-us">
<head>
    <meta charset="utf-8" />
    <title>Full Screen Mario</title>
    <meta name="keywords" content="fullscreenmario, full, screen, mario, javascript, html5, gaming, online, online game, fun, distraction" />
    <meta name="description" content="FullScreenMario is a free HTML5 remake of Nintendo's original Super Mario Bros. Play it here!" />

    <!-- build:css index.min.css -->
    <link href="index.css" rel="stylesheet" />
    <!-- /build -->

    <link rel="shortcut icon" href="Theme/Mario.gif">
</head>

<body>
    <header>
        <img src="Theme/Header.gif" alt="FullScreenMario.com" />
        <div id="header-right">
            <a class="hoverable" target="_blank" href="https://twitter.com/FullScreenMario">
                <img id="twitter" src="Theme/Twitter.png" alt="Twitter" />
            </a>
            <a class="hoverable" target="_blank" href="https://github.com/FullScreenShenanigans/FullScreenMario">
                <img id="github" src="Theme/Github.png" alt="Github" />
            </a>
            <a class="hoverable" target="_blank" href="https://facebook.com/FullScreenMario">
                <img id="facebook" src="Theme/Facebook.png" alt="Facebook" />
            </a>
        </div>
    </header>

    <section id="game">
        <!-- FSM.UserWrapper will fill out this section... -->
    </section>

    <section id="controls">
        <!-- FSM.UserWrapper will fill out this section... -->
    </section>

    <section id="explanation" class="section-text">
        FullScreenMario is a free HTML5 remake of Nintendo's original Super Mario Bros.
        It includes the original 32 levels, a random map generator, a <!-- social --> level editor, and over a dozen custom mods.
    </section>

    <section id="social" class="section-text">
        You may <a class="link-github" href="https://www.github.com/FullScreenShenanigans/FullScreenMario">download the game for yourself</a> from GitHub, the location of Full Screen Mario's open source project.
        Be sure to get the latest news on our <a class="link-facebook" href="https://www.facebook.com/FullScreenMario">Facebook</a> and <a class="link-twitter" href="https://www.twitter.com/FullScreenMario">Twitter</a> too!
    </section>

    <section id="credits" class="section-text">
        FullScreenMario was made possible first and foremost by Nintendo, who originally created Mario and has since maintained the series.
        It would also not have been possible without the dedicated efforts of the Mario fan community over the past three decades, in particular <a href="http://www.themushroomkingdom.net/">themushroomkingdom.net</a>.
    </section>

    <section id="hangar96" class="section-text">
        <a href="http://marathon.sourceforge.net" alt="Escape will make me god.">
            <img class="hoverable" src="Theme/Aleph One.png" />
        </a>
    </section>

    <section id="legal" class="section-text">
        <small><em>Mario, Super Mario Brothers, and all associated games and media are property of Nintendo and/or Nintendo of America Inc., and are protected by United States and international copyright, trademark and other intellectual property laws.</em></small>
    </section>

    <!-- build:template
    <script src="FullScreenMario-<%= version %>.min.js"></script>
    /build -->
    <!-- build:remove -->
    <script src="References/AreaSpawnr-0.2.0.js" type="text/javascript"></script>
    <script src="References/AudioPlayr-0.2.1.js" type="text/javascript"></script>
    <script src="References/ChangeLinr-0.2.0.js" type="text/javascript"></script>
    <script src="References/DeviceLayr-0.2.0.js" type="text/javascript"></script>
    <script src="References/EightBittr-0.2.0.js" type="text/javascript"></script>
    <script src="References/FPSAnalyzr-0.2.1.js" type="text/javascript"></script>
    <script src="References/GamesRunnr-0.2.0.js" type="text/javascript"></script>
    <script src="References/GameStartr-0.2.0.js" type="text/javascript"></script>
    <script src="References/GroupHoldr-0.2.1.js" type="text/javascript"></script>
    <script src="References/InputWritr-0.2.0.js" type="text/javascript"></script>
    <script src="References/ItemsHoldr-0.2.1.js" type="text/javascript"></script>
    <script src="References/LevelEditr-0.2.0.js" type="text/javascript"></script>
    <script src="References/MapsCreatr-0.2.1.js" type="text/javascript"></script>
    <script src="References/MapScreenr-0.2.1.js" type="text/javascript"></script>
    <script src="References/MathDecidr-0.2.0.js" type="text/javascript"></script>
    <script src="References/ModAttachr-0.2.2.js" type="text/javascript"></script>
    <script src="References/NumberMakr-0.2.2.js" type="text/javascript"></script>
    <script src="References/ObjectMakr-0.2.2.js" type="text/javascript"></script>
    <script src="References/PixelDrawr-0.2.0.js" type="text/javascript"></script>
    <script src="References/PixelRendr-0.2.0.js" type="text/javascript"></script>
    <script src="References/QuadsKeepr-0.2.1.js" type="text/javascript"></script>
    <script src="References/ScenePlayr-0.2.0.js" type="text/javascript"></script>
    <script src="References/StringFilr-0.2.1.js" type="text/javascript"></script>
    <script src="References/ThingHittr-0.2.0.js" type="text/javascript"></script>
    <script src="References/TimeHandlr-0.2.0.js" type="text/javascript"></script>
    <script src="References/TouchPassr-0.2.0.js" type="text/javascript"></script>
    <script src="References/UsageHelpr-0.2.0.js" type="text/javascript"></script>
    <script src="References/UserWrappr-0.2.0.js" type="text/javascript"></script>
    <script src="References/WorldSeedr-0.2.0.js" type="text/javascript"></script>
    <script src="References/js_beautify.js" type="text/javascript"></script>
    <script src="Animations.js" type="text/javascript"></script>
    <script src="Activations.js" type="text/javascript"></script>
    <script src="Collisions.js" type="text/javascript"></script>
    <script src="Cutscenes.js" type="text/javascript"></script>
    <script src="Deaths.js" type="text/javascript"></script>
    <script src="Inputs.js" type="text/javascript"></script>
    <script src="Macros.js" type="text/javascript"></script>
    <script src="Maintenance.js" type="text/javascript"></script>
    <script src="Movements.js" type="text/javascript"></script>
    <script src="Physics.js" type="text/javascript"></script>
    <script src="Scoring.js" type="text/javascript"></script>
    <script src="Spawns.js" type="text/javascript"></script>
    <script src="Transports.js" type="text/javascript"></script>
    <script src="FullScreenMario.js" type="text/javascript"></script>
    <script src="settings/audio.js" type="text/javascript"></script>
    <script src="settings/collisions.js" type="text/javascript"></script>
    <script src="settings/devices.js" type="text/javascript"></script>
    <script src="settings/editor.js" type="text/javascript"></script>
    <script src="settings/generator.js" type="text/javascript"></script>
    <script src="settings/groups.js" type="text/javascript"></script>
    <script src="settings/events.js" type="text/javascript"></script>
    <script src="settings/help.js" type="text/javascript"></script>
    <script src="settings/input.js" type="text/javascript"></script>
    <script src="settings/items.js" type="text/javascript"></script>
    <script src="settings/maps.js" type="text/javascript"></script>
    <script src="settings/maps/1-1.js" type="text/javascript"></script>
    <script src="settings/maps/1-2.js" type="text/javascript"></script>
    <script src="settings/maps/1-3.js" type="text/javascript"></script>
    <script src="settings/maps/1-4.js" type="text/javascript"></script>
    <script src="settings/maps/2-1.js" type="text/javascript"></script>
    <script src="settings/maps/2-2.js" type="text/javascript"></script>
    <script src="settings/maps/2-3.js" type="text/javascript"></script>
    <script src="settings/maps/2-4.js" type="text/javascript"></script>
    <script src="settings/maps/3-1.js" type="text/javascript"></script>
    <script src="settings/maps/3-2.js" type="text/javascript"></script>
    <script src="settings/maps/3-3.js" type="text/javascript"></script>
    <script src="settings/maps/3-4.js" type="text/javascript"></script>
    <script src="settings/maps/4-1.js" type="text/javascript"></script>
    <script src="settings/maps/4-2.js" type="text/javascript"></script>
    <script src="settings/maps/4-3.js" type="text/javascript"></script>
    <script src="settings/maps/4-4.js" type="text/javascript"></script>
    <script src="settings/maps/5-1.js" type="text/javascript"></script>
    <script src="settings/maps/5-2.js" type="text/javascript"></script>
    <script src="settings/maps/5-3.js" type="text/javascript"></script>
    <script src="settings/maps/5-4.js" type="text/javascript"></script>
    <script src="settings/maps/6-1.js" type="text/javascript"></script>
    <script src="settings/maps/6-2.js" type="text/javascript"></script>
    <script src="settings/maps/6-3.js" type="text/javascript"></script>
    <script src="settings/maps/6-4.js" type="text/javascript"></script>
    <script src="settings/maps/7-1.js" type="text/javascript"></script>
    <script src="settings/maps/7-2.js" type="text/javascript"></script>
    <script src="settings/maps/7-3.js" type="text/javascript"></script>
    <script src="settings/maps/7-4.js" type="text/javascript"></script>
    <script src="settings/maps/8-1.js" type="text/javascript"></script>
    <script src="settings/maps/8-2.js" type="text/javascript"></script>
    <script src="settings/maps/8-3.js" type="text/javascript"></script>
    <script src="settings/maps/8-4.js" type="text/javascript"></script>
    <script src="settings/maps/Random.js" type="text/javascript"></script>
    <script src="settings/math.js" type="text/javascript"></script>
    <script src="settings/mods.js" type="text/javascript"></script>
    <script src="settings/objects.js" type="text/javascript"></script>
    <script src="settings/quadrants.js" type="text/javascript"></script>
    <script src="settings/renderer.js" type="text/javascript"></script>
    <script src="settings/runner.js" type="text/javascript"></script>
    <script src="settings/scenes.js" type="text/javascript"></script>
    <script src="settings/sprites.js" type="text/javascript"></script>
    <script src="settings/touch.js" type="text/javascript"></script>
    <script src="settings/ui.js" type="text/javascript"></script>
    <!-- /build -->
    <!-- build:js index.min.js -->
    <script src="index.js" type="text/javascript"></script>
    <!-- /build -->
</body>
</html>
