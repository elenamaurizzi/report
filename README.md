r<html>
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
  <a href="https://elenamaurizzi.github.io/home/" href="#home">HOME</a>
  <a href="https://elenamaurizzi.github.io/articolo1prova/">ARTICLE 1</a>
  <a href="https://elenamaurizzi.github.io/article2prova/">ARTICLE 2</a>
  <a href="https://elenamaurizzi.github.io/article3prova/">ARTICLE 3</a>
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
      margin-left: 80px;
      text-align: center;
    }

    .article-image {
      flex: 1;
      margin-left: 160px;
      margin-right: -60px;
    }

    .text-article {
        flex: 1;
        text-align: center;
        margin-right: 80px;;
    }

    .image-article {
      flex: 1;
      margin-left: 80px;
      margin-right: 0px;
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
    opacity: 0.8;
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
  <img src="header.jpg" alt="Reports" style="width:100%;">
  
  <div class="centered"><h1 align="centered"><span style="font-family: Georgia, serif;">OUR REPORTS</span></h1></div>

</div>
<br><br><br>

  
  
   <div class="article">
      <div class="image-article">
      <img src="CD.jpg" alt="Article Image" width="500" height="800"><br><br><br><br>
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
                some years appeared more than once on the x-axis, but the issue at hand was solved through a BIND clause - BIND(YEAR(?date) AS ?label). 
                Broadly speaking, the more time we spent familiarising ourselves with our tools, the easier it got to face all manner of challenges, 
                and to create an engaging data story.
                  </p>
    </div> 
      
  </div>

<br><br>


      <div class="article">
    <div class="article-text">
  <h1><span style="font-family:'Times New Roman', Times, serif; color:black">Best female music artists</span></h1>
<h2>Methodology, tools and data sources</h2>
    <p align="justify"> The starting point of our research was the Polifonia corpus. Initially, we explored the MusicBo module, but we did not find any information about modern female artists or even about female artists in general. Therefore, we selected “Wikipedia” as a module and we got interesting results by typing some keywords, namely “album”, “women” and “female”. In particular, we had different occurrences for “female album” and this guided us to the decision of the final topic of our research: the best female music artists. 
For our research we decided to use the DBpedia Sparql Endpoint to explore the knowledge graph provided by DBpedia. After defining all the standard prefixes, such as rdf, rdfs and all those required by DBpedia ontology, we started to query over the knowledge graph using SPARQL language and a significant number of operators that were useful to constraint the values that we wanted to retrieve. In particular, we used: FILTER regex, ORDER BY, COUNT, OPTIONAL, DISTINCT, BIND, MINUS, LIMIT and GROUP BY.
Moreover, for the definition of the prefixes and for the construction of the queries we explored the knowledge graph to see, for instance, with what type of queries were we dealing with and whether we got a resource, or a property or a value. 
Finally, we put all the queries used on Melody platform and created our web-ready story that is made of several graphics (table, doughnut chart, bar chart etc.). These help to drive the understanding of the audience of the topic's research, allowing all viewers to visualize all data and information that we retrieved in the exploration of the aforementioned knowledge graph.
</p>

<h2>The challenges</h2>
<p align="justify"> The first challenge we had to face was the display of the images on Melody, since we got the IRI of the resource from DBpedia but not the depiction itself. In the first place, we tried to change the property from dbo:thumbnail to foaf:depiction, but in this way, we could see the images but there were multiple for each resource. Therefore, we tried to get one picture of each resource by using the SAMPLE operator, but we still had some problems with duplicates. Eventually, we decided to use the dbo:thumbnail together with the operator BIND(REPLACE(str(A),””,) AS B), as suggested by the professor. Even though we managed to get the picture, we still had problems with one image, since it was not available on its DBpedia page anymore. For this reason, we decided to leave the picture out, using the MINUS operator, so as to have a more aesthetically pleasing table. 
Then, another challenge we encountered was that, even if we used the operator DISTINCT, we got multiple results for each resource. So, to solve this problem, we used the operator GROUP BY. Moreover, we cannot have links that work on Melody, because we see only their strings and not the functioning links. Even though we added “Label” to the variable, we did not get the expected result. 
In general, sometimes Melody was not working properly, so we had to stop and wait until it worked again or we tried several times to upload the changes before getting the result we wanted. 
In conclusion, despite all the challenges that we encountered, in the end we are satisfied with the outcome of the project. 
      </p>
    </div> 
    <div class="article-image">
      <img src="/cant.jpeg" alt="Article Image" width="500" height="800"><br><br><br><br>
          </div>  
  </div>
  
  
<br><br><br>
     <div class="article">
          </div>
    <div class="text-article">
  <h1><span style="font-family:'Times New Roman', Times, serif; color:black">ARTICLE 3</span></h1>
   <h2>Methodology, tools and data sources</h2>
    <p align="justify">The project initially started with the intention of utilizing the Polifonia module “Music Bo” to gather information. Upon realizing the limited information available through the Music Bo module, we decided to shift our focus to Wikipedia. This choice provided access to a wider range of data, thereby inspiring the project to proceed in a more fruitful direction. Subsequently, we initiated the process by collecting pertinent data from Wikidata, which served as the fundamental basis for our research and to extract relevant information related to the indie rock genre. Starting from a general point of view, we narrowed down our search to identify the most famous bands within the indie rock genre. To accomplish this, we scrutinized the queries that had been covered during our classes and began generating novel queries to address our inquiries. All the acquired data underwent a deep examination to detect noteworthy correlations and trends. Every time we formulated a new query, our aim was to execute it on MELODY platform, as to obtain a visual representation of our findings. The use of data visualization played a central role not just in presenting the project's discoveries but also in enabling us to examine deeper into comprehending the data. Consequently, MELODY facilitated our creation of tables, charts, and graphs, all aimed at showing the progression of indie rock music, particularly in the analysis of the musical contributions made by two iconic bands: Blur and Sonic Youth.
      </p>

      <h2>The challenges</h2>
<p align="justify">ADD PHRAGRAPH
      </p>
    </div> 
  </div>

  <div class="image-article">
      <img src="concert.jpg" alt="Article Image" width="500" height="800"><br><br><br><br>
  
<br>
  
<footer>
  <p>All rights reseved to...</p>
</footer>
</body>
</html>
