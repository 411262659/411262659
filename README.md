<!DOCTYPE html>
<html>
  <head>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script>
      $(document).ready(function() {
        // Function to show/hide the text input field based on the "Yes" or "No" selection
        $('input[name="enthusiast"]').change(function() {
          if ($('#yes').is(':checked')) {
            $('input[name="nbaphotourl"]').show();
          } else {
            $('input[name="nbaphotourl"]').hide();
          }
        });
      });
    </script>
  </head>
  <body>
    <main>
      <!-- Your existing HTML code -->
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
            <select name="favorite-player">
              <option value="jordan">Michael Jordan</option>
              <option value="lebron">LeBron James</option>
              <option value="kobe">Kobe Bryant</option>
              <!-- Add more NBA players here -->
            </select>
          </fieldset>
          <input type="text" name="nbaphotourl" placeholder="NBA photo URL" required>
          <button type="submit">Submit</button>
        </form>
      </section>
    </main>
  </body>
</html>
