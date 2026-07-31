---

layout: default
title: Anmeldung
----------------

<div class="form-page">

  <div class="form-header">
    <div class="hero-eyebrow">PARTICIPANT FORM</div>
    <h1>📝 Anmeldung</h1>
    <p>
      Bitte beantworte die folgenden Fragen, damit wir das Spiel
      und die Gruppenplanung vorbereiten können.
    </p>
  </div>

  <form id="participant-form">

```
<div class="form-section">

  <h2>👤 Über dich</h2>


  <div class="form-group">

    <label for="discord-name">
      Discord Name
    </label>

    <input
      type="text"
      id="discord-name"
      name="discord-name"
      placeholder="Dein Discord-Name"
      required
    >

  </div>


  <div class="form-group">

    <label>
      Confirm attendance
    </label>

    <div class="options">

      <label class="option">
        <input
          type="radio"
          name="attendance"
          value="yes"
          required
        >
        <span>✅ Yes, I'm attending</span>
      </label>

      <label class="option">
        <input
          type="radio"
          name="attendance"
          value="no"
        >
        <span>❌ No, I can't attend</span>
      </label>

    </div>

  </div>


  <div class="form-group">

    <label>
      Preferred game language
    </label>

    <div class="options">

      <label class="option">
        <input
          type="radio"
          name="language"
          value="german"
          required
        >
        <span>🇩🇪 Deutsch</span>
      </label>

      <label class="option">
        <input
          type="radio"
          name="language"
          value="english"
        >
        <span>🇬🇧 English</span>
      </label>

      <label class="option">
        <input
          type="radio"
          name="language"
          value="both"
        >
        <span>🌍 Both are fine</span>
      </label>

    </div>

  </div>

</div>


<div class="form-section">

  <h2>📍 Organisation</h2>


  <div class="form-group">

    <label>
      Is Essen Hbf okay as the starting point?
    </label>

    <div class="options">

      <label class="option">
        <input
          type="radio"
          name="essen-hbf"
          value="yes"
          required
        >
        <span>✅ Yes</span>
      </label>

      <label class="option">
        <input
          type="radio"
          name="essen-hbf"
          value="no"
        >
        <span>❌ No</span>
      </label>

    </div>

  </div>


  <div class="form-group">

    <label for="group-size">
      Preferred group size
    </label>

    <select
      id="group-size"
      name="group-size"
      required
    >

      <option value="">
        Please select...
      </option>

      <option value="2">
        2 players
      </option>

      <option value="3">
        3 players
      </option>

      <option value="4">
        4 players
      </option>

      <option value="5">
        5+ players
      </option>

      <option value="any">
        No preference
      </option>

    </select>

  </div>


  <div class="form-group">

    <label>
      Have you played before?
    </label>

    <div class="options">

      <label class="option">
        <input
          type="radio"
          name="played-before"
          value="yes"
          required
        >
        <span>🎮 Yes</span>
      </label>

      <label class="option">
        <input
          type="radio"
          name="played-before"
          value="no"
        >
        <span>🆕 No</span>
      </label>

    </div>

  </div>

</div>


<div class="form-section">

  <h2>👥 Gruppen</h2>


  <div class="form-group">

    <label for="group-preference">
      Prefer being put into a group with another player?
    </label>

    <p class="form-help">
      If yes, tell us who you'd prefer to be grouped with.
      We'll try to accommodate your preference.
    </p>

    <textarea
      id="group-preference"
      name="group-preference"
      rows="4"
      placeholder="e.g. I'd like to be in a group with Alex."
    ></textarea>

  </div>

</div>


<div class="form-section">

  <h2>🎲 Game & Rules</h2>


  <div class="form-group">

    <label>
      Do you own the game?
    </label>

    <div class="options">

      <label class="option">
        <input
          type="radio"
          name="owns-game"
          value="yes"
          required
        >
        <span>🎲 Yes</span>
      </label>

      <label class="option">
        <input
          type="radio"
          name="owns-game"
          value="no"
        >
        <span>❌ No</span>
      </label>

    </div>

  </div>


  <div class="form-group">

    <label>
      Are you okay with curses which cost money?
    </label>

    <p class="form-help">
      Some game mechanics may involve spending real money.
      We will provide more details before the game.
    </p>

    <div class="options">

      <label class="option">
        <input
          type="radio"
          name="paid-curses"
          value="yes"
          required
        >
        <span>💰 Yes</span>
      </label>

      <label class="option">
        <input
          type="radio"
          name="paid-curses"
          value="no"
        >
        <span>🚫 No</span>
      </label>

      <label class="option">
        <input
          type="radio"
          name="paid-curses"
          value="maybe"
        >
        <span>🤔 Depends on the amount</span>
      </label>

    </div>

  </div>


  <div class="form-group">

    <label>
      Move card
    </label>

    <div class="options">

      <label class="option">
        <input
          type="radio"
          name="move-card"
          value="in"
          required
        >
        <span>⬅️ In</span>
      </label>

      <label class="option">
        <input
          type="radio"
          name="move-card"
          value="out"
        >
        <span>➡️ Out</span>
      </label>

    </div>

  </div>

</div>


<div class="form-submit">

  <button type="submit">
    Submit answers
  </button>

  <p id="form-message"></p>

</div>
```

  </form>

</div>
