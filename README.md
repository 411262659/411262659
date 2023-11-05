<!DOCTYPE html>
<html>
<head>
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
</head>
<body>
  <main>
    <h1>NBA Legends</h1>
    <section>
      <h2>Top NBA Moments</h2>
      <p>Witness more <a target="_blank" href="https://nba.com">epic NBA moments</a> in our gallery.</p>
      <a href="https://nba.com"><img src="https://ichef.bbci.co.uk/onesport/cps/624/cpsprodpb/1139B/production/_110655507_kb.jpg" alt="A dynamic NBA game in action."></a>
    </section>
    <section>
      <h2>NBA Icons</h2>
      <h3>Legendary NBA players:</h3>
      <ul id="nba-players">
        <li>Michael Jordan</li>
        <li>LeBron James</li>
        <li>Kobe Bryant</li>
      </ul>
      <button id="add-player">Add Player</button>
    </section>
    <section>
      <h2>Join the NBA Enthusiasts Community</h2>
      <form action="https://nba.com/submit-nba-photo">
        <fieldset>
          <legend>Are you an NBA enthusiast?</legend>
          <label><input id="yes" type="radio" name="enthusiast" value="yes"> Yes</label>
          <label><input id="no" type="radio" name="enthusiast" value="no"> No</label>
        </fieldset>
        <fieldset>
          <legend>Who is your favorite NBA player?</legend>
          <select name="favorite-player" id="favorite-player">
            <option value="jordan">Michael Jordan</option>
            <option value="lebron">LeBron James</option>
            <option value="kobe">Kobe Bryant</option>
          </select>
        </fieldset>
        <input type="text" name="nbaphotourl" placeholder="NBA photo URL" required>
        <button type="submit">Submit</button>
      </form>
    </section>
  </main>

  <script>
    $(document).ready(function() {
      // Event listener to add a new player to the list
      $("#add-player").click(function() {
        var newPlayerName = prompt("Enter the name of the new player:");
        if (newPlayerName) {
          $("#nba-players").append("<li>" + newPlayerName + "</li>");
        }
      });

      // Event listener for the form submission
      $("form").submit(function(event) {
        event.preventDefault(); // Prevent form submission
        var selectedPlayer = $("#favorite-player").val();
        var photoUrl = $("input[name='nbaphotourl']").val();
        alert("Favorite Player: " + selectedPlayer + "\nNBA Photo URL: " + photoUrl);
      });
    });
  </script>
</body>
</html>
