<template>
    <section>
        <div class="header">
            <nuxt-link to="/" class="td-none"><h1>portfolio</h1></nuxt-link> 
        </div>
        <div class="projects">
            <div class="project">
                <div class="description">
                    <h3>Project-cat</h3>
                    <p>Cute cat assembled from a div. His eyes follows a special cursor.</p>
                </div>
                <div class="links">
                    <a class="td-none" target="_blank" href="https://avlitvin73.github.io/project-cat/index.html">view</a>
                    <a class="td-none" target="_blank" href="https://github.com/avlitvin73/avlitvin73.github.io/tree/main/project-cat">code</a> 
                </div>
  
            </div>
            <div class="project">
                <div class="description">
                    <h3>3D-cube</h3>
                    <p>Great cube that spins in all planes. Keyboard arrows work.</p>
                </div>  
                <div class="links">  
                    <a class="td-none" target="_blank" href="https://avlitvin73.github.io/project-box/index.html">view</a>
                    <a class="td-none" target="_blank" href="https://github.com/avlitvin73/avlitvin73.github.io/tree/main/project-box">code</a>   
                </div>    
            </div>
            <div class="project">
                <div class="description">
                    <h3>Register-form</h3>
                    <p>Awesome registration form with a palm tree.</p>
                </div>  
                <div class="links">   
                    <a class="td-none" target="_blank" href="https://AwesomeForm.pylearn-2017.repl.co/">view</a>
                    <a class="td-none" target="_blank" href="https://repl.it/@Pylearn_2017/AwesomeForm">code</a>   
                </div>      
            </div>
            <div class="project">
                <div class="description">
                    <h3>Analog-clock</h3>
                    <p>Modern clock with arrows. Works super quiet.</p>
                </div>   
                <div class="links">  
                    <a class="td-none" target="_blank" href="https://analogclock.pylearn-2017.repl.co/">view</a>
                    <a class="td-none" target="_blank" href="https://repl.it/@Pylearn_2017/AnalogClock">code</a>   
                </div>  
            </div>        
            <div class="project">
                <div class="description">
                    <h3>Video-sphere</h3>
                    <p>Nice wrapper video file in a sphere.</p>
                </div>  
                <div class="links"> 
                    <a class="td-none" target="_blank" href="https://videosphere.pylearn-2017.repl.co/">view</a>
                    <a class="td-none" target="_blank" href="https://videosphere.pylearn-2017.repl.co/">code</a>   
                </div>  
            </div>
            
        </div>
    </section>    
</template>



<style>

@media (max-width: 650px) {
  .project {
        display: flex;
        flex-direction: column;
        margin: 10px;
  }
  .links {
      display: flex;
      /* justify-content: space-between; */
      line-height: 1;
      padding: 5px;
  }
  .description h3{
      margin-left: -10px;
  }

}



section {
    max-width: 43em;
    margin: auto;
    padding: 1rem;
    font-size: 1rem;
    font-family: Helvetica;
    color: #444;
    line-height: 1.5;
    user-select: none; 
}

.project {
    display: flex;
    justify-content: space-between;
    margin: 10px;
}

.project a {
    margin-right: 15px;

}

.header {
    display: flex;
    justify-content: center;
    margin-top: 1em;
    margin-bottom: 2rem;
    font-size: 1rem;
    font-family: Helvetica;
}

</style>