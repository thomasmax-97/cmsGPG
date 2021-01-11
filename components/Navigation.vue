<template>
    <header id="header" class="site-header site-header--landing">
        <!-- Main Navigation Left -->
        <nav class="main-nav">
            <ul class="main-nav__list">
                <li class="">
                    <NuxtLink to="/">Home</NuxtLink>
                </li>
                <li class="">
                    <a>Verein</a>
                    <ul class="main-nav__sub">
                        <li>
                            <NuxtLink to="/ueberuns">Über Uns</NuxtLink>
                        <li>
                            <NuxtLink to="/bewerben">Mitglied werden</NuxtLink>
                        </li>
                        <li>
                            <NuxtLink to="/">Vereinssatzung</NuxtLink>
                        </li>

                    </ul>
                </li>
                <li>
                    <a>Teams</a>
                    <ul class="main-nav__sub">
                        <li>
                            <NuxtLink to="/team">Team 1</NuxtLink>
                        <li class="">
                            <NuxtLink to="/team1">Team 2</NuxtLink>
                        </li>
                    </ul>
                </li>
            </ul>
        </nav>
        <!-- Main Navigation Left / End -->

        <!-- Logo - Image Based -->
        <div class="header-logo header-logo--img">
            <a href="index.html"><img src="~assets/img/logo.png" srcset="assets/img/logo@2x.png 2x"
                                      alt="Necromancers"></a>
        </div>
        <!-- Logo - Image Based / End -->

        <!-- Main Navigation Right -->
        <nav class="main-nav">
            <ul class="main-nav__list">
                <li>
                    <NuxtLink to="#">Streamer</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="#">Partner</NuxtLink>
                </li>
                <li>
                    <a href="https://forum.germany-playsgroup.de/">Forum</a>
                </li>
                <li>
                    <a href="/kontakt">Kontakt</a>
                </li>
            </ul>
        </nav>
        <!-- Main Navigation Right / End -->
    </header>
</template>