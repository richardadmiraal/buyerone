# buyerone<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Buyer One Custom Form</title>
</head>
<body>
    <h2>Welcome to Your Secure Homebuying Assistant!</h2>
    <p>Please fill out the form below to help us find your perfect home. Your information is securely handled and only shared with your assigned real estate agent, Richard Admiraal, REALTOR™.</p>

    <form action="/submit_form" method="post">
        <h3>Personal Information</h3>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br>

        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone" required><br>

        <h3>Property Preferences</h3>
        <label for="property_type">Property Type:</label>
        <input type="text" id="property_type" name="property_type" required><br>

        <label for="bedrooms">Number of Bedrooms:</label>
        <input type="number" id="bedrooms" name="bedrooms" required><br>

        <label for="bathrooms">Number of Bathrooms:</label>
        <input type="number" id="bathrooms" name="bathrooms" required><br>

        <label for="location">Preferred Location/Neighborhood:</label>
        <input type="text" id="location" name="location" required><br>

        <label for="budget">Budget Range:</label>
        <input type="text" id="budget" name="budget" required><br>

        <label for="features">Must-Have Features:</label>
        <textarea id="features" name="features" rows="3"></textarea><br>

        <h3>Financial Information</h3>
        <label for="down_payment">Estimated Down Payment:</label>
        <input type="text" id="down_payment" name="down_payment" required><br>

        <label for="mortgage_type">Preferred Mortgage Type:</label>
        <input type="text" id="mortgage_type" name="mortgage_type"><br>

        <h3>Additional Information</h3>
        <label for="questions">Specific Concerns or Questions:</label>
        <textarea id="questions" name="questions" rows="3"></textarea><br>

        <p>Rest assured, your conversation and all submitted information are secure and confidential. Only Richard Admiraal, your dedicated real estate agent, will have access to this data. If you have any privacy concerns, please refer to our <a href="https://privacy.microsoft.com/en-us/privacystatement">Privacy Policy</a>.</p>

        <button type="submit">Submit</button>
    </form>
</body>
</html>
