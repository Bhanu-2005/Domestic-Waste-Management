# Domestic-Waste-Management
hackathon
CBP09- Domestic Waste Management
Ideas which we implemented in our project
1. Home: Provide an overview of the website and its purpose, along with quick tips for waste management at home.

2. Recycling Guide: Create a comprehensive guide on different types of waste and how to recycle them properly. Include information on recycling centers and drop-off locations in your area.
3. Waste Reduction Tips: Share practical tips and ideas on how to reduce waste in everyday life, such as using reusable bags, avoiding single-use plastics, and buying in bulk.

4. Educational Resources: Compile informative articles, videos, and infographics about waste management, recycling, and sustainability to help users learn more about the topic.
5. Social media
6. code :
html:-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Community Waste Management</title>
    <link rel="stylesheet" href="">
</head>
<body>
    <div class="header">
        <h1>DOMESTIC WASTE MANAGEMENT</h1>
    </div>
    <div class="section">
        <h2>ABOUT D.W.M</h2>
        <p>Domestic waste (also known as household waste) is any waste that is generated in the home from day-to-day activities.</p>
        <p>What is Domestic Waste Management?:</p>
        <ul>
            <li>Domestic waste disposal is an issue that is important to the management of any urban area. Cities without a functioning waste-disposal plan face risks of disease running rampant.</li>
            <li>economic activity grinding to a halt.</li>
            <li>The majority of North American cities use the sanitary-landfill method of waste disposal.</li>
            <li> which has served fairly well for quite a while; however, in situations where space is at a premium.</li>
            <li>incineration and material-recycling-based waste disposal are more likely to come to the forefront..</li>
        </ul>
    </div>
        <div class="event">
            <div class="event-title">ENVIRONMENTAL POLLUTION</div>
            <div class="event-description">Environmental pollution is unwarranted disposal of mass or energy into earth's natural resource pool such as water, land, or air that results in long- or short-term detriment to the atmosphere and its ecological health to negatively impact the living beings and their life both quantitatively and qualitativelY.</div>
            <div class="event-link"><a href="READMORE.HTML">READ MORE</a></div>
        </div>
        <div class="event">
            <div class="event-title">AWARENESS & EDUCATION</div>
            <div class="event-description">Definitions of education aim to describe the essential features of education. A great variety of definitions has been proposed. There is wide agreement that education involves, among other things, the transmission of knowledge.</div>
            <div class="event-link"><a href="READMORE2.HTML">READ MORE</a></div>
        </div>
    </div>
    <section id="external_links">
        <h2>External Links</h2>
        <button><a href="" target="_blank">Example Website</a></button>
        <button><a href="" target="_blank">Another Example Website</a></button>
    </section>
    <footer>
        <p>&copy; 2024 Community Waste Management. All rights reserved.</p>
    </footer>
    <script>
        document.getElementById('').addEventListener('click', function() {
            window.open('', '_blank');
        });
        document.getElementById('').addEventListener('click', function() {
            window.open('', '_blank');
        });
    </script>
</body>
</html>
css:-.header {
    background-image: url("1592292414_LPLxtK_LPU.jpg");
    background-size: cover;
    background-position: center;
    height: 350px;
}



.header h1 {
    color: rgb(22, 162, 209);
    font-size: 100;
    text-align: center;
    padding-top: 100px;
}

.section {
    padding: 20px;
}

.header h2{
    text-align: center;
    margin-bottom: 20px;
}

.header h2 {
    background-color: rgb(13, 240, 210) ;
    border: 1px solid #11dae1;
    border-radius: 20px;
    margin-bottom: 40px;
    padding: 10px;
}

.event-title {
    font-weight: bold;
    font-size: 20px;
}

.event-date {
    color: #eb1fcc;
    font-size: 15px;
}

.event-description {
    font-size: 18px;
}

.event-link {
    text-decoration: none;
    color: #f71bcb;
}

#external_links {
    text-align: center;
}
#external_links button {
    margin: 10px;
}
#external_links button a {
    color: #fff;
    text-decoration: none;
}
#external_links button:hover {
    background-color: #e68a00;
}
