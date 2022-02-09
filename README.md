# Test
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <title></title>
    <link href="FormValidation.css" type="text/css" rel="stylesheet" />
</head>
<body>
    <form name="kontaktFormular" action="test.html">
        <fieldset>
            <legend>Formularvalidierung</legend>
            <section>
                <label for="nameTextInput">Name: Lukas</label>
                <input name="nameTextInput" type="text" />
            </section>
            <section>
                <label for="vornameTextInput">Vorname:</label>
                <input name="vornameTextInput" type="text" />
            </section>
            <section>
                <label></label>
                <input type="submit" value="Senden" />
                <input type="reset" value="Zurücksetzen" />
            </section>
            <section>
                <span id="fehlermeldung"></span>
            </section>
        </fieldset>
    </form>
</body>
</html>
