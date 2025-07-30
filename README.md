<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>The Via Verse</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <header>
      <h1>The Via Verse</h1>
      <h2>Welcome, Starbabies</h2>
    </header>
    <section class="intro">
      <p>
        You've fallen into my frequency...<br />
        You're in the presence of all that I am...<br />
        Words, Art, Power, and Pretty Little Spells.<br />
        Take what you need. Worship nothing.<br />
        Become everything.<br />
        Kiss your expectations good-bye.
      </p>
    </section>
    <nav>
      <ul>
        <li><a href="diary.html">Mood Diary</a></li>
        <li><a href="writings.html">Writings</a></li>
        <li><a href="offerings.html">Designs & Art</a></li>
        <li><a href="loves.html">Monthly Loves</a></li>
        <li><a href="#" id="secret-link">Enter the Void</a></li>
      </ul>
    </nav>
  </div>

  <script>
    document.getElementById('secret-link').addEventListener('click', function(e) {
      e.preventDefault();
      const pass = prompt('Speak the magic word:');
      if (pass && pass.toLowerCase() === 'lumos') {
        window.location.href = 'secret.html';
      } else {
        alert('The spell fizzles... Try again.');
      }
    });
  </script>
</body>
</html>
