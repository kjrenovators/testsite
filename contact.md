# Contact Us

## Get in Touch

<div id="contactForm">
    <label for="name">Name:</label><br>
    <input type="text" id="name" required><br><br>
    <label for="email">Email:</label><br>
    <input type="email" id="email" required><br><br>
    <label for="message">Message:</label><br>
    <textarea id="message" rows="4" cols="50" required></textarea><br><br>
    <button onclick="submitForm()">Submit</button>
</div>

<script>
function submitForm() {
    var name = document.getElementById("name").value;
    var email = document.getElementById("email").value;
    var message = document.getElementById("message").value;

    // Here, you can handle the form submission, e.g., send the data to a server
    console.log("Name: " + name);
    console.log("Email: " + email);
    console.log("Message: " + message);

    // You can add additional logic here, such as displaying a confirmation message
    alert("Your message has been submitted successfully!");
}
</script>
