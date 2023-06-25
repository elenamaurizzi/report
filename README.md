<html>
<head>

<title>Our reports</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  margin: 0;
  font-family: 'Times New Roman', Times, serif;
}

.topnav {
  overflow: hidden;
  background-color: #353535;
}

.topnav a {
  float: left;
  color: #fff;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
  font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}


</style>
</head>

<body>

<div class="topnav">
  <a href="https://elenamaurizzi.github.io/prova/" href="#home">HOME</a>
  <a href="https://elenamaurizzi.github.io/articolo1prova/">ARTICLE 1</a>
  <a href="#ARTICLE 2 LINK">ARTICLE 2</a>
  <a href="#ARTICLE 3 LINK">ARTICLE 3</a>
  <a class="active">OUR REPORTS</a>
</div>

<meta name="viewport" content="width=device-width, initial-scale=1">
<style>

body {
      font-family: 'Times New Roman', Times, serif;
      background-color: #;
      color: #333;
      margin: 0;
      padding: 0px;
    }

    h1 {
      color: #FFF;
      font-family: 'Times New Roman', Times, serif !important;
      font-size: 36px;
      margin: 0;
    }

    h2 {
      color: #000000;
      font-family: 'Times New Roman', Times, serif !important;
      font-size: 22px !important;
      margin-top: 10px;
    }

    p {
        font-family: 'Times New Roman', Times, serif;
        font-size: 18px;
    }

    .article {
      display: flex;
      align-items: center;
      border: 1px solid #DDD;
      padding: 20px;
      margin-bottom: 20px;
      background-color: #FFF;
    }

    .article-text {
      flex: 1;
      margin-left: 150px;
      text-align: center;
    }

    .article-image {
      flex: 1;
      margin-left: 150px;
      margin-right: 0px;
    }

    .text-article {
        flex: 1;
        text-align: center;
        margin-right: 150px;
    }

    .image-article {
      flex: 1;
      margin-left: 40px;
      margin-right: 40px;
    }

    .section {
      margin-top: 0px;
    }


    .white-box {
      background-color: #FFF;
      border: 1px solid #DDD;
      padding: 20px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }


  </style>


</head>


<style>
.container {
  position: relative;
  text-align: center;
  color: white;
}

.container img {
    opacity: 1;
}

.centered {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -100%);
  color: #ffffff;
}

/* Style the footer */
footer {
  background-color: #f2f4f3ce;
  padding: 10px;
  text-align: center;
  color: rgb(0, 0, 0);
  font-family: 'Times New Roman', Times, serif;
  font-size: 15px;
}
</style>




<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">


<body>


<div class="container">
  <img src="records2.jpeg" alt="Reports" style="width:100%;">
  
  <div class="centered"><h1 align="centered"><span style="font-family: Georgia, serif;">OUR REPORTS</span></h1></div>

</div>
<br><br><br>

  
  
   <div class="article">
      <div class="image-article">
      <img src="ADD IMAGE" alt="Article Image" width="500" height="800"><br><br><br><br>
         </div>
    <div class="text-article">
  <h1><span style="font-family:'Times New Roman', Times, serif; color:black">ARTICLE 1</span></h1>
      <h2>Methodology, tools and data sources</h2>
    <p align="justify"> The exploration of albums distribution formats began with our analysis of the corpus Polifonia, which 
        provided valuable insights into the diverse formats used to distribute albums. One trend that particularly caught our 
        attention when looking into the keywords “CD” and “vinyl” was their juxtaposition / association / combination to words 
        such as “revival” or “era”, that prompted us to delve deeper into this phenomenon. To narrow down our research focus, 
        we decided to concentrate on the years between 2000 and 2020, as they encompass a significant period of change in the 
        music industry.
        For collecting the necessary data, we opted for Wikidata as our go-to SPARQL engine. Its extensive and well-structured 
        information on albums, distribution formats, and music streaming platforms made it an ideal resource. By creating SPARQL 
        queries, we were able to extract relevant data from Wikidata's vast collection. This included the number of albums released 
        between 2000-2020, specific distribution formats, founding dates and locations of music streaming platforms, and much more.
        To present our findings in an engaging manner, we used Melody. This tool allowed us to process and transform the data 
        extracted from Wikidata into meaningful and interactive charts. These visuals, such as bar charts and maps, allow readers 
        to easily comprehend and compare key trends. Moreover, they enhance the storytelling aspect, making the data more engaging and memorable.        
      </p>
            <h2>The challenges</h2>
<p align="justify">Particularly in the earlier stages of data collection, most challenges encountered stemmed from our initial 
    unfamiliarity with the tools, and from our uncertainty about what kind of information was available to us and how it was organised 
    within the Wikidata knowledge graph. We had to come to terms with entities lacking crucial information; in some instances, the data 
    retrieved was either not up-to-date or even unreliable (we stumbled upon an album that was allegedly released in 2171!). Faced with 
    these kinds of issues, we had to take – on more than one occasion – a step back to readjust our course of action, modifying the plans 
    for our data story. Be that as it may, some good actually came from tackling the above-mentioned challenges: in the long run, they 
    pushed us to detach ourselves from the query models used in class and to adopt a creative problem-solving mindset, which turned out 
    to be pivotal in the process of query writing. For instance, we encountered an unexpected problem whilst writing the query for the 
    line chart showcasing the number of albums released on CD format/vinyl per year: even though we used the SELECT DISTINCT statement, 
    some years appeared more than once on the x-axis, but the issue at hand was solved through a BIND clause (BIND(YEAR(?date) AS ?label)). 
    Broadly speaking, the more time we spent familiarising ourselves with our tools, the easier it got to face all manner of challenges, 
    and to create an engaging data story.
      </p>
    </div> 
      
  </div>

<br><br>


      <div class="article">
    <div class="article-text">
  <h1><span style="font-family:'Times New Roman', Times, serif; color:black">ARTICLE 2</span></h1>
<h2>Methodology, tools and data sources</h2>
    <p align="justify">    
      </p>

      <h2>The challenges</h2>
<p align="justify">
      </p>
    </div> 
    <div class="article-image">
      <img src="ADD IMAGE" alt="Article Image" width="500" height="800"><br><br><br><br>
          </div>  
  </div>
  
  
<br><br><br>
     <div class="article">
      <div class="image-article">
      <img src="ADD IMAGE" alt="Article Image" width="500" height="800"><br><br><br><br>
          </div>
    <div class="text-article">
  <h1><span style="font-family:'Times New Roman', Times, serif; color:black">ARTICLE 3</span></h1>
   <h2>Methodology, tools and data sources</h2>
    <p align="justify">ADD PHRAGRAPH
      </p>

      <h2>The challenges</h2>
<p align="justify">ADD PHRAGRAPH
      </p>
    </div> 
  </div>
  
<br>
  
<footer>
  <p>All rights reseved to...</p>
</footer>
</body>
</html>
