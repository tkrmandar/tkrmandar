<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dynamic Greeting</title>
</head>
<body>

<h1 id="greeting">Hello, amigos!</h1>

<script>
// List of greetings in different languages
const greetings = [
    "Hello, friends!",     // English
    "¡Hola, amigos!",      // Spanish
    "Bonjour, amis!",      // French
    "Hallo, Freunde!",     // German
    "Ciao, amici!"         // Italian
];

// Function to change the greeting
function changeGreeting() {
    const greetingElement = document.getElementById('greeting');
    let index = 0;
    return setInterval(() => {
        greetingElement.textContent = greetings[index];
        index = (index + 1) % greetings.length;
    }, 5000); // Change greeting every 5 seconds
}

// Call the function to start changing the greeting
changeGreeting();
</script>

</body>
</html>



<!--
**tkrmandar/tkrmandar** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
