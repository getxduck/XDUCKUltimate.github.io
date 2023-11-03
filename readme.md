<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>GitHub Dashboard</title>
</head>

<body>
    <div class="dashboard">
        <div class="menu">
            <div class="menu-item" onclick="loadPage('home')">
                <img src="home-icon.png" alt="Home">
                Home
            </div>
            <div class="menu-item" onclick="loadPage('profile')">
                <img src="profile-icon.png" alt="Profile">
                Profile
            </div>
            <div class="menu-item" onclick="loadPage('projects')">
                <img src="projects-icon.png" alt="Projects">
                Projects
            </div>
            <div class="menu-item" onclick="loadPage('settings')">
                <img src="settings-icon.png" alt="Settings">
                Settings
            </div>
            <!-- Redirect buttons for Beta version and XDUCK release -->
            <div class="menu-item" onclick="redirectToBetaVersion()">
                Beta Version
            </div>
            <div class="menu-item" onclick="redirectToXDUCKRelease()">
                XDUCK Release
            </div>
        </div>
        <div class="content">
            <iframe id="content-frame" src="home.html" frameborder="0"></iframe>
        </div>
    </div>

    <script src="script.js"></script>

    <script>
        // Function to redirect to the Beta version download link
        function redirectToBetaVersion() {
            window.location.href = 'https://example.com/beta-download';
        }

        // Function to redirect to the XDUCK release download link
        function redirectToXDUCKRelease() {
            window.location.href = 'https://example.com/xduck-download';
        }
    </script>
</body>

</html>
