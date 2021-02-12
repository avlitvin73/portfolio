<template>
    <section>
        <div class="header">
            <nuxt-link to="/" class="td-none"><h1>portfolio</h1></nuxt-link> 
        </div>
        <div class="article">
            <p>I am a modern Front-End engineer, currently using my skills as a guide for very young web development lovers to determine their direction.</p>
            <p>The thought that my knowledge is being used by someone else, and most importantly, it is all available for free, is very helpful to me.</p>
            <p>I have 3 years of experience in creating websites.</p>
            <p>I love the power that JavaScript gives me and the way I can program styles with CSS.</p>
            <p>
                When I am not programming at work, I maintain my social life. 
                It takes a lot of time to be a good friend, but I enjoy every moment of it. 
                I love to spend time with my family, I have a dog. I also have a hobby when I shoot a bow.
            </p>
        </div>
        <div class="signature">
            <a href="https://telegram.me/avlitvin" class="td-none"><p>+7-977-954-71-65</p></a>
            <a href = "mailto: av.litvin73@gmail.com" class="td-none"><p>av.litvin73@gmail.com </p></a>    
        </div>

            

        
    </section>    
</template>


<style>
section {
    max-width: 43em;
    margin: auto;
    padding: 1rem;
    font-size: 1rem;
    font-family: Helvetica;
    color: #444;
    user-select: none; 
}

.article p{
    margin: 15px 0;
    line-height: 1.5;
}

.signature {
    display: flex;
    flex-direction: column;
    float: right;
    text-align: right;
    margin-top: 1em;
}

a {
    color: #35495e;
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