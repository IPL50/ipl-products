<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IPL Products</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: white;
            padding: 20px;
            text-align: center;
            font-size: 36px;
            font-weight: bold;
            color: green;
            text-transform: uppercase;
            font-family: 'Bodoni MT Black', sans-serif;
            font-style: italic; /* Added italic style to the header */
        }

        header .subtitle {
            font-family: Calibri, sans-serif;
            font-size: 18px;
            color: green;
        }

        header .name-quality {
            font-family: Calibri, sans-serif;
            font-weight: bold;
            font-size: 20px;
            color: green;
        }

        .main-content {
            padding: 20px;
        }

        .table-container {
            border-collapse: collapse;
            width: 100%;
            margin-top: 30px;
        }

        .table-container th, .table-container td {
            border: 1px solid #ddd;
            padding: 12px;
            text-align: center;
        }

        .table-container th {
            background-color: #4CAF50;
            color: white;
        }

        .table-container td {
            background-color: #f2f2f2;
        }

        .new-star {
            color: red;
            font-weight: bold;
            animation: blink 1s linear infinite;
        }

        @keyframes blink {
            50% {
                opacity: 0;
            }
        }

        .footer {
            background-color: #222;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .footer a {
            color: #4CAF50;
            text-decoration: none;
        }

        .button {
            background-color: #4CAF50;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            margin-top: 10px;
        }

        .menu-content {
            display: none;
            padding: 10px;
            background-color: #f9f9f9;
            margin-top: 10px;
            border: 1px solid #ddd;
        }

        .menu-content a {
            text-decoration: none;
            color: #333;
            font-size: 16px;
            display: block;
            padding: 5px;
        }

        .menu-content a:hover {
            background-color: #ddd;
        }

        .winding-specifications, .assembly-drawing {
            text-decoration: none;
        }

        .transformer-unit {
            font-family: 'Times New Roman', serif;
            font-size: 24px;
            font-weight: bold;
            color: #2A3D52;
            background-color: #E2F1D6;
            padding: 20px;
            margin: 20px 0;
            text-align: center;
        }

    </style>
</head>
<body>

<header>
    I.P.L. PRODUCTS
    <div class="subtitle">ISO 9001-2015 CERTIFIED</div>
    <div class="name-quality">Name for Quality and Services</div>
</header>

<div class="main-content">
    <div class="transformer-unit">
        TRANSFORMER UNIT – DESIGN CORNER
    </div>

    <button class="button" onclick="toggleMenu()">Show/Hide Information</button>

    <div id="menuContent" class="menu-content">
        <button onclick="toggleProjectStatus()">Project Status</button>
        <div id="projectStatus" style="display:none;">
            <a href=https://drive.google.com/file/d/1Y8EwVdExJcb4SX8MFRX-9036hHO5b1am/view?usp=sharing target="_blank">Click here to download</a>
        </div>
        
        <button onclick="toggleTestReports()">Test Reports</button>
        <div id="testReports" style="display:none;">
            <p>Coming soon 🚧</p>
        </div>
        
        <button onclick="toggleAboutUs()">About Us</button>
        <div id="aboutUs" style="display:none;">
            <p><strong>Our C.E.O.:</strong> Mr. Harirajan</p>
            <p><strong>Design-Head:</strong> Mr. R.Vijayashankar</p>
            <p><strong>Design Engineer-Mechanical:</strong> Mr.R.Kalaisurya</p>
            <p><strong>Jr. Design Engineer-Mechanical:</strong> Mr.B.Saravanan</p>
        </div>
        
        <button onclick="toggleContactUs()">Contact Us</button>
        <div id="contactUs" style="display:none;">
            <p>Email: transformermarketing@iplproducts.com</p>
            <p>Email: design@iplproducts.com</p>
            <p>Phone: 9600080611</p>
        </div>
        
        <button onclick="toggleDevelopers()">Developers</button>
        <div id="developers" style="display:none;">
            <p><strong>Developer:</strong> Mr. B.Saravanan (Jr.Design Engineer-Mechanical)</p>
            <p>Email: saravananiplproducts@gmail.com</p>
            <p>Phone: 9087800454</p>
        </div>
    </div>

    <table class="table-container">
        <tr>
            <th>W.O. No.</th>
            <th>BOM</th>
            <th>CORE</th>
            <th>CORE Channel</th>
            <th>P.O.</th>
            <th>Winding Specification</th>
            <th>Assembly Drawing</th>
        </tr>
        <!-- W.O.No: IPL328 to IPL340 -->
        <tr>
            <td><span class="new-star">NEW</span> IPL 335</td>
            <td><a href=https://drive.google.com/file/d/1PN8xIwkwPk1S9S5zf5yl0zjZWOL2z76I/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href=https://drive.google.com/file/d/1kzeXghwPNejciQsS91CCmsk8QBnVUnu5/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href=https://drive.google.com/file/d/1GGTnKMQ4hTzQjpGnBXf5p9ZChAK8LQcp/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href="https://drive.google.com/your-po-pdf-link" target="_blank">Click here</a></td>
            <td><a href="https://drive.google.com/your-winding-specification-link" target="_blank">Click here</a></td>
            <td><a href="https://drive.google.com/your-assembly-drawing-link" target="_blank">Click here</a></td>
        </tr>
        <tr>
            <td><span class="new-star">NEW</span> IPL 333</td>
            <td><a href=https://drive.google.com/file/d/1zYW8CjHHj8EAKqO-tWObfVDBCzlA_Fjo/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href=https://drive.google.com/file/d/1ZFysi3mORcaYGnTdGxcSoPfqRsRZ9Dge/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href=https://drive.google.com/file/d/1eh2mt6KpwueMWsp1hT6wF94HkpabAAqh/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href=https://drive.google.com/file/d/1MiVLW_Yrho9s7g1FJL7Ka8m9qLs0GuW-/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href="https://drive.google.com/your-winding-specification-link" target="_blank">Click here</a></td>
            <td><a href="https://drive.google.com/your-assembly-drawing-link" target="_blank">Click here</a></td>
        </tr>
        <tr>
            <td><span class="new-star">NEW</span> IPL 332</td>
            <td><a href=https://drive.google.com/file/d/1BKtJ3qLb_sCK4cf7yQfXbpZZ3u1ldcYI/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href=https://drive.google.com/file/d/10SgZGJwtEEtB8ROp5nicZiAWNDuLFnPD/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href=https://drive.google.com/file/d/1fQNsyEaXhesmEjxTRY3TcMSsGvBMhGYq/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href=https://drive.google.com/file/d/1Ivy9lQw75b7cOyOEaZZW4h1Yf8oINP-L/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href="https://drive.google.com/your-winding-specification-link" target="_blank">Click here</a></td>
            <td><a href="https://drive.google.com/your-assembly-drawing-link" target="_blank">Click here</a></td>
        </tr>
        <tr>
            <td><span class="new-star">NEW</span> IPL 329</td>
            <td><a href=https://drive.google.com/file/d/1n7mgvjSdzT0d49WhXGOw69C8Fua2CGHl/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href=https://drive.google.com/file/d/1nWbHJr70ahTuZ0mW1cdpGIKRaeLmyn4R/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href="https://drive.google.com/your-core-channel-pdf-link" target="_blank">Click here</a></td>
            <td><a href=https://drive.google.com/file/d/1vtgMSD4_bn4Uuw0GZzbe7wuYWDKJv_jO/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href="https://drive.google.com/your-winding-specification-link" target="_blank">Click here</a></td>
            <td><a href="https://drive.google.com/your-assembly-drawing-link" target="_blank">Click here</a></td>
        </tr>
        <tr>
            <td><span class="new-star">NEW</span> IPL 328</td>
            <td><a href=https://drive.google.com/file/d/165fxcDbd7GYVfDAN3fgw-dHwNMZWzJZM/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href=https://drive.google.com/file/d/1il9hMwTo9spdx7iwx8oJC5Y2SafxTNlt/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href=https://drive.google.com/file/d/1Ln1SBod3IO5-fXhg2dz72m06qTfeg8Vs/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href=https://drive.google.com/file/d/1xRtYaQpKqbIf_airnuT1GeSYCsx0BnyQ/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href="https://drive.google.com/your-winding-specification-link" target="_blank">Click here</a></td>
            <td><a href="https://drive.google.com/your-assembly-drawing-link" target="_blank">Click here</a></td>
        </tr>
        <tr>
            <td><span class="new-star">NEW</span> IPL 326</td>
            <td><a href=https://drive.google.com/file/d/1t_83ajwpX43klfufHC67epfWDrdQIpl_/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href=https://drive.google.com/file/d/1Rw4LLS84sbgQcFzLuYs61RnClkP8AWL7/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href=https://drive.google.com/file/d/1S-DOcJOkmCii9Xlx7Phor8TF-XbjmSQc/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href=https://drive.google.com/file/d/18rt4_l7dkKteYvbPUAFHpTqdNays-Tjj/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href="https://drive.google.com/your-winding-specification-link" target="_blank">Click here</a></td>
            <td><a href="https://drive.google.com/your-assembly-drawing-link" target="_blank">Click here</a></td>
        </tr>
        <tr>
            <td><span class="new-star">NEW</span> IPL 323</td>
            <td><a href=https://drive.google.com/file/d/1Yj_AGolFO1x6_6ecQeQTAnmF7Ust0bIz/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href=https://drive.google.com/file/d/1L0gIf1CmBC_pS4_ZpslK1_umEw5Gqoj2/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href=https://drive.google.com/file/d/1Bg5DqkWVvTWSOjiXrHbmUXE9PRRczoHJ/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href=https://drive.google.com/file/d/1AK-VrZxTI8ScA4bZbUru6_7LpC-5co8E/view?usp=sharing target="_blank">Click here</a></td>
            <td><a href="https://drive.google.com/your-winding-specification-link" target="_blank">Click here</a></td>
            <td><a href="https://drive.google.com/your-assembly-drawing-link" target="_blank">Click here</a></td>
        </tr>
    </table>
</div>

<div class="footer">
    <p>&copy; 2025 All Rights Reserved</p>
    <p>Visit our website: <a href="https://www.iplproducts.com" target="_blank">www.iplproducts.com</a></p>
</div>

<script>
    function toggleMenu() {
        var menuContent = document.getElementById("menuContent");
        menuContent.style.display = (menuContent.style.display === "none" || menuContent.style.display === "") ? "block" : "none";
    }

    function toggleProjectStatus() {
        var status = document.getElementById("projectStatus");
        status.style.display = (status.style.display === "none" || status.style.display === "") ? "block" : "none";
    }

    function toggleTestReports() {
        var reports = document.getElementById("testReports");
        reports.style.display = (reports.style.display === "none" || reports.style.display === "") ? "block" : "none";
    }

    function toggleAboutUs() {
        var about = document.getElementById("aboutUs");
        about.style.display = (about.style.display === "none" || about.style.display === "") ? "block" : "none";
    }

    function toggleContactUs() {
        var contact = document.getElementById("contactUs");
        contact.style.display = (contact.style.display === "none" || contact.style.display === "") ? "block" : "none";
    }

    function toggleDevelopers() {
        var developers = document.getElementById("developers");
        developers.style.display = (developers.style.display === "none" || developers.style.display === "") ? "block" : "none";
    }
</script>

</body>
</html>
