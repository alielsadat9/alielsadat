// JavaScript function to show registration steps when the button is clicked
function showRegistrationSteps() {
    var stepsDiv = document.getElementById('registration-steps');
    if (stepsDiv.style.display === "none") {
        stepsDiv.style.display = "block";
    } else {
        stepsDiv.style.display = "none";
    }
}