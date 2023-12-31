<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Save Saraswati Petition</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f2f2f2;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }

        main {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        #petition {
            margin-top: 20px;
        }

        form {
            display: grid;
            gap: 10px;
        }

        label {
            font-weight: bold;
        }

        button {
            padding: 10px;
            background-color: #333;
            color: white;
            border: none;
            cursor: pointer;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Save Saraswati Petition</h1>
    </header>

    <main>
        <p>As I walked home one day, I heard the hoarse call of a cow in pain...</p>

        <div id="petition">
            <h2>Sign the Petition</h2>
            <form id="petitionForm">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="location">Location:</label>
                <input type="text" id="location" name="location" required>

                <label for="comments">Comments:</label>
                <textarea id="comments" name="comments" rows="4"></textarea>

                <button type="submit" onclick="submitForm()">Sign Now</button>
            </form>
        </div>
    </main>

    <footer>
        <p>#SaveSaraswati - Share this petition. Make your voice heard!</p>
    </footer>

    <script>
        function submitForm() {
            // Basic form submission logic
            const form = document.getElementById("petitionForm");
            const formData = new FormData(form);

            // You can send the form data to a server using fetch or other methods
            // For simplicity, we'll just log the data to the console here
            for (const entry of formData.entries()) {
                console.log(entry[0] + ': ' + entry[1]);
            }

            // You can also add an AJAX request to send data to a server
            // Example using fetch:
            // fetch('https://your-api-endpoint.com', {
            //     method: 'POST',
            //     body: formData,
            // })
            // .then(response => response.json())
            // .then(data => console.log(data))
            // .catch(error => console.error('Error:', error));

            // Prevent the default form submission
            event.preventDefault();
        }
    </script>
</body>
</html>
