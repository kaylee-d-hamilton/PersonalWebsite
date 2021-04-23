<html>
    <h1>Kaylee Hamilton's Personal Website</h1>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        body {
            font-family: Arial;
            background-color: lightpink;
        }

        /* Style the tab */
        .tab {
            overflow: hidden;
            border: 1px solid #ccc;
            background-color: #f1f1f1;
        }

            /* Style the buttons inside the tab */
            .tab button {
                background-color: inherit;
                float: left;
                border: none;
                outline: none;
                cursor: pointer;
                padding: 14px 16px;
                transition: 0.3s;
                font-size: 17px;
            }

                /* Change background color of buttons on hover */
                .tab button:hover {
                    background-color: #ddd;
                }

                /* Create an active/current tablink class */
                .tab button.active {
                    background-color: #ccc;
                }

        /* Style the tab content */
        .tabcontent {
            display: none;
            padding: 6px 12px;
            border: 1px solid #ccc;
            border-top: none;
        }
    </style>
</head>
<body>


    <div class="tab">
        <button class="tablinks" onclick="openCity(event, 'Home')">Home</button>
        <button class="tablinks" onclick="openCity(event, 'AboutMe')">About Me</button>
        <button class="tablinks" onclick="openCity(event, 'Skills')">Skills</button>
        <button class="tablinks" onclick="openCity(event, 'Projects')">Projects</button>
        <button class="tablinks" onclick="openCity(event, 'Employment')">Employment</button>
    </div>




    <div id="Home" class="tabcontent">
        <h3>Home</h3>
        <div>
            <p style="font-size: 20px; border:solid; border-width: 4px;">
                <b>
                    Hi! Welcome to my personal website. The purpose of this website is the showcase my accomplishments as an undergraduate student while developing my skills as a programmer using HTML, MVC, and CSS. Click <a href="https://drive.google.com/file/d/1zqvhulXFgi_MGrc3KndAV2IZffXgLN0w/view?usp=sharing">here</a> to view my resume and click <a href="https://www.linkedin.com/in/kayleedhamilton/">
                        here
                    </a> to view my LinkedIn profile.
                </b>
            </p>

        </div>

        <div style="padding-left: 40%">
            <img src="https://media-exp1.licdn.com/dms/image/C4E03AQEzketI0BvxCg/profile-displayphoto-shrink_200_200/0/1590808563016?e=1624492800&v=beta&t=jkgz_g2NkEpUmhvntkV4muFiprBYASFuexRfRpgaorw" />
        </div>
    </div>
    
    
    
    
    
    
    
    
    

    <div id="AboutMe" class="tabcontent">
        <h3>About Me</h3>

        <p style="border:solid; border-color:black; border-width: 4px;">
            <b>
                My name is Kaylee Hamilton and I am a junior at the University of Oklahoma studying Accounting and MIS. I plan to pursue my Master's degree in Accounting and graduate in May of 2023.
                During my time at OU, I have been apart of many student organizations and held several leadership roles. I currently am a member of Pi Beta Phi sorority where I have served on the executive
                council for two years as Vice President of Communications and Vice President of Finance and Housing. Additionally, I am a part of the JCPenney Leadership Program and Beta Alpha Psi. I
                also am I Price College Ambassador and share my experiences at Price with prospective students. In terms of community service outreaches, I have been a part of OU Dance Marathon, OU Big
                Event, and OU Relay For Life. I also volunteered weekly with Champions Are Readers where I read to first graders at Norman's local elementary school. While I am not a full time student, I
                enjoy visiting with friends and family, playing sports, and reading. After graduation, I plan on sitting for my CPA exam and pursing a career in auditing in the DFW area.
            </b>
        </p>


        <div style="float:left;">
            <img src="https://upload.wikimedia.org/wikipedia/en/thumb/5/56/University_of_Oklahoma_seal.svg/1200px-University_of_Oklahoma_seal.svg.png" style="width: 18%" />

            <img src="https://upload.wikimedia.org/wikipedia/en/6/62/Pi_Beta_Phi_crest.png" style="width: 18%" />

            <img src="https://pbs.twimg.com/profile_images/1027888354849972224/9Pl2eJs9_400x400.jpg" style="width: 18%" />

            <img src="https://ou-dance-marathon.square.site/uploads/b/d7badd317282907db616f2e860e6eb81590ea22bdd53d28b1ac9a439cb84157a/OUDM_1601482320.png" style="width: 18%" />

            <img src="https://www.goodaccountants.com/blog/wp-content/uploads/2012/03/CPA-certified-public-accountant.gif" style="width: 18%" />


        </div>

    </div>
    
    
    
    
    
    
    

    <div id="Skills" class="tabcontent">
        <h3>Skills</h3>

        <div style="border:solid; border-width: 4px;">
            <p>
                <b>
                    My technical skills include...
                    <ul>
                        <li>C#</li>
                        <li>SQL</li>
                        <li>VBA</li>
                        <li>Microsoft Office</li>
                        <li>Knowledge of SAP ERP</li>
                    </ul>
                </b>
            </p>
        </div>
    </div>

    <div id="Projects" class="tabcontent">
    

       <h3>Projects</h3>
        <div style="border:solid; border-width:4px">

    <p>
        <b>
            As a student at OU, I have had the chance to work on many different projects in various team settings. A project I am most proud of is my Database Milestone Project
            for my Databases course. My team and I were tasked to develop a funtional database for a fictional company to track information pertaining to their sales, customers,
            production, and purchases. After meeting with our fictional client to discuss unclear demands, we started an ERD diagram to illustrate the reationships and help                build our entities in Microsoft SQl Server. We then implemented entities into SQL Sever and after a lot of denormalization and debugging, we created SQL statements             that outputted what the client needed.


        </b>
    </p>

    <p> <b>Here is the final Database Project: <a href="https://drive.google.com/file/d/15ShfmBGJGAOcQkuGZbZQKja6nUTcTHiT/view?usp=sharing">Database Final Project</a></b></p>



    </div>
    
    
    
    
    
    
    
   <div id="Employment" class="tabcontent">


        <h3>Employment History</h3>
    
        <div style="border:solid; border-width:4px">

            <p>
                <b>
            My most recent employment was with Buchanan Clarke Schlader in Colleyville, Texas during summer of 2020. I worked as a Forensic Accounting Intern where I helped estimate the forgone business income on several insurance claims. A lot of my tasks included data entry and data analysis for several large clients, creating partial financial statements, and working on a handful of litigation cases. During summer of 2021, I will be working with Paycom as a Database Administrator Intern in Oklahoma City, Oklahoma. During spring of 2022, I will be working with Deloitte as an Audit and Assurance Intern in Dallas, Texas. Finally, in summer of 2022, I will be working with Grant Thorton as an Audit Intern in Tulsa, Oklahoma.
                 </b>
            </p>
        </div>
    
    </div>
    
    
    
    
    

    <script>
    
function openCity(evt, cityName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}
    </script>

 
