---
layout: default
title: Home
---

<div class="hero">
  <h1>🕵️ RHEIN-RUHR-RUN: A HIDE & SEEK GAME</h1>
</div>

<!-- COUNTDOWN EINFÜGEN -->
<div class="countdown-container" style="text-align: center; font-family: Arial, sans-serif; font-size: 1.5em; margin: 20px 0;">
  <h3>⏳ Zeit bis zum Rhein-Ruhr-Run:</h3>
  <div id="countdown" style="font-weight: bold; color: #2a6496;"></div>
</div>

<script>
  const countdownDate = new Date("Aug 29, 2026 00:00:00").getTime();
  const countdown = setInterval(() => {
    const now = new Date().getTime();
    const distance = countdownDate - now;
    const days = Math.floor(distance / (1000 * 60 * 60 * 24));
    const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    const seconds = Math.floor((distance % (1000 * 60)) / 1000);
    document.getElementById("countdown").innerHTML = `${days}d ${hours}h ${minutes}m ${seconds}s`;
    if (distance < 0) {
      clearInterval(countdown);
      document.getElementById("countdown").innerHTML = "🎉 Das Event hat begonnen!";
    }
  }, 1000);
</script>

## 🎮 Game Basics

<div class="info-grid">

  <div class="info-card">
    <div class="info-icon">📅 DATE</div>
    <div class="info-value">August 29th & 30th 2026</div>
  </div>
<br>

  <div class="info-card">
    <div class="info-icon">📍 GAME AREA</div>
    <div class="info-value">Ruhr area (+ a few selected places along the Rhine & Wupper)</div>
  </div>
<br>

  <div class="info-card">
    <div class="info-icon">📏 GAME SIZE</div>
    <div class="info-value">Medium</div>
  </div>
<br>

  <div class="info-card">
    <div class="info-icon">⏱️ DURATION</div>
    <div class="info-value">TBD</div>
  </div>

</div>

## 📚 Game Hub

<div class="card-grid">

  <a class="game-card" href="{{ '/regeln' | relative_url }}">
    <span class="game-card-icon">📜</span>
    <strong>Regeln</strong>
    <span>Alle Spielregeln</span>
  </a>
<br>

  <a class="game-card" href="{{ '/spielgebiet' | relative_url }}">
    <span class="game-card-icon">🗺️</span>
    <strong>Spielgebiet</strong>
    <span>Karte & Grenzen</span>
  </a>


  <a class="game-card" href="{{ '/teilnehmende' | relative_url }}">
    <span class="game-card-icon">👥</span>
    <strong>Teilnehmer</strong>
    <span>Wer spielt mit?</span>
  </a>

  <a class="game-card" href="{{ '/anmeldung' | relative_url }}">
    <span class="game-card-icon">👥</span>
    <strong>Bla</strong>
    <span>Wer spielt mit?</span>
  </a>


</div>

## 📢 Aktuelle Informationen

<div class="announcement">

**🟢 Vorbereitung läuft**

Die Spielinformationen werden nach und nach ergänzt.

Schaut regelmäßig hier vorbei und achtet auf wichtige Ankündigungen im Discord.

</div>

## 💬 Discord

Die Website ist die zentrale Informationsquelle für das Spiel.

Für Diskussionen, Fragen und kurzfristige Informationen nutzen wir Discord.
