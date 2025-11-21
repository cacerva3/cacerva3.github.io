# cacerva3.github.io
/* Healthy Smiles CSS with Custom Theme Colors */
:root {
--text: #050315;
--background: #fbfbfe;
--primary: #1e90ff;
--secondary: #00bfff;
--accent: #ffffff;
}


body {
font-family: Arial, sans-serif;
margin: 0;
padding: 0;
background: var(--background);
color: var(--text);
line-height: 1.6;
}


header {
display: flex;
justify-content: space-between;
align-items: center;
padding: 20px;
background: #ffffff;
border-bottom: 2px solid #ddd;
}


nav a {
margin: 0 15px;
text-decoration: none;
font-weight: bold;
color: #333;
font-size: 18px;
}


.stories-box {
flex: 1;
background: white;
padding: 20px;
border: 1px solid #ccc;
min-height: 350px;
}


footer a {
text-decoration: none;
color: var(--text);
font-weight: bold;
transition: color 0.3s ease;
}
footer a:hover {
color: var(--primary);
}
