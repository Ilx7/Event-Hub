Event-Hub

A simple website to display upcoming and past events.

Structure
- **Header**: site name and navigation.
- **Upcoming Events**: list of upcoming events.
- **Past Events**: list of past events with description and image.

Technologies used
- HTML5

- The work was done independently based on a laboratory assignment.

[index.html](https://github.com/user-attachments/files/27105334/index.html)<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" >
    <title>Event Hub</title>
  </head>

  <body>
    <header>
      <h1>Event Hub</h1>
      <nav>
        <ul>
          <li><a href="#upcoming-events">Upcoming Events</a></li>
          <li><a href="#past-events">Past Events</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <section id="upcoming-events">
        <h2>upcoming Events</h2>
        <article>
          <h3>Raid exit</h3>
          <p>
            I set off from the base at Agroprom Research Institute in the
            direction of the Dump, passing through the territory of Agroprom.
            Dogs were waiting for me ahead, I easily dealt with them and moved
            on. I examined the anomalies of Agroprom, but did not find anything
            useful. We must be careful, because encounters with mutants are
            possible.
          </p>
          <p>
            <time datetime="2026-03-15T06:00">March 15</time><br>
            Time: 6:00
          </p>
          <img
            src="https://i.postimg.cc/fbqFLVKH/photo-2026-04-22-13-47-47.jpg"
            alt="After the emission, I raid the Agroprom Research Institute."
          >
        </article>
        <article>
          <h3>Searching for artifacts after the ejection</h3>
          <p>
            After going through Agroprom, I decided to go to the Dump, because
            there might be a better chance of finding something valuable there.
            It is after the ejection that artifacts often appear in new places,
            and I hope to stumble upon something rare. I move carefully, because
            dangerous mutants are awake and can appear anywhere.
          </p>
          <p>
            <time datetime="2026-03-15T10:00">March 15</time><br>
            Time: 10:00
          </p>
          <img
            src="https://i.postimg.cc/7ZvWJvSG/photo-2026-04-22-13-48-13.jpg"
            alt="at the dump shortly before the chimera"
          >
        </article>
      </section>
      <section id="past-events">
        <h2>Past Events</h2>
        <article>
          <h3>Encounter with a chimera</h3>
          <p>
            I encountered a chimera near the "Gazirovka" anomaly. It was a
            difficult and exhausting battle: the mutant attacked quickly and
            fiercely, forcing me to retreat and seek cover. However, thanks to
            my endurance and accurate shots, I was able to defeat him. After the
            battle, I still couldn't believe for a long time that a chimera
            could appear in the Dump.
          </p>
          <p>
            <time datetime="2026-03-15T14:00">March 15</time><br>
            Time: 14:00
          </p>
          <img
            src="https://i.postimg.cc/X76PpSwR/photo-2026-04-22-13-48-09.jpg"
            alt="killed the chimera, received a minor injury"
          >
        </article>
        <article>
          <h3>Return to base</h3>
          <p>
            After the foray, I was returning to the Agroprom Research Institute
            base. The Chimera managed to slightly injure me, but the wound was
            not critical, and I was able to reach safe territory. The way back
            was tense, as I constantly looked around, expecting new dangers. In
            the end, I reached my people, feeling relieved and tired.
          </p>
          <p>
            <time datetime="2026-03-15T18:00">March 15</time><br>
            Time: 18:00
          </p>
          <img
            src="https://i.postimg.cc/zXkxvLDy/photo-2026-04-22-13-48-05.jpg"
            alt="return to base at Agroprom Research Institute"
          >
        </article>
      </section>
    </main>
  </body>
</html>
