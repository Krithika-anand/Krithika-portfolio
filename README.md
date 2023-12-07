# Krithika-portfolio
[link] (https://krithika-anand.github.io/Krithika-portfolio/)

# website-homepage

![Alt text](image-4.png)

# css grid

![Alt text](image-2.png)

<section id="projects" class="container">
        <div class="textshadow">
            <h3>Projects</h3>
        </div>
        
            <div id="categoryGrid" class="textborder">
                <div id="architecture" class="categoryGridArea">
                    <a href="https://www.instagram.com/kadv_studioarchitecture/?igshid=YmMyMTA2M2Y%3D"
                        class="heading">Architecture</a>
                </div>

                <div id="interiordesign" class="categoryGridArea">

                    <a href="https://www.instagram.com/kadv_studioarchitecture/?igshid=YmMyMTA2M2Y%3D"
                        class="heading">Interior Design</a>
                </div>

                <div id="uxDesign" class="categoryGridArea">
                    <a href="#uxDesign" class="heading">UX-Design</a>
                </div>

                <div id="webDev" class="categoryGridArea">

                    <a href="https://github.com/Krithika-anand" class="heading">Web Development</a>
                </div>

                <div id="others" class="categoryGridArea">
                    <a href="#projects" class="heading">More..</a>
                </div>
            </div>
       
    </section>

# hover effect

.textshadow:hover{ 

    color: #452a2a;
    text-shadow: 0px 2px 5px rgb(171, 171, 113)

}

#.heading:hover{

    background-color: rgb(68, 67, 67, .9);
    text-shadow: rgba(68, 31, 31, 0.9);

}

# media query 

## container grid

###

#categoryGrid 
{

    grid-template-rows: 175px 175px 175px 175px 175px;
    grid-template-columns: 1fr;
    grid-template-areas:
      "architecture"
      "interiordesign"
      "uxDesign"
      "webDev"
      "others";
    background-position: center;
    background-size: cover;
    max-width: fit-content;
  }


 ![Alt text](image-3.png) 